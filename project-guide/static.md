# 静态文件

> 如无特殊说明，本文中的静态文件是指web项目中的图片、css、js等静态资源而言（有cdn的需求）


1. 为了便于部署时使用cdn加速，静态文件应该统一存放于项目根目录下的```static```文件夹中

2. 为了便于统一管理，favicon.ico文件也应该放置于static文件夹中， 在html中使用link方式引用

    ```html
    <!DOCTYPE html>
    <html>
    <head>
    <title>标题</title>
    <link rel="shortcut icon" href="http://www.xxx.com/图标的地址.../favicon.ico">
    </head>
    ... ...
    ```

3. 引用静态文件时，**不要用绝对路径**，可以使用django的static模板标签，或flask的url_for自动生成

    * django 静态文件引用示例

    ```html
    {% raw %}
    {% load staticfiles %}
    <img src="{% static "my_app/myexample.jpg" %}" alt="My image"/>
    {% endraw %}
    ```

    * flask 静态文件引用示例

    ```html
    {% raw %}
    <img src="{% url_for "my_app/myexample.jpg" %}" alt="My image"/>
    {% endraw %}
    ```

    * 错误的静态文件引用方式

    ```html
    <img src="/static/img/pic1.jpg" alt="My image"/>
    ```
