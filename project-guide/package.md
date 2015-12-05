# 包和依赖

1. 如无特殊情况，项目的包管理器**一律使用pip**

2. 项目**根目录下必须包含requirements.txt文件**，作为项目依赖的显示声明文件

3. 所有依赖都必须显示声明，禁止隐式依赖，例如：

    ```python
    # 错误，依赖的wget在别的系统环境下很可能不存在
    def download(url):
        os.system('wget %s' % url)
    ```
    以上代码隐式依赖了wget，但很有可能开发环境中有wget，而在部署环境下根本不存在，
    这样部署app时就很可能出错！

4. 依赖声明文件中不应该包含项目中没有用到的依赖

5. 建议在开发项目时使用virtualenv做依赖隔离，便于使用pip freeze自动生成

    ```sh
    # 自动生成requirement.txt示例
    $ pip freeze > requirements.txt
    ```
