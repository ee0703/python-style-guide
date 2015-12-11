# 命名

## 应该避免的名称
以下命名应该尽量避免
* 单字符名称, 除了计数器和迭代器.

```python
if __name__ == '__main__':
    # 不推荐的写法
    # 尽量避免单字符变量名
    s = "hello world!"
```
* 包/模块名中的连字符(-)

```python
# 错误的包名
# 引用文件 html-parser.py
import html-parser

# 正确的写法
# 文件名应为 html_parser.py
import html_parser
```

* 双下划线开头并结尾的名称(Python保留, 例如\_\_init\_\_)
* 应避免使用小写字母l(L)，大写字母O(o)或I(i)单独作为一个变量的名称，以区分数字1和0

```python
if __name__ == '__main__':
    # 不推荐的写法
    # 尽量避免l、O 等容易混淆的字母
    l = 1
    O = 0
    l = (O + 1)*l
```

* 当参数名称和Python保留字冲突，可在最后添加一个下划线，而不是使用缩写或自造的词

```python
# 如果变量名和python保留字冲突，则在末尾添加下划线
# 切记不要自己造词，或者使用缩写
def print_():
    ... ...

if __name__ == '__main__':
    str_ = "hello world!"
    print_(str_)
```

## 命名约定

###  模块
* 模块尽量使用小写命名，首字母保持小写，尽量不要用下划线(除非多个单词，且数量不多的情况)

```python
# 正确的模块名
import decoder
import html_parser

# 不推荐的模块名
import Decoder
```

### 类名
* 类名使用驼峰(CamelCase)命名风格，首字母大写，私有类可用一个下划线开头

```Python
class Farm():
    pass

class AnimalFarm(Farm):
    pass

class _PrivateFarm(Farm):
    pass
```

* 将相关的类和顶级函数放在同一个模块里. 不像Java, 没必要限制一个类一个模块.

### 函数

* 函数名一律小写，如有多个单词，用下划线隔开

```python
def run():
    pass

def run_with_env():
    pass
```

* 私有函数在函数前加一个下划线_

```python
class Person():

    def _private_func():
        pass
```

### 变量名

* 变量名尽量小写, 如有多个单词，用下划线隔开

```python
if __name__ == '__main__':
    count = 0
    school_name = ''
```

* 常量采用全大写，如有多个单词，使用下划线隔开

```python
MAX_CLIENT = 100
MAX_CONNECTION = 1000
CONNECTION_TIMEOUT = 600
```
