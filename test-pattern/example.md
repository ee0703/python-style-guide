# 单元测试框架的选择


选择框架之前首先要确认一下我们的选项概念和她们之间的区别。


### PyUnit

PyUnit（The Python unit testing framework) 是 Kent Beck 和 Erich Gamma 所设计的 JUnit 的 Python 版本。从 Python 2.1 版本后，PyUnit 成为 Python 标准库的一部分。

这就是我们日常使用的 unittest 。它太过优秀了，以至于我们几乎没有必要再用别的测试框架了。

下面这个例子，是bottle框架下测试首页的简单例子，首先是bottle的代码：

```python
#!/usr/bin/env python
# encoding: utf-8
import bottle


@bottle.route('/')
def index():
    return 'Hi!'


if __name__ == '__main__':
    bottle.run()
```

这是单元测试的代码：

```python
#!/usr/bin/env python
# encoding: utf-8
import mywebapp
import unittest


class TestBottle(unittest.TestCase):
    def test_webapp_index(self):
        assert mywebapp.index() == 'Hi!'


if __name__ == '__main__':
    unittest.main()
```

直接运行这个文件就可以了，可以看到在普通模式，和verbosity模式下的返回结果:



普通模式:

```

.
----------------------------------------------------------------------
Ran 1 test in 0.000s

OK
```

verbosity模式:

```
test_webapp_index (__main__.TestBottle) ... ok

----------------------------------------------------------------------
Ran 1 test in 0.000s

OK
```

表示我们的测试都通过了。


### doctest

doctest 也是 Python 标准库的一部分。

doctest 可以用来写一些比较简单的测试，也可以用来检查文档和注释能否解释当前版本的代码。

### pytest

pytest 也是一个很流行的测试框架，是很多公司的首选。

看一份邮件流吧，一些工程师阐述了他们为什么会选择使用pytest: [我是邮件链接](http://thread.gmane.org/gmane.comp.python.testing.general/3748)

### nose

nose 并不是一个真正的测试框架，它只是一个很优秀的测试执行器，是unittest的拓展。

它的官方也是这样介绍自己的：nose extends unittest to make testing easier.

nose 可以运行由PyUnit(unittest), doctest，[pytest](https://github.com/pytest-dev/pytest)创建的测试。
