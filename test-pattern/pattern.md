
# 单元测试的书写规范


## 一个单元测试样例的规则

- 完全自动运行，而不需要人工干预。单元测试几乎是全自动的。
- 自主判断被测试的方法是通过还是失败，而不需要人工解释结果。
- 独立运行，而不依赖其它测试用例（即使测试的是同样的方法）。即，每一个测试用例都是一个孤岛。
- 每一个独立的测试都有它自己的不含参数及没有返回值的方法。如果方法不抛出异常而正常退出则认为测试通过;否则，测试失败。

## 测试文件的位置及命名规则


1. 为了编写测试用例，首先使该测试用例类成为unittest 模块的TestCase 类的子类。TestCase 提供了很多你可以用于测试特定条件的测试用例的有用的方法。
2. 所有测试样例放在项目根目录下的 test 文件夹中，如果你的所有测试都在一个文件中，也可以省略文件夹，直接把这个文件放在根目录下，命名为`test_your_project.py` (例如`test_requests.py`)。
3. 如前一个测试用例，创建一个继承于 unittest.TestCase 的类。你可以在每个类中实现多个测试（正如你在本节中将会看到的一样），但是我却选择了创建一个新类，因为该测试与上一个有点不同。这样，我们可以把正常输入的测试跟非法输入的测试分别放入不同的两个类中。
4. 测试本身是类一个方法，并且该方法以 test 开头命名。
5. 当你改变条件的时候，要确保同步更新那些提示错误信息的可读字符串。unittest 框架并不关心这些，但是如果你的代码抛出描述不正确的异常信息的话会使得手工调试代码变得困难。
6. 出现频率较多和不明朗的方法，需要加注释，比如`test_string`如果不加注释很难让人读懂测试的是哪一个 string。

我们以bottle的测试为例：

```python
import unittest
from tools import warn
from bottle import MakoTemplate, mako_template, mako_view, touni

class TestMakoTemplate(unittest.TestCase):
    def test_string(self):
        """ Templates: Mako string"""
        t = MakoTemplate('start ${var} end').render(var='var')
        self.assertEqual('start var end', t)

    def test_file(self):
        """ Templates: Mako file"""
        t = MakoTemplate(name='./views/mako_simple.tpl').render(var='var')
        self.assertEqual('start var end\n', t)

    # ...
```

