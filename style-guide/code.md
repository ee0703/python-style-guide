# 程序设计规范

## 避免'裸代码'

* 尽量不要直接将代码写在模块的顶层中，在执行主程序前应该总是检查 ``if __name__ == '__main__'`` , 这样当模块被导入时主程序就不会被执行.

```python
# 不推荐的写法(裸代码)
do_something()

# 正确的写法
def main():
    do_something()

if __name__ == '__main__':
    main()
```

所有的顶级代码在模块导入时都会被执行. 要小心不要去调用函数, 创建对象, 或者执行那些不应该在使用pydoc时执行的操作.

## 字符串

* 尽量不要用```+```号拼接字符串, 使用```%s```模板或```join```拼接

```Python
# 不推荐的写法
print("Spam" + " eggs" + " and" + " spam")
# 正确写法, 使用 join
print(" ".join(["Spam","eggs","and","spam"]))          
# 正确写法, 使用 %s 模板
print("%s %s %s %s" % ("Spam", "eggs", "and", "spam"))
```
## 列表和字典

* 在不复杂的情况下, 尽量多用列表生成式, 可以使代码更加清晰  

**注意: 复杂情况下不适用, 列表生成式过复杂反而会导致阅读和调试困难**

```Python
# 不推荐的写法
items = []
for item in directory:
    items.append(item)

# 正确的写法
items = [item for item in directory]
```

* 尽量使用map和filter等内置函数, 而不是自己去写循环

```Python
numbers = [1, 2, 6, 9, 10 ...]

# 不推荐的写法
def even(numbers):
    evens = []
    for number in numbers:
        if number % 2 == 0:
            evens.append(number)
    return even

# 正确的写法
def even(numbers):
    return filter(lambda x: x%2 == 0, numbers)

```

## 正则表达式

* 正则表达式前一律加r

```Python
regex_phone = re.compile(r'(13\d|14[57]|15[^4,\D]))$')
```

* 正则表达式使用前尽量先编译好

```Python
# 不推荐的写法, 不要使用未编译的正则
result = re.match(r'(^(13\d|14[57]|15[^4,\D]))$', my_phone)

# 正确的写法，使用前先编译
regex_phone = re.compile(r'(13\d|14[57]|15[^4,\D]))$')

if __name__ == '__main__':
    result = regex_phone.match(my_phone)
```
