# Python的轮子 -- 常用的包、库、软件

一些比较好用的 Python 框架、库、软件等的合集, 基于[awesome-python](https://github.com/vinta/awesome-python).

- [目录](#常用的包、库、软件)
    - [Python环境管理](#Python环境管理)
    - [包管理工具](#包管理工具)
    - [打包发布工具](#打包发布工具)
    - [交互式工具(REPL)](#交互式工具（REPL）)
    - [文件](#文件)
    - [时间和日期](#时间和日期)
    - [文本处理](#文本处理)
    - [特定文本格式处理(word、excel、pdf、markdown等)](#特定文本格式处理（word、excel、pdf、markdown等）)
    - [自然语言处理](#自然语言处理)
    - [文档工具](#文档工具)
    - [配置](#配置)
    - [图片](#图片)
    - [文字识别(OCR)](#文字识别（OCR）)
    - [音频](#音频)
    - [视频](#视频)
    - [地理位置](#地理位置)
    - [HTTP](#http)
    - [数据库](#数据库)
    - [数据库驱动（连接件）](#数据库驱动（连接件）)
    - [数据库对象关系模型映射(orm)](#数据库对象关系模型映射（orm）)
    - [Web框架](#Web框架)
    - [内容管理系统(CMS)](#内容管理系统（CMS）)
    - [电子商务](#电子商务)
    - [RESTful API 框架](#restful-api-框架)
    - [授权(Authentication)](#授权（Authentication）)
    - [模版引擎](#模版引擎)
    - [任务队列](#任务队列)
    - [搜索工具](#搜索工具)
    - [Feed工具](#Feed工具)
    - [网站资源管理(压缩、最小化等)](#网站资源管理)
    - [缓存](#caching)
    - [电子邮件(email)](#电子邮件（email）)
    - [国际化(多语言)](#国际化(多语言))
    - [URL处理](#URL处理)
    - [HTML处理](#HTML处理)
    - [Web爬虫](#Web爬虫)
    - [Web内容解析](#Web内容解析)
    - [数据验证](#数据验证)
    - [管理界面](#管理界面)
    - [静态网站生成](#静态网站生成)
    - [进程管理](#进程管理)
    - [并发和并行](#并发和并行)
    - [网络](#网络)
    - [WebSocket处理](#WebSocket处理)
    - [WSGI服务器](#WSGI服务器)
    - [远程调用服务](#远程调用服务)
    - [加解密](#加解密)
    - [图形界面（GUI）](#图形界面（GUI）)
    - [游戏开发](#游戏开发)
    - [日志工具](#日志工具)
    - [测试](#测试)
    - [代码分析和优化](#代码分析和优化)
    - [调试工具](#调试工具)
    - [科学算和数据分析](#科学计算和数据分析)
    - [数据可视化](#数据可视化)
    -  [计算机图形学](#计算机图形学)
    - [机器学习](#机器学习)
    - [函数式编程](#函数式编程)
    - [MapReduce](#mapreduce)
    - [运维开发工具](#运维开发工具)
    - [任务调度](#任务调度)
    - [使用其它语言扩展Python](#使用其它语言扩展Python)
    - [高性能](#高性能)
    - [Windows工具](#Windows工具)
    - [网络虚拟化和SDN](#网络虚拟化和SDN)
    - [硬件](#硬件)
    - [兼容性](#兼容性)
    - [开发者插件](#开发者插件)
    - [IDEs](#ides)
- [Python资源](#Python资源)
    - [网站](#网站)
    - [网站](#网站)
    - [Twitter](#twitter)


- - -

## Python环境管理

*Python版本和虚拟环境管理.*

* [virtualenv](https://pypi.python.org/pypi/virtualenv) - 最常用的Python虚拟环境管理工具.
* [p](https://github.com/qw3rtman/p) - 非常简单的Python版本管理工具.
* [pyenv](https://github.com/yyuu/pyenv) - 简单的Python版本管理工具.
* [PyRun](https://www.egenix.com/products/python/PyRun/) - 一个单文件、免安装的Python运行环境.
* [Vex](https://github.com/sashahart/vex) - 在virtualenv中运行命令的工具.
* [virtualenvwrapper](https://pypi.python.org/pypi/virtualenvwrapper) - virtualenv的插件合集.

## 包管理工具

*包和依赖管理工具.*

* [pip](https://pip.pypa.io/) - 即Python Package Index, 最常用的Python包管理工具.
    * 官方网站 [Python Package Index](https://pypi.python.org/pypi)
* [pip-tools](https://github.com/nvie/pip-tools) - 保持pip的包最新的同步工具.
* [conda](https://github.com/conda/conda/) - 跨平台的二进制包管理工具.
* [Curdling](http://clarete.li/curdling/) - 命令行包管理工具.
* [wheel](http://pythonwheels.com/) - 标准Python打包工具（用来替代eggs）.


## 打包发布工具

*打包发布和安装包制作工具.*

* [PyInstaller](https://github.com/pyinstaller/pyinstaller) - 将Python程序转换为跨平台的可执行程序(客户无需安装python即可运行).
* [dh-virtualenv](http://dh-virtualenv.readthedocs.org/) - 将virtualenv环境打包成可发布的Debian软件包.
* [Nuitka](http://nuitka.net/) - 将python脚本、模块、包编译成可执行或可扩展模块.
* [py2app](http://pythonhosted.org/py2app/) - Python代码打包成 Mac OS X App 的工具.
* [py2exe](http://www.py2exe.org/) - Python转exe(Windows).
* [pynsist](http://pynsist.readthedocs.org/) - Windows安装包制作工具，会将Python一起打包.


## 交互式工具（REPL）

*交互式Python执行工具 (REPL).*

* [IPython](https://github.com/ipython/ipython) - 强大，比较常用的Python交互shell.
* [bpython](http://bpython-interpreter.org) – 一个便捷的Python交互工具.
* [ptpython](https://github.com/jonathanslenders/ptpython) - 先进的Python交互工具.

## 文件

*文件操作和MIME类型描述等.*

* [imghdr](https://docs.python.org/2/library/imghdr.html) - (Python内置标准库) 判断图片类型的库.
* [mimetypes](https://docs.python.org/2/library/mimetypes.html) - (Python内置标准库) 获取文件的MIME类型描述.
* [path.py](https://github.com/jaraco/path.py) - [os.path](https://docs.python.org/2/library/os.path.html)的便捷版本.
* [pathlib](https://pathlib.readthedocs.org/en/pep428/) - (Python3.4+ 内置标准库) 跨平台的文件路径库.
* [python-magic](https://github.com/ahupp/python-magic) - libmagic 的便捷版本.
* [Unipath](https://github.com/mikeorr/Unipath) - 一个面向对象的文件和目录操作库.
* [watchdog](https://github.com/gorakhargosh/watchdog) - 监视文件系统改动的库.

## 时间和日期

*关于时间和日期的库.*

* [arrow](https://github.com/crsmithdev/arrow) - 更好用的时间日期库.
* [Chronyk](https://github.com/KoffeinFlummi/Chronyk) - Python3 时间日期解析库.
* [dateutil](https://pypi.python.org/pypi/python-dateutil) - Python标准模块 [datetime](https://docs.python.org/2/library/datetime.html) 的扩展.
* [delorean](https://github.com/myusuf3/delorean/) - 处理跨时区、时间和日期的库.
* [moment](https://github.com/zachwill/moment) - 时间日期处理库，[Moment.js](http://momentjs.com/)的Python 版.
* [PyTime](https://github.com/shnode/PyTime) - 易用的的时间处理库，把date/time/datetime当成string来处理.
* [pytz](https://launchpad.net/pytz) - 世界时区的库. 使用 [tz database](http://en.wikipedia.org/wiki/Tz_database).
* [when.py](https://github.com/dirn/When.py) - 用户友好的时间日期操作库.

## 文本处理

*解析和操作普通文本的库.*

* 通用
    * [chardet](https://github.com/chardet/chardet) - 兼容 Python 2/3 的字符编码检测.
    * [difflib](https://docs.python.org/2/library/difflib.html) - (Python内置标准库) 差异计算工具.
    * [esmre](https://code.google.com/p/esmre/) - 正则表达式加速器.
    * [ftfy](https://github.com/LuminosoInsight/python-ftfy) - Unicode文本乱码自动修复.
    * [fuzzywuzzy](https://github.com/seatgeek/fuzzywuzzy) - 文本模糊匹配(包含相似度计算).
    * [Levenshtein](https://github.com/ztane/python-Levenshtein/) - 字符串莱文斯坦距离和相似度计算.
    * [pangu.py](https://github.com/vinta/pangu.py) - 中日韩文分词库.
    * [pyfiglet](https://github.com/pwaller/pyfiglet) - figlet的Python实现.
    * [shortuuid](https://github.com/stochastic-technologies/shortuuid) - 简洁，唯一，URL安全的UUID生成器.
    * [unidecode](https://pypi.python.org/pypi/Unidecode) - Unicode转ASCII.
    * [uniout](https://github.com/moskytw/uniout) - 打印可读的字符串（自动消除转义）.
    * [xpinyin](https://github.com/lxneng/xpinyin) - 将中文汉字转化为拼音.
* 字符串转义(Slugify)
    * [awesome-slugify](https://github.com/dimka665/awesome-slugify) - 不转换unicode的slugify库.
    * [python-slugify](https://github.com/un33k/python-slugify) - slugify库，将会把unicode转成ASCII.
    * [unicode-slugify](https://github.com/mozilla/unicode-slugify) - slugify库, 支持unicode.
* 解析器(Parser)
    * [phonenumbers](https://github.com/daviddrysdale/python-phonenumbers) - 解析、格式化、存储和验证电话号码.
    * [PLY](http://www.dabeaz.com/ply/) - lex 和 yacc 解析工具的python实现.
    * [Pygments](http://pygments.org/) - （编程语言）文本语法高亮工具.
    * [pyparsing](http://pyparsing.wikispaces.com/) - 通用parser生成框架.
    * [python-nameparser](https://github.com/derek73/python-nameparser) - 人名解析器（英文）.
    * [python-user-agents](https://github.com/selwin/python-user-agents) - 浏览器user-agent解析器.
    * [sqlparse](https://sqlparse.readthedocs.org/) - SQL语句解析器.

## 特定文本格式处理（word、excel、pdf、markdown等）

*解析和处理特定文本格式的库.*

* 通用
    * [tablib](https://github.com/kennethreitz/tablib) - XLS, CSV, JSON, YAML处理.
* Office
    * [Marmir](https://github.com/brianray/mm) -  把Python数据结构转化成表格.
    * [openpyxl](https://openpyxl.readthedocs.org/en/latest/) - 读写微软Excel 2010 xlsx/xlsm/xltx/xltm 文件.
    * [python-docx](https://github.com/python-openxml/python-docx) - 读写微软Word 2007/2008 docx文件.
    * [unoconv](https://github.com/dagwieers/unoconv) -  LibreOffice/OpenOffice 文档格式转化.
    * [XlsxWriter](https://xlsxwriter.readthedocs.org/) - 创建 .xlsx 文件的库.
    * [xlwings](http://xlwings.org/) - 读写 Excel.
    * [xlwt](https://github.com/python-excel/xlwt) / [xlrd](https://github.com/python-excel/xlrd) - 读写 Excel 文件.
    * [relatorio](http://relatorio.tryton.org/) - OpenDocument文件模版库.
* PDF
    * [PDFMiner](https://github.com/euske/pdfminer) - 读取PDF文档.
    * [PyPDF2](https://github.com/mstamy2/PyPDF2) - 切分、合并、转换PDF文档
    * [ReportLab](http://www.reportlab.com/opensource/) - 快速创建PDF文档.
* Markdown
    * [Mistune](https://github.com/lepture/mistune) - 快速，功能齐全的Markdown解析器.
    * [Python-Markdown](https://github.com/waylan/Python-Markdown) - John Gruber的Markdown的Python实现.
* YAML
    * [PyYAML](http://pyyaml.org/) - YAML的Python实现.
* CSV
    * [csvkit](https://github.com/onyxfish/csvkit) - CSV转化和操作库.
* 压缩文件
    * [unp](https://github.com/mitsuhiko/unp) - 压缩文件处理库（.tar, .gz, .zip, .7z, .bz, .rar 等）.

## 自然语言处理

*自然语言处理库.*

* [NLTK](http://www.nltk.org/) - 最常用的Python自然语言处理平台.
* [jieba](https://github.com/fxsjy/jieba) - 中文分词.
* [langid.py](https://github.com/saffsd/langid.py) - 自动判断语言类型（可判别英文、中文等97种语言）.
* [Pattern](http://www.clips.ua.ac.be/pattern) - 网络文本挖掘和分析.
* [SnowNLP](https://github.com/isnowfy/snownlp) - 中文文本处理库(分词、词性、情感分析等).
* [TextBlob](http://textblob.readthedocs.org/) - 便捷的NLP通用库.

## 文档工具

*生成项目文档的工具.*

* [Sphinx](http://sphinx-doc.org/) - 功能强大的文档生成器，广泛用于Python社区的各种文档.
* [MkDocs](http://www.mkdocs.org/) - 使用Markdown的文档生成器.
* [pdoc](https://github.com/BurntSushi/pdoc) - 自动为Python库生成文档.
* [Pycco](http://fitzgen.github.io/pycco/) - "文艺编程"风格的文档生成器.

## 配置

*存储和解析配置的库.*

* [config](http://www.red-dove.com/config-doc/)
* [ConfigObj](http://www.voidspace.org.uk/python/configobj.html) - INI配置文件处理.
* [ConfigParser](https://docs.python.org/2/library/configparser.html) - (Python内置标准库) 解析INI文件.
* [profig](http://profig.readthedocs.org/) - 可解析多种配置文件格式.
* [python-decouple](https://github.com/henriquebastos/python-decouple) - Strict separation of settings from code.

## 图片

*Libraries for manipulating images.*

* [pillow](http://pillow.readthedocs.org/) - Pillow is the friendly [PIL](http://www.pythonware.com/products/pil/) fork.
* [hmap](https://github.com/rossgoodwin/hmap) - Image histogram remapping.
* [imgSeek](http://www.imgseek.net/) - A project for searching a collection of images using visual similarity.
* [nude.py](https://github.com/hhatto/nude.py) - Nudity detection.
* [pyBarcode](https://pythonhosted.org/pyBarcode/) - Create barcodes in Python without needing PIL.
* [pygram](https://github.com/ajkumar25/pygram) - Instagram-like image filters.
* [python-qrcode](https://github.com/lincolnloop/python-qrcode) - A pure Python QR Code generator.
* [Quads](https://github.com/fogleman/Quads) - Computer art based on quadtrees.
* [scikit-image](http://scikit-image.org/) - A Python library for (scientific) image processing.
* [thumbor](https://github.com/thumbor/thumbor) - A smart imaging service. It enables on-demand crop, re-sizing and flipping of images.
* [wand](https://github.com/dahlia/wand) - Python bindings for [MagickWand](http://www.imagemagick.org/script/magick-wand.php), C API for ImageMagick.

## 文字识别（OCR）

*文字识别库, OCR(Optical Character Recognition).*

* [pyocr](https://github.com/jflesch/pyocr) - A wrapper for Tesseract and Cuneiform.
* [pytesseract](https://github.com/madmaze/pytesseract) - Another wrapper for Google Tesseract OCR.
* [python-tesseract](https://code.google.com/p/python-tesseract) - A wrapper class for [Google Tesseract OCR](https://code.google.com/p/tesseract-ocr/).

## 音频

*Libraries for manipulating audio.*

* [audiolazy](https://github.com/danilobellini/audiolazy) - Expressive Digital Signal Processing (DSP) package for Python.
* [audioread](https://github.com/sampsyo/audioread) - Cross-library (GStreamer + Core Audio + MAD + FFmpeg) audio decoding.
* [beets](http://beets.radbox.org/) - A music library manager and [MusicBrainz](https://musicbrainz.org/) tagger.
* [dejavu](https://github.com/worldveil/dejavu) - Audio fingerprinting and recognition.
* [django-elastic-transcoder](https://github.com/StreetVoice/django-elastic-transcoder) - Django + [Amazon Elastic Transcoder](http://aws.amazon.com/elastictranscoder/).
* [eyeD3](http://eyed3.nicfit.net/) - A tool for working with audio files, specifically MP3 files containing ID3 metadata.
* [id3reader](http://nedbatchelder.com/code/modules/id3reader.py) - A Python module for reading MP3 meta data.
* [m3u8](https://github.com/globocom/m3u8) - A module for parsing m3u8 file.
* [mutagen](https://bitbucket.org/lazka/mutagen) - A Python module to handle audio metadata.
* [pydub](https://github.com/jiaaro/pydub) - Manipulate audio with a simple and easy high level interface.
* [pyechonest](https://github.com/echonest/pyechonest) - Python client for the [Echo Nest](http://developer.echonest.com/docs/) API.
* [talkbox](http://scikits.appspot.com/talkbox) - A Python library for speech/signal processing.
* [TimeSide](https://github.com/yomguy/TimeSide) - Open web audio processing framework.
* [tinytag](https://github.com/devsnd/tinytag) - A library for reading music meta data of MP3, OGG, FLAC and Wave files.
* [mingus](http://bspaans.github.io/python-mingus/) - An advanced music theory and notation package with MIDI file and playback support.

## 视频

*Libraries for manipulating video and GIFs.*

* [moviepy](http://zulko.github.io/moviepy/) - A module for script-based movie editing with many formats, including animated GIFs.
* [scikit-video](https://github.com/aizvorski/scikit-video) - Video processing routines for SciPy.

## 地理位置

*Libraries for geocoding addresses and working with latitudes and longitudes.*

* [GeoDjango](https://docs.djangoproject.com/en/dev/ref/contrib/gis/) - A world-class geographic web framework.
* [GeoIP](https://github.com/maxmind/geoip-api-python) - Python API for MaxMind GeoIP Legacy Database.
* [geojson](https://github.com/frewsxcv/python-geojson) - Python bindings and utilities for GeoJSON.
* [geopy](https://github.com/geopy/geopy) - Python Geocoding Toolbox.
* [pygeoip](https://github.com/appliedsec/pygeoip) - Pure Python GeoIP API.
* [django-countries](https://github.com/SmileyChris/django-countries) - A Django app that provides country choices for use with forms, flag icons static files, and a country field for models.

## HTTP

*Libraries for working with HTTP.*

* [requests](http://docs.python-requests.org/) - HTTP Requests for Humans™.
* [grequests](https://github.com/kennethreitz/grequests) - requests + gevent for asynchronous HTTP requests.
* [httplib2](https://github.com/jcgregorio/httplib2) - Comprehensive HTTP client library.
* [treq](https://github.com/dreid/treq) - Python requests like API built on top of Twisted's HTTP client.
* [urllib3](https://github.com/shazow/urllib3) - A HTTP library with thread-safe connection pooling, file post support, sanity friendly.

## 数据库

*用Python写的数据库.*

* [pickleDB](https://pythonhosted.org/pickleDB/) - A simple and lightweight key-value store for Python.
* [PipelineDB](http://www.pipelinedb.com/) - The Streaming SQL Database.
* [TinyDB](https://github.com/msiemens/tinydb) - A tiny, document-oriented database.
* [ZODB](http://www.zodb.org/) - A native object database for Python. A key-value and object graph database.

## 数据库驱动（连接件）

*连接和操作数据库.*

* MySQL
    * [mysql-python](http://sourceforge.net/projects/mysql-python/) - Python默认的MySQL连接件.
    * [mysqlclient](https://github.com/PyMySQL/mysqlclient-python) - 支持Python 3，是mysql-python的一个分支.
    * [PyMySQL](https://github.com/PyMySQL/PyMySQL) -  纯Python MySQL连接件，兼容mysql-python.
    * [oursql](https://pythonhosted.org/oursql/) - 一个更好用的MySQL连接件.
* PostgreSQL
    * [psycopg2](http://initd.org/psycopg/) - 最常用的PostgreSQL连接件.
    * [queries](https://github.com/gmr/queries) - A wrapper of the psycopg2 library for interacting with PostgreSQL.
    * [txpostgres](http://txpostgres.readthedocs.org/) - Twisted based asynchronous driver for PostgreSQL.
* 其它关系型数据库
    * [apsw](http://rogerbinns.github.io/apsw/) - Another Python SQLite wrapper.
    * [dataset](https://github.com/pudo/dataset) - Store Python dicts in a database - works with SQLite, MySQL, and PostgreSQL.
    * [pymssql](http://www.pymssql.org/) - A simple database interface to Microsoft SQL Server.
* NoSQL数据库
    * [cassandra-python-driver](https://github.com/datastax/python-driver) - Python driver for Cassandra.
    * [HappyBase](http://happybase.readthedocs.org/) - A developer-friendly library for Apache HBase.
    * [Plyvel](https://plyvel.readthedocs.org/) - A fast and feature-rich Python interface to LevelDB.
    * [py2neo](http://book.py2neo.org/) - Python wrapper client for Neo4j's restful interface.
    * [pycassa](https://github.com/pycassa/pycassa) - Python Thrift driver for Cassandra.
    * [PyMongo](http://docs.mongodb.org/ecosystem/drivers/python/) - The official Python client for MongoDB.
    * [redis-py](https://github.com/andymccurdy/redis-py) - The Redis Python Client.
    * [telephus](https://github.com/driftx/Telephus) - Twisted based client for Cassandra.
    * [txRedis](https://github.com/deldotdr/txRedis) - Twisted based client for Redis.

## 数据库对象关系模型映射（ORM）

*Libraries that implement Object-Relational Mapping or data mapping techniques.*

* 关系型数据库
    * [Django Models](https://docs.djangoproject.com/en/dev/topics/db/models/) - A part of Django.
    * [SQLAlchemy](http://www.sqlalchemy.org/) - The Python SQL Toolkit and Object Relational Mapper.
        * [awesome-sqlalchemy](https://github.com/dahlia/awesome-sqlalchemy)
    * [Peewee](https://github.com/coleifer/peewee) - A small, expressive ORM.
    * [PonyORM](http://ponyorm.com) - ORM that provides a generator-oriented interface to SQL.
    * [python-sql](https://pypi.python.org/pypi/python-sql) - Write SQL queries pythonically.
* NoSQL数据库
    * [django-mongodb-engine](https://github.com/django-nonrel/mongodb-engine) - Django MongoDB Backend.
    * [PynamoDB](https://github.com/jlafon/PynamoDB) - A Pythonic interface for [Amazon DynamoDB](https://aws.amazon.com/dynamodb/).
    * [flywheel](https://github.com/mathcamp/flywheel) - Object mapper for Amazon DynamoDB.
    * [MongoEngine](http://mongoengine.org/) - A Python Object-Document-Mapper for working with MongoDB.
    * [hot-redis](https://github.com/stephenmcd/hot-redis) - Rich Python data types for Redis.
    * [redisco](https://github.com/kiddouk/redisco) - A Python Library for Simple Models and Containers Persisted in Redis.
* 其它
    * [butterdb](https://github.com/Widdershin/butterdb) - A Python ORM for Google Drive Spreadsheets.

## Web框架

*Full stack web frameworks.*

* [Django](https://www.djangoproject.com/) - The most popular web framework in Python.
    * [awesome-django](https://github.com/rosarior/awesome-django)
* [Flask](http://flask.pocoo.org/) - A microframework for Python.
    * [awesome-flask](https://github.com/humiaozuzu/awesome-flask)
* [Pyramid](http://www.pylonsproject.org/) - A small, fast, down-to-earth, open source Python web framework.
    * [awesome-pyramid](https://github.com/ITCase/awesome-pyramid)
* [Bottle](http://bottlepy.org/) - A fast, simple and lightweight WSGI micro web-framework.
* [CherryPy](http://www.cherrypy.org/) - A minimalist Python web framework, HTTP/1.1-compliant and WSGI thread-pooled.
* [TurboGears](http://www.turbogears.org/) - A microframework that can scale up to a full stack solution.
* [web.py](http://webpy.org/) - A web framework for Python that is as simple as it is powerful.
* [web2py](http://www.web2py.com) - A full stack web framework and platform focused in the ease of use.


## 内容管理系统（CMS）

*Content Management Systems.*

* [django-cms](https://www.django-cms.org/en/) - An Open source enterprise CMS based on the Django.
* [djedi-cms](http://djedi-cms.org/) - A lightweight but yet powerful Django CMS with plugins, inline editing and performance in mind.
* [FeinCMS](http://www.feincms.org/) - One of the most advanced Content Management Systems built on Django.
* [Kotte](http://kotti.pylonsproject.org/) - A high-level, Pythonic web application framework built on Pyramid.
* [Mezzanine](http://mezzanine.jupo.org/) - A powerful, consistent, and flexible content management platform.
* [Opps](http://oppsproject.org/) - A Django-based CMS for magazines, newspapers websites and portals with high-traffic.
* [Plone](http://plone.org/) - A CMS built on top of the open source application server Zope.
* [Quokka](http://quokkaproject.org/) - Flexible, extensible, small CMS powered by Flask and MongoDB.
* [Wagtail](http://wagtail.io/) - A Django content management system.
* [Widgy](http://wid.gy/) - Last CMS framework, based on Django.

## 电子商务

*Frameworks and libraries for e-commerce and payments.*

* [django-oscar](http://oscarcommerce.com/) - An open-source e-commerce framework for Django.
* [django-shop](https://www.django-cms.org/) - A Django based shop system.
* [Cartridge](https://github.com/stephenmcd/cartridge) - A shopping cart app built using the Mezzanine.
* [shoop](https://www.shoop.io/) - An open source E-Commerce platform based on Django.
* [alipay](https://github.com/lxneng/alipay) - Unofficial Alipay API for Python.
* [merchant](https://github.com/agiliq/merchant) - A Django app to accept payments from various payment processors.
* [money](https://github.com/carlospalol/money) - Money class with optional CLDR-backed locale-aware formatting and an extensible currency exchange solution.
* [python-currencies](https://github.com/Alir3z4/python-currencies) - Display money format and its filthy currencies.

## RESTful API 框架

*Libraries for developing RESTful APIs.*

* Django
    * [django-rest-framework](http://www.django-rest-framework.org/) - A powerful and flexible toolkit to build web APIs.
    * [django-tastypie](http://tastypieapi.org/) - Creating delicious APIs for Django apps.
    * [django-formapi](https://github.com/5monkeys/django-formapi) - Create JSON APIs with Django's form validation.
* Flask
    * [flask-api](http://www.flaskapi.org/) - Browsable Web APIs for Flask.
    * [flask-restful](http://flask-restful.readthedocs.org/) - Quickly building REST APIs for Flask.
    * [flask-restless](https://flask-restless.readthedocs.org/en/latest/) - Generating RESTful APIs for database models defined with SQLAlchemy.
    * [flask-api-utils](https://github.com/marselester/flask-api-utils) - Taking care of API representation and authentication for Flask.
    * [eve](https://github.com/nicolaiarocci/eve) - REST API framework powered by Flask, MongoDB and good intentions.
* Pyramid
    * [cornice](https://cornice.readthedocs.org/) - A REST framework for Pyramid.
* 其它
    * [falcon](http://falconframework.org/) - A high-performance framework for building cloud APIs and web app backends.
    * [sandman](https://github.com/jeffknupp/sandman) - Automated REST APIs for existing database-driven systems.
    * [restless](http://restless.readthedocs.org/en/latest/) - Framework agnostic REST framework based on lessons learned from Tastypie.
    * [ripozo](https://github.com/vertical-knowledge/ripozo) - Quickly creating REST/HATEOAS/Hypermedia APIs.

## 授权（Authentication）

*Libraries for implementing authentications schemes.*

* OAuth
    * [Authomatic](http://peterhudec.github.io/authomatic/) - Simple but powerful framework agnostic authentication/authorization client.
    * [django-allauth](https://github.com/pennersr/django-allauth) - Authentication app for Django that "just works."
    * [django-oauth-toolkit](https://github.com/evonove/django-oauth-toolkit) - OAuth2 goodies for the Djangonauts.
    * [django-oauth2-provider](https://github.com/caffeinehit/django-oauth2-provider) - Providing OAuth2 access to Django app.
    * [Flask-OAuthlib](https://github.com/lepture/flask-oauthlib) - OAuth 1.0/a, 2.0 implementation of client and provider for Flask.
    * [OAuthLib](https://github.com/idan/oauthlib) - A generic and thorough implementation of the OAuth request-signing logic.
    * [python-oauth2](https://github.com/simplegeo/python-oauth2) - A fully tested, abstract interface to creating OAuth clients and servers.
    * [python-social-auth](https://github.com/omab/python-social-auth) - An easy-to-setup social authentication mechanism.
    * [rauth](https://github.com/litl/rauth) - A Python library for OAuth 1.0/a, 2.0, and Ofly.
    * [sanction](https://github.com/demianbrecht/sanction) - A dead simple OAuth2 client implementation.
* 其它
    * [jose](https://github.com/demonware/jose) - JavaScript Object Signing and Encryption draft implementation.
    * [PyJWT](https://github.com/progrium/pyjwt) - Implementation of the JSON Web Token draft 01.
    * [python-jws](https://github.com/brianloveswords/python-jws) - Implementation of JSON Web Signatures draft 02.
    * [python-jwt](https://github.com/davedoesdev/python-jwt) - Module for generating and verifying JSON Web Tokens.

## 模板引擎

*Libraries and tools for templating and lexing.*

* [Jinja2](https://github.com/mitsuhiko/jinja2) - A modern and designer friendly templating language.
* [Chameleon](https://chameleon.readthedocs.org/) - An HTML/XML template engine. Modeled after ZPT, optimized for speed.
* [Genshi](http://genshi.edgewall.org/) - Python templating toolkit for generation of web-aware output.
* [Mako](http://www.makotemplates.org/) - Hyperfast and lightweight templating for the Python platform.
* [Spitfire](https://code.google.com/p/spitfire/) - A very fast Python template compiler.

## 任务队列

*Libraries for working with event and task queues.*

* [celery](http://www.celeryproject.org/) - An asynchronous task queue/job queue based on distributed message passing.
* [huey](https://github.com/coleifer/huey) - Little multi-threaded task queue.
* [mrq](https://github.com/pricingassistant/mrq) - Mr. Queue - A distributed worker task queue in Python using Redis & gevent.
* [rq](http://python-rq.org/) - Simple job queues for Python.
* [simpleq](https://github.com/rdegges/simpleq) - A simple, infinitely scalable, Amazon SQS based queue.

## 搜索工具

*Libraries and software for indexing and performing search queries on data.*

* [django-haystack](https://github.com/toastdriven/django-haystack) - Modular search for Django.
* [elasticsearch-py](http://www.elasticsearch.org/guide/en/elasticsearch/client/python-api/current/) - The official low-level Python client for [Elasticsearch](https://www.elastic.co/products/elasticsearch).
* [elasticsearch-dsl-py](https://github.com/elastic/elasticsearch-dsl-py) - The official high-level Python client for Elasticsearch.
* [solrpy](https://code.google.com/p/solrpy/) - A Python client for [solr](http://lucene.apache.org/solr/).
* [Whoosh](http://whoosh.readthedocs.org/) - A fast, pure Python search engine library.

## Feed工具

*Libraries for building user's activities.*

* [django-activity-stream](https://github.com/justquick/django-activity-stream) - Generating generic activity streams from the actions on your site.
* [Stream-Framework](https://github.com/tschellenbach/Stream-Framework) - Building newsfeed and notification systems using Cassandra and Redis.

## 网站资源管理（压缩、最小化等）

*Tools for managing, compressing and minifying website assets.*

* [django-compressor](https://github.com/django-compressor/django-compressor) - Compresses linked and inline JavaScript or CSS into a single cached file.
* [django-storages](http://code.larlet.fr/django-storages/) - A collection of custom storage back ends for Django.
* [fanstatic](http://www.fanstatic.org/) - Packages, optimizes, and serves static file dependencies as Python packages.
* [File Conveyor](http://fileconveyor.org/) - A daemon to detect and sync files to CDNs, S3 and FTP.
* [Flask-Assets](http://flask-assets.readthedocs.org/) - Helps you integrate webassets into your Flask app.
* [glue](http://gluecss.com) - Glue is a simple command line tool to generate CSS sprites.
* [jinja-assets-compressor](https://github.com/jaysonsantos/jinja-assets-compressor) - A Jinja extension to compile and compress your assets.
* [webassets](http://webassets.readthedocs.org/) - Bundles, optimizes, and manages unique cache-busting URLs for static resources.

## 缓存

*Libraries for caching data.*

* [Beaker](http://beaker.readthedocs.org/) - A library for caching and sessions for use with web applications and stand-alone Python scripts and applications.
* [django-cache-machine](https://github.com/jbalogh/django-cache-machine) - Automatic caching and invalidation for Django models.
* [django-cacheops](https://github.com/Suor/django-cacheops) - A slick ORM cache with automatic granular event-driven invalidation.
* [django-viewlet](https://github.com/5monkeys/django-viewlet) - Render template parts with extended cache control.
* [dogpile.cache](http://dogpilecache.readthedocs.org/) - dogpile.cache is next generation replacement for Beaker made by same authors.
* [HermesCache](https://pypi.python.org/pypi/HermesCache) - Python caching library with tag-based invalidation and dogpile effect prevention.
* [johnny-cache](https://github.com/jmoiron/johnny-cache) - A caching framework for django applications.
* [pylibmc](https://github.com/lericson/pylibmc) - A Python wrapper around the [libmemcached](http://libmemcached.org/libMemcached.html) interface.

## 电子邮件（email）

*Libraries for sending and parsing email.*

* [django-celery-ses](https://github.com/StreetVoice/django-celery-ses) - Django email back end with AWS SES and Celery.
* [envelopes](http://tomekwojcik.github.io/envelopes/) - Mailing for human beings.
* [flanker](https://github.com/mailgun/flanker) - A email address and Mime parsing library.
* [imbox](https://github.com/martinrusev/imbox) - Python IMAP for Humans.
* [inbox.py](https://github.com/kennethreitz/inbox.py) - Python SMTP Server for Humans.
* [inbox](https://github.com/inboxapp/inbox) - The open source email toolkit.
* [lamson](https://github.com/zedshaw/lamson) - Pythonic SMTP Application Server.
* [mailjet](https://github.com/WoLpH/mailjet) - Mailjet API implementation for batch mailing, statistics and more.
* [marrow.mailer](https://github.com/marrow/marrow.mailer) - High-performance extensible mail delivery framework.
* [modoboa](https://github.com/tonioo/modoboa) - A mail hosting and management platform including a modern and simplified Web UI.
* [pyzmail](http://www.magiksys.net/pyzmail/) - Compose, send and parse emails.
* [Talon](https://github.com/mailgun/talon) - Mailgun library to extract message quotations and signatures.

## 国际化（多语言）

*Libraries for working with i18n.*

* [Babel](http://babel.pocoo.org/) - An internationalization library for Python.
* [Korean](https://korean.readthedocs.org/) - A library for [Korean](http://en.wikipedia.org/wiki/Korean_language) morphology.

## URL处理

*Libraries for parsing URLs.*

* [furl](https://github.com/gruns/furl) - A small Python library that makes manipulating URLs simple.
* [purl](https://github.com/codeinthehole/purl) - A simple, immutable URL class with a clean API for interrogation and manipulation.
* [pyshorteners](https://github.com/ellisonleao/pyshorteners) - A pure Python URL shortening lib.
* [short_url](https://github.com/Alir3z4/python-short_url) - Python implementation for generating Tiny URL and bit.ly-like URLs.
* [webargs](https://github.com/sloria/webargs) - A friendly library for parsing HTTP request arguments, with built-in support for popular web frameworks, including Flask, Django, Bottle, Tornado, and Pyramid.

## HTML处理

*Libraries for working with HTML and XML.*

* [BeautifulSoup](http://www.crummy.com/software/BeautifulSoup/bs4/doc/) - Providing Pythonic idioms for iterating, searching, and modifying HTML or XML.
* [bleach](http://bleach.readthedocs.org/) - A whitelist-based HTML sanitization and text linkification library.
* [cssutils](https://pypi.python.org/pypi/cssutils/) - A CSS library for Python.
* [html5lib](https://github.com/html5lib/html5lib-python) - A standards-compliant library for parsing and serializing HTML documents and fragments.
* [lxml](http://lxml.de/) - A very fast, easy-to-use and versatile library for handling HTML and XML.
* [MarkupSafe](https://github.com/mitsuhiko/markupsafe) - Implements a XML/HTML/XHTML Markup safe string for Python.
* [pyquery](https://github.com/gawel/pyquery) - A jQuery-like library for parsing HTML.
* [untangle](https://github.com/stchris/untangle) - Converts XML documents to Python objects for easy access.
* [xhtml2pdf](https://github.com/chrisglass/xhtml2pdf) - HTML/CSS to PDF converter.
* [xmltodict](https://github.com/martinblech/xmltodict) - Working with XML feel like you are working with JSON.

## Web爬虫

*Libraries for scraping websites.*

* [Scrapy](http://scrapy.org/) - A fast high-level screen scraping and web crawling framework.
* [cola](https://github.com/chineking/cola) - A distributed crawling framework.
* [Demiurge](https://github.com/matiasb/demiurge) - PyQuery-based scraping micro-framework.
* [feedparser](http://pythonhosted.org/feedparser/) - Universal feed parser.
* [Grab](http://grablib.org/) - Site scraping framework.
* [MechanicalSoup](https://github.com/hickford/MechanicalSoup) - A Python library for automating interaction with websites.
* [portia](https://github.com/scrapinghub/portia) - Visual scraping for Scrapy.
* [pyspider](https://github.com/binux/pyspider) - A powerful spider system.
* [RoboBrowser](https://github.com/jmcarp/robobrowser) - A simple, Pythonic library for browsing the web without a standalone web browser.

## Web内容解析

*Libraries for extracting web contents.*

* [Haul](https://github.com/vinta/Haul) - An Extensible Image Crawler.
* [html2text](https://github.com/Alir3z4/html2text) - Convert HTML to Markdown-formatted text.
* [lassie](https://github.com/michaelhelmick/lassie) - Web Content Retrieval for Humans.
* [micawber](https://github.com/coleifer/micawber) - A small library for extracting rich content from URLs.
* [newspaper](https://github.com/codelucas/newspaper) - News extraction, article extraction and content curation in Python.
* [opengraph](https://github.com/erikriver/opengraph) - A Python module to parse the Open Graph Protocol
* [python-goose](https://github.com/grangier/python-goose) - HTML Content/Article Extractor.
* [python-readability](https://github.com/buriy/python-readability) - Fast Python port of arc90's readability tool.
* [sanitize](https://github.com/Alir3z4/sanitize) - Bringing sanity to world of messed-up data.
* [sumy](https://github.com/miso-belica/sumy) - A module for automatic summarization of text documents and HTML pages.
* [textract](https://github.com/deanmalmgren/textract) - Extract text from any document, Word, PowerPoint, PDFs, etc.

## 数据验证

*Libraries for validating data. Used for forms in many cases.*

* [Cerberus](http://python-cerberus.org) - A mappings-validator with a variety of rules, normalization-features and simple customization that uses a pythonic schema-definition.
* [colander](http://docs.pylonsproject.org/projects/colander/) - A system for validating and deserializing data obtained via XML, JSON, an HTML form post or any other equally simple data serialization.
* [kmatch](https://github.com/ambitioninc/kmatch) - A language for matching/validating/filtering Python dictionaries.
* [schema](https://github.com/halst/schema) - A library for validating Python data structures.
* [Schematics](https://github.com/schematics/schematics) - Data Structure Validation.
* [valideer](https://github.com/podio/valideer) - Lightweight extensible data validation and adaptation library.
* [voluptuous](https://github.com/alecthomas/voluptuous) - A Python data validation library. It is primarily intended for validating data coming into Python as JSON, YAML, etc.

## 管理界面

*Libraries for administrative interfaces.*

* [Ajenti](https://github.com/Eugeny/ajenti) - The admin panel your servers deserve.
* [django-suit](http://djangosuit.com/) - Alternative Django Admin-Interface (free only for Non-commercial use).
* [django-xadmin](https://github.com/sshwsfc/django-xadmin) - Drop-in replacement of Django admin comes with lots of goodies.
* [flask-admin](https://github.com/mrjoes/flask-admin) - Simple and extensible administrative interface framework for Flask.
* [flower](https://github.com/mher/flower) - Real-time monitor and web admin for Celery.
* [Grappelli](http://grappelliproject.com) – A jazzy skin for the Django Admin-Interface.
* [Wooey](https://github.com/wooey/wooey) - A Django app which creates automatic web UIs for Python scripts.

## 静态网站生成

*Static site generator is a software that takes some text + templates as input and produces HTML files on the output.*

* [Pelican](http://blog.getpelican.com/) - Uses Markdown or ReST for content and Jinja 2 for themes. Supports DVCS, Disqus. AGPL.
* [Cactus](http://github.com/koenbok/Cactus/) – Static site generator for designers.
* [Hyde](https://hyde.github.com/) - Jinja2-based static web site generator.
* [Nikola](http://www.getnikola.com/) - A static website and blog generator.
* [Tinkerer](http://tinkerer.me/) - Tinkerer is a blogging engine/.static website generator powered by Sphinx.

## 进程管理

*Libraries for starting and communicating with OS processes.*

* [envoy](https://github.com/kennethreitz/envoy) - Python [subprocess](https://docs.python.org/2/library/subprocess.html) for Humans™.
* [sarge](http://sarge.readthedocs.org/) - Yet another wrapper for subprocess.
* [sh](https://github.com/amoffat/sh) - A full-fledged subprocess replacement for Python.

## 并发和并行

*Libraries for concurrent and parallel execution.*

* [multiprocessing](https://docs.python.org/2/library/multiprocessing.html) - (Python standard library) Process-based "threading" interface.
* [threading](https://docs.python.org/2/library/threading.html) - (Python standard library) Higher-level threading interface.
* [eventlet](http://eventlet.net/) - Asynchronous framework with WSGI support.
* [gevent](http://www.gevent.org/) - A coroutine-based Python networking library that uses [greenlet](https://github.com/python-greenlet/greenlet).
* [Tomorrow](https://github.com/madisonmay/Tomorrow) - Magic decorator syntax for asynchronous code.

## 网络

*Libraries for networking programming.*

* [asyncio](https://docs.python.org/3/library/asyncio.html) - (Python standard library) Asynchronous I/O, event loop, coroutines and tasks.
* [Tornado](http://www.tornadoweb.org/) - A Web framework and asynchronous networking library.
* [Twisted](https://twistedmatrix.com/trac/) - An event-driven networking engine.
* [pulsar](https://github.com/quantmind/pulsar) - Event-driven concurrent framework for Python.
* [diesel](https://github.com/jamwt/diesel) - Greenlet-based event I/O Framework for Python.
* [pyzmq](http://zeromq.github.io/pyzmq/) - A Python wrapper for the ZeroMQ message library.
* [txZMQ](https://github.com/smira/txZMQ) - Twisted based wrapper for the ZeroMQ message library.

## WebSocket处理

*Libraries for working with WebSocket.*

* [AutobahnPython](https://github.com/tavendo/AutobahnPython) - WebSocket & WAMP for Python on Twisted and [asyncio](https://docs.python.org/3/library/asyncio.html).
* [Crossbar](https://github.com/crossbario/crossbar/) - Open-source Unified Application Router (Websocket & WAMP for Python on Autobahn).
* [django-socketio](https://github.com/stephenmcd/django-socketio) - WebSockets for Django.
* [WebSocket-for-Python](https://github.com/Lawouach/WebSocket-for-Python) - WebSocket client and server library for Python 2 and 3 as well as PyPy.

## WSGI服务器

*兼容WSGI的web服务器.*

* [gunicorn](http://pypi.python.org/pypi/gunicorn) - Pre-forked, partly written in C.
* [uwsgi](https://uwsgi-docs.readthedocs.org/en/latest/) - A project aims at developing a full stack for building hosting services, written in C.
* [bjoern](http://pypi.python.org/pypi/bjoern) - Asynchronous, very fast and written in C.
* [fapws3](http://www.fapws.org/) - Asynchronous (network side only), written in C.
* [meinheld](http://pypi.python.org/pypi/meinheld) - Asynchronous, partly written in C.
* [netius](https://github.com/hivesolutions/netius) - Asynchronous, very fast.
* [paste](http://pythonpaste.org/) - Multi-threaded, stable, tried and tested.
* [rocket](http://pypi.python.org/pypi/rocket) - Multi-threaded.
* [waitress](https://waitress.readthedocs.org/) - Multi-threaded, poweres Pyramid.
* [Werkzeug](http://werkzeug.pocoo.org/) - A WSGI utility library for Python that powers Flask and can easily be embedded into your own projects.

## 远程调用

*RPC-compatible servers.*

* [SimpleJSONRPCServer](https://github.com/joshmarshall/jsonrpclib/) - This library is an implementation of the JSON-RPC specification.
* [SimpleXMLRPCServer](https://docs.python.org/2/library/simplexmlrpcserver.html) - (Python standard library) Simple XML-RPC server implementation, single-threaded.
* [zeroRPC](https://github.com/dotcloud/zerorpc-python) - zerorpc is a flexible RPC implementation based on [ZeroMQ](http://zeromq.org/) and [MessagePack](http://msgpack.org/).

## 加解密

* [cryptography](https://cryptography.io/) - A package designed to expose cryptographic primitives and recipes to Python developers.
* [hashids](https://github.com/davidaurelio/hashids-python) - Implementation of [hashids](http://hashids.org) in Python.
* [Paramiko](http://www.paramiko.org/) - A Python (2.6+, 3.3+) implementation of the SSHv2 protocol, providing both client and server functionality.
* [Passlib](https://pythonhosted.org/passlib/) - Secure password storage/hashing library, very high level.
* [PyCrypto](https://www.dlitz.net/software/pycrypto/) - The Python Cryptography Toolkit.
* [PyNacl](https://github.com/pyca/pynacl) - Python binding to the Networking and Cryptography (NaCl) library.

## 图形界面（GUI）

*Libraries for working with graphical user interface applications.*

* [curses](https://docs.python.org/2/library/curses.html#module-curses) - Built-in wrapper for [ncurses](http://www.gnu.org/software/ncurses/) used to create terminal GUI applications.
* [enaml](https://github.com/nucleic/enaml) - Creating beautiful user-interfaces with Declaratic Syntax like QML.
* [kivy](http://kivy.org/) - A library for creating NUI applications, running on Windows, Linux, Mac OS X, Android and iOS.
* [pyglet](http://www.pyglet.org/) - A cross-platform windowing and multimedia library for Python.
* [PyQt](http://www.riverbankcomputing.co.uk/software/pyqt/intro) - Python bindings for the [Qt](http://qt-project.org/) cross-platform application and UI framework, with support for both Qt v4 and Qt v5 frameworks.
* [PySide](http://qt-project.org/wiki/pyside) - Python bindings for the [Qt](http://qt-project.org/) cross-platform application and UI framework, supporting the Qt v4 framework.
* [Tkinter](https://wiki.python.org/moin/TkInter) - Tkinter is Python's de-facto standard GUI package.
* [Toga](https://github.com/pybee/toga) - A Python native, OS native GUI toolkit.
* [urwid](http://urwid.org/) - A library for creating terminal GUI applications with strong support for widgets, events, rich colors, etc.
* [wxPython](http://wxpython.org/) - A blending of the wxWidgets C++ class library with the Python.
* [PyGObject](https://wiki.gnome.org/Projects/PyGObject) - Python Bindings for GLib/GObject/GIO/GTK+ (GTK+3)
* [Flexx](https://github.com/zoofIO/flexx) - Flexx is a pure Python toolkit for creating GUI's, that uses web technology for its rendering.

## 游戏开发

*Awesome game development libraries.*

* [Cocos2d](http://cocos2d.org/) - cocos2d is a framework for building 2D games, demos, and other graphical/interactive applications. It is based on pyglet.
* [Panda3D](https://www.panda3d.org/) - 3D game engine developed by Disney and maintained by Carnegie Mellon's Entertainment Technology Center. Written in C++, completely wrapped in Python.
* [Pygame](http://www.pygame.org/news.html) - Pygame is a set of Python modules designed for writing games.
* [PyOgre](http://www.ogre3d.org/tikiwiki/PyOgre) - Python bindings for the Ogre 3D render engine, can be used for games, simulations, anything 3D.
* [PyOpenGL](http://pyopengl.sourceforge.net/) - Python ctypes bindings for OpenGL and it's related APIs.
* [PySDL2](http://pysdl2.readthedocs.org/) - A ctypes based wrapper for the SDL2 library.
* [PySFML](http://www.python-sfml.org/) - Python bindings for [SFML](http://www.sfml-dev.org/)
* [RenPy](http://www.renpy.org/) - A Visual Novel engine.

## 日志工具

*Libraries for generating and working with logs.*

* [logging](https://docs.python.org/2/library/logging.html) - (Python standard library) Logging facility for Python.
* [logbook](http://pythonhosted.org/Logbook/) - Logging replacement for Python.
* [Eliot](https://eliot.readthedocs.org/) - Logging for complex & distributed systems.
* [Raven](http://raven.readthedocs.org/) - The Python client for Sentry.
* [Sentry](https://pypi.python.org/pypi/sentry) - A realtime logging and aggregation server.

## 测试

*Libraries for testing codebases and generating test data.*

* 测试框架
    * [unittest](https://docs.python.org/2/library/unittest.html) - (Python standard library) Unit testing framework.
    * [nose](https://nose.readthedocs.org/) - nose extends unittest.
    * [contexts](https://github.com/benjamin-hodgson/Contexts) - A BDD framework for Python 3.3+. Inspired by C#'s `Machine.Specifications`.
    * [hypothesis](https://github.com/DRMacIver/hypothesis) - Hypothesis is an advanced Quickcheck style property based testing library.
    * [mamba](https://nestorsalceda.github.io/mamba) - The definitive testing tool for Python. Born under the banner of BDD.
    * [PyAutoGUI](https://github.com/asweigart/pyautogui) - PyAutoGUI is a cross-platform GUI automation Python module for human beings.
    * [pyshould](https://github.com/drslump/pyshould) - Should style asserts based on [PyHamcrest](https://github.com/hamcrest/PyHamcrest).
    * [pytest](http://pytest.org/) - A mature full-featured Python testing tool.
    * [pyvows](http://heynemann.github.io/pyvows/) - BDD style testing for Python. Inspired by [Vows.js](http://vowsjs.org/).
    * [Robot Framework](https://github.com/robotframework/robotframework) - A generic test automation framework.
* Web测试
    * [Selenium](https://pypi.python.org/pypi/selenium) - Python bindings for [Selenium](http://www.seleniumhq.org/) WebDriver.
    * [locust](https://github.com/locustio/locust) - Scalable user load testing tool written in Python.
    * [sixpack](https://github.com/seatgeek/sixpack) - A language-agnostic A/B Testing framework.
    * [splinter](https://splinter.readthedocs.org/en/latest/) - Open source tool for testing web applications.
* Mock
    * [mock](https://docs.python.org/3/library/unittest.mock.html) - (Python standard library) A mocking and patching library.
    * [doublex](https://pypi.python.org/pypi/doublex) - Powerful test doubles framework for Python.
    * [freezegun](https://github.com/spulec/freezegun) - Travel through time by mocking the datetime module.
    * [httmock](https://github.com/patrys/httmock) - A mocking library for requests for Python 2.6+ and 3.2+.
    * [httpretty](http://falcao.it/HTTPretty/) - HTTP request mock tool for Python.
    * [responses](https://github.com/dropbox/responses) - A utility library for mocking out the requests Python library.
    * [VCR.py](https://github.com/kevin1024/vcrpy) - Record and replay HTTP interactions on your tests.
* 对象工厂
    * [factory_boy](https://github.com/rbarrois/factory_boy) - A test fixtures replacement for Python.
    * [mixer](https://github.com/klen/mixer) - Another fixtures replacement. Supported Django, Flask, SQLAlchemy, Peewee and etc.
    * [model_mommy](https://github.com/vandersonmota/model_mommy) - Creating random fixtures for testing in Django.
* 代码覆盖率
    * [coverage](https://pypi.python.org/pypi/coverage) - Code coverage measurement.
* 伪数据（生成）
    * [faker](http://www.joke2k.net/faker/) - A Python package that generates fake data.
    * [fake2db](https://github.com/emirozer/fake2db) - Fake database generator.
    * [radar](https://pypi.python.org/pypi/radar) - Generate random datetime / time.
* 错误处理
    * [FuckIt.py](https://github.com/ajalt/fuckitpy) - FuckIt.py uses state-of-the-art technology to make sure your Python code runs whether it has any right to or not.


## 代码分析和优化

*Libraries and tools for analysing, parsing and manipulation codebases.*

* 代码分析
    * [code2flow](https://github.com/scottrogowski/code2flow) - Turn your Python and JavaScript code into DOT flowcharts.
    * [pycallgraph](https://github.com/gak/pycallgraph) - A library that visualises the flow (call graph) of your Python application.
    * [pysonar2](https://github.com/yinwang0/pysonar2) - A type inferencer and indexer for Python.
* 代码检查和优化
    * [Flake8](https://pypi.python.org/pypi/flake8) - The modular source code checker: pep8, pyflakes and co.
    * [Pylint](http://www.pylint.org/) - A source code analyzer.
    * [pylama](https://pylama.readthedocs.org/) - Code audit tool for Python and JavaScript.

## 调试工具

*Libraries for debugging code.*

* 调试器
    * [ipdb](https://pypi.python.org/pypi/ipdb) - IPython-enabled [pdb](https://docs.python.org/2/library/pdb.html).
    * [pudb](https://pypi.python.org/pypi/pudb) – A full-screen, console-based Python debugger.
    * [pyringe](https://github.com/google/pyringe) - Debugger capable of attaching to and injecting code into Python processes.
    * [wdb](https://github.com/Kozea/wdb) - An improbable web debugger through WebSockets.
    * [winpdb](http://winpdb.org/) - A Python Debugger with GUI, capable of remote debugging based on `rpdb2`.
    * [django-debug-toolbar](https://github.com/django-debug-toolbar/django-debug-toolbar) - Display various debug information for Django.
    * [django-devserver](https://github.com/dcramer/django-devserver) - A drop-in replacement for Django's runserver.
    * [flask-debugtoolbar](https://github.com/mgood/flask-debugtoolbar) - A port of the django-debug-toolbar to flask.
* 性能分析
    * [line_profiler](https://github.com/rkern/line_profiler) - Line-by-line profiling.
    * [memory_profiler](https://github.com/fabianp/memory_profiler) - Monitor Memory usage of Python code.
    * [profiling](https://github.com/what-studio/profiling) - An interactive Python profiler.
* 其它
    * [pyelftools](https://github.com/eliben/pyelftools) - Parsing and analyzing ELF files and DWARF debugging information.
    * [python-statsd](https://github.com/WoLpH/python-statsd) - Python Client for the [statsd](https://github.com/etsy/statsd/) server.

## 科学计算和数据分析

*Libraries for scientific computing and data analyzing.*

* [astropy](http://www.astropy.org/) - A community Python library for Astronomy.
* [bcbio-nextgen](https://github.com/chapmanb/bcbio-nextgen) - A toolkit providing best-practice pipelines for fully automated high throughput sequencing analysis.
* [bccb](https://github.com/chapmanb/bcbb) - Collection of useful code related to biological analysis.
* [Biopython](http://biopython.org/wiki/Main_Page) - Biopython is a set of freely available tools for biological computation.
* [blaze](http://blaze.pydata.org/en/latest/) - NumPy and Pandas interface to Big Data.
* [cclib](http://cclib.github.io/) - A library for parsing and interpreting the results of computational chemistry packages.
* [NetworkX](https://networkx.github.io/) - A high-productivity software for complex networks.
* [Neupy](http://neupy.com/pages/home.html) - Running and testing different Artificial Neural Networks algorithms.
* [Numba](http://numba.pydata.org/) - Python JIT (just in time) complier to LLVM aimed at scientific Python by the developers of Cython and NumPy.
* [NumPy](http://www.numpy.org/) - A fundamental package for scientific computing with Python.
* [Open Babel](http://openbabel.org/wiki/Main_Page) - A chemical toolbox designed to speak the many languages of chemical data.
* [Open Mining](https://github.com/avelino/mining) - Business Intelligence (BI) in Python (Pandas web interface)
* [orange](http://orange.biolab.si/) - Data mining, data visualization, analysis and machine learning through visual programming or Python scripting.
* [Pandas](http://pandas.pydata.org/) - A library providing high-performance, easy-to-use data structures and data analysis tools.
* [PyDy](https://pydy.org/) - Short for Python Dynamics, used to assist with workflow in the modeling of dynamic motion based around NumPy, SciPy, IPython, and matplotlib.
* [PyMC](https://github.com/pymc-devs/pymc3) - Markov Chain Monte Carlo sampling toolkit.
* [RDKit](http://www.rdkit.org/) - Cheminformatics and Machine Learning Software.
* [SciPy](http://www.scipy.org/) - A Python-based ecosystem of open-source software for mathematics, science, and engineering.
* [statsmodels](https://github.com/statsmodels/statsmodels) - Statistical modeling and econometrics in Python.
* [SymPy](https://github.com/sympy/sympy) - A Python library for symbolic mathematics.
* [zipline](https://github.com/quantopian/zipline) - A Pythonic algorithmic trading library.

## 数据可视化

*Libraries for visualizing data. See: [awesome-javascript](https://github.com/sorrycc/awesome-javascript#data-visualization).*

* [matplotlib](http://matplotlib.org/) - A Python 2D plotting library.
* [bokeh](https://github.com/ContinuumIO/bokeh) - Interactive Web Plotting for Python.
* [ggplot](https://github.com/yhat/ggplot) - Same API as ggplot2 for R.
* [plotly](https://plot.ly/python) - Collaborative web plotting for Python and matplotlib.
* [pygal](http://pygal.org/) - A Python SVG Charts Creator.
* [pygraphviz](https://pypi.python.org/pypi/pygraphviz) - Python interface to [Graphviz](http://www.graphviz.org/).
* [PyQtGraph](http://www.pyqtgraph.org/) - Interactive and realtime 2D/3D/Image plotting and science/engineering widgets.
* [SnakeViz](https://jiffyclub.github.io/snakeviz) - A browser based graphical viewer for the output of Python's cProfile module.
* [vincent](https://github.com/wrobstory/vincent) - A Python to Vega translator.
* [VisPy](http://vispy.org/) - High-performance scientific visualization based on OpenGL.

## 视觉计算

*Libraries for computer vision.*

* [OpenCV](http://opencv.org/) - Open Source Computer Vision Library.
* [SimpleCV](http://simplecv.org/) - An open source framework for building computer vision applications.

## 机器学习

*Libraries for Machine Learning. See: [awesome-machine-learning](https://github.com/josephmisiti/awesome-machine-learning#python).*

* [Crab](https://github.com/muricoca/crab) - A ﬂexible, fast recommender engine.
* [gensim](https://github.com/piskvorky/gensim) - Topic Modelling for Humans.
* [hebel](https://github.com/hannes-brt/hebel) - GPU-Accelerated Deep Learning Library in Python.
* [NuPIC](https://github.com/numenta/nupic) - Numenta Platform for Intelligent Computing.
* [pattern](https://github.com/clips/pattern) - Web mining module for Python.
* [PyBrain](https://github.com/pybrain/pybrain) - Another Python Machine Learning Library.
* [Pylearn2](https://github.com/lisa-lab/pylearn2) - A Machine Learning library based on [Theano](https://github.com/Theano/Theano).
* [python-recsys](https://github.com/ocelma/python-recsys) - A Python library for implementing a Recommender System.
* [scikit-learn](http://scikit-learn.org/) - A Python module for machine learning built on top of SciPy.
* [vowpal_porpoise](https://github.com/josephreisinger/vowpal_porpoise) - A lightweight Python wrapper for [Vowpal Wabbit](https://github.com/JohnLangford/vowpal_wabbit/).

## MapReduce

*Framworks and libraries for MapReduce.*

* [dpark](https://github.com/douban/dpark) - Python clone of Spark, a MapReduce alike framework in Python.
* [dumbo](https://github.com/klbostee/dumbo) - Python module that allows one to easily write and run Hadoop programs.
* [luigi](https://github.com/spotify/luigi) - A module that helps you build complex pipelines of batch jobs.
* [mrjob](https://github.com/Yelp/mrjob) - Run MapReduce jobs on Hadoop or Amazon Web Services.
* [PySpark](http://spark.apache.org/docs/latest/programming-guide.html) - The Spark Python API.
* [streamparse](https://github.com/Parsely/streamparse) - Run Python code against real-time streams of data. Integrates with [Apache Storm](https://storm.incubator.apache.org/).

## 函数式编程

*Functional Programming with Python.*

* [CyToolz](https://github.com/pytoolz/cytoolz/) - Cython implementation of Toolz: High performance functional utilities.
* [fn.py](https://github.com/kachayev/fn.py) - Functional programming in Python: implementation of missing features to enjoy FP.
* [funcy](https://github.com/Suor/funcy) - A fancy and practical functional tools.
* [Toolz](https://github.com/pytoolz/toolz) - A collection of functional utilities for iterators, functions, and dictionaries.

## 运维开发工具

*Software and libraries for DevOps.*

* [Ansible](https://github.com/ansible/ansible) - A radically simple IT automation platform.
* [SaltStack](https://github.com/saltstack/salt) - Infrastructure automation and management system.
* [OpenStack](http://www.openstack.org/) - Open source software for building private and public clouds.
* [Docker Compose](https://docs.docker.com/compose/) - Fast, isolated development environments using [Docker](https://www.docker.com/).
* [Fabric](http://www.fabfile.org/) - A simple, Pythonic tool for remote execution and deployment.
* [cuisine](https://github.com/sebastien/cuisine) - Chef-like functionality for Fabric.
* [Fabtools](https://github.com/ronnix/fabtools) - Tools for writing awesome Fabric files.
* [gitapi](http://bitbucket.org/haard/gitapi) - Pure-Python API for Git.
* [hgapi](http://bitbucket.org/haard/hgapi) - Pure-Python API for Mercurial.
* [honcho](https://github.com/nickstenning/honcho) - A Python clone of [Foreman](https://github.com/ddollar/foreman), for managing Procfile-based applications.
* [pexpect](https://github.com/pexpect/pexpect) - Controlling interactive programs in a pseudo-terminal like GNU expect.
* [psutil](https://github.com/giampaolo/psutil) - A cross-platform process and system utilities module.
* [supervisor](https://github.com/Supervisor/supervisor) - Supervisor process control system for UNIX.

## 任务调度

*Libraries for scheduling jobs.*

* [APScheduler](http://apscheduler.readthedocs.org/) - A light but powerful in-process task scheduler that lets you schedule functions.
* [django-schedule](https://github.com/thauber/django-schedule) - A calendaring app for Django.
* [doit](http://pydoit.org/) - A task runner and build tool.
* [gunnery](https://github.com/gunnery/gunnery) - Multipurpose task execution tool for distributed systems with web-based interface.
* [Joblib](http://pythonhosted.org/joblib/index.html) - A set of tools to provide lightweight pipelining in Python.
* [Plan](https://github.com/fengsp/plan) - Writing crontab file in Python like a charm.
* [schedule](https://github.com/dbader/schedule) - Python job scheduling for humans.
* [Spiff](https://github.com/knipknap/SpiffWorkflow) - A powerful workflow engine implemented in pure Python.
* [TaskFlow](http://docs.openstack.org/developer/taskflow/) - A Python library that helps to make task execution easy, consistent and reliable.

## 使用其它语言扩展Python

*Libraries for providing foreign function interface.*

* [cffi](https://pypi.python.org/pypi/cffi) - Foreign Function Interface for Python calling C code.
* [ctypes](https://docs.python.org/2/library/ctypes.html) - (Python standard library) Foreign Function Interface for Python calling C code.
* [PyCUDA](http://mathema.tician.de/software/pycuda/) - A Python wrapper for Nvidia's CUDA API.
* [SWIG](http://www.swig.org/Doc1.3/Python.html) - Simplified Wrapper and Interface Generator.

## 高性能

*Libraries for making Python faster.*

* [Cython](http://cython.org/) - Optimizing Static Compiler for Python. Uses type mixins to compile Python into C or C++ modules resulting in large performance gains.
* [PeachPy](https://github.com/Maratyszcza/PeachPy) - x86-64 assembler embedded in Python. Can be used as inline assembler for Python or as a stand-alone assembler for Windows, Linux, OS X, Native Client and Go.
* [PyPy](http://pypy.org/) - An implementation of Python in Python. The interpreter uses black magic to make Python very fast without having to add in additional type information.
* [Pyston](https://github.com/dropbox/pyston) - A Python implementation built using LLVM and modern JIT techniques with the goal of achieving good performance.
* [Stackless Python](http://www.stackless.com/) - An enhanced version of the Python.

## Windows工具

*Python programming on Microsoft Windows.*

* [Python(x,y)](https://code.google.com/p/pythonxy/) - Scientific-applications-oriented Python Distribution based on Qt and Spyder.
* [pythonlibs](http://www.lfd.uci.edu/~gohlke/pythonlibs/) - Unofficial Windows binaries for Python extension packages.
* [PythonNet](https://github.com/pythonnet/pythonnet) - Python Integration with the .NET Common Language Runtime (CLR).
* [PyWin32](http://sourceforge.net/projects/pywin32/) - Python Extensions for Windows.
* [WinPython](https://winpython.github.io/) - Portable development environment for Windows 7/8.

## 网络虚拟化和SDN

*网络虚拟化和SDN(Software Defined Networking).*

* [Mininet](http://mininet.org/) - A popular network emulator and API written in Python.
* [POX](http://www.noxrepo.org/pox/about-pox/) - An open source development platform for Python-based Software Defined Networking (SDN) control applications, such as OpenFlow SDN controllers.
* [Pyretic](http://frenetic-lang.org/pyretic/) - A member of the Frenetic family of SDN programming languages that provides powerful abstractions over network switches or emulators.
* [SDX Platform](https://github.com/sdn-ixp/internet2award) - SDN based IXP implementation that leverages Mininet, POX and Pyretic.

## 硬件

*Libraries for programming with hardware.*

* [ino](http://inotool.org/) - Command line toolkit for working with [Arduino](http://www.arduino.cc/).
* [Pyro](http://pyrorobotics.com/) - Python Robotics.
* [PyUserInput](https://github.com/SavinaRoja/PyUserInput) - A module for cross-platform control of the mouse and keyboard.
* [scapy](http://www.secdev.org/projects/scapy/) - A brilliant packet manipulation library.
* [wifi](https://wifi.readthedocs.org/) - A Python library and command line tool for working with WiFi on Linux.
* [Pingo](http://pingo.io) - Pingo provides a uniform API to program devices like the Raspberry Pi, pcDuino, Intel Galileo, etc.

## 兼容性

*Python 2 和 3兼容性和转换工具.*

* [Python-Future](http://python-future.org/index.html) - The missing compatibility layer between Python 2 and Python 3.
* [Python-Modernize](https://github.com/mitsuhiko/python-modernize) - Modernizes Python code for eventual Python 3 migration.
* [Six](https://pypi.python.org/pypi/six) - Python 2 and 3 compatibility utilities.

## 开发者插件

*各种编辑器和IDE的插件.*

* Emacs
    * [Elpy](https://github.com/jorgenschaefer/elpy) - Emacs Python Development Environment.
* Sublime Text
    * [SublimeJEDI](https://github.com/srusskih/SublimeJEDI) - A Sublime Text plugin to the awesome auto-complete library Jedi.
    * [Anaconda](https://github.com/DamnWidget/anaconda) - Anaconda turns your Sublime Text 3 in a full featured Python development IDE.
* Vim
    * [YouCompleteMe](https://github.com/Valloric/YouCompleteMe) - Includes [Jedi](https://github.com/davidhalter/jedi)-based completion engine for Python.
    * [Jedi-vim](https://github.com/davidhalter/jedi-vim) - Vim bindings for the Jedi auto-completion library for Python.
    * [Python-mode](https://github.com/klen/python-mode) - An all in one plugin for turning Vim into a Python IDE.
* Visual Studio
    * [PTVS](https://github.com/Microsoft/PTVS) - Python Tools for Visual Studio.

## IDEs

*Popular Python IDEs.*

* [PyCharm](https://www.jetbrains.com/pycharm/) - Commercial Python IDE by JetBrains. Has free community edition available.
* [LiClipse](http://www.liclipse.com/) - Free polyglot IDE based on Eclipse. Uses PyDev for Python support.
* [Spyder](https://github.com/spyder-ide/spyder) - Open Source Python IDE.

# Python资源

Where to discover new Python libraries.

## 网站

* [r/Python](http://www.reddit.com/r/python)
* [CoolGithubProjects](http://coolgithubprojects.com/)
* [Django Packages](https://www.djangopackages.com/)
* [Full Stack Python](http://www.fullstackpython.com/)
* [Python 3 Wall of Superpowers](http://python3wos.appspot.com/)
* [Python Hackers](http://pythonhackers.com/open-source/)
* [Python ZEEF](https://python.zeef.com/alan.richmond)
* [Trending Python repositories on GitHub today](https://github.com/trending?l=python)

## 周报

* [Import Python Newsletter](http://importpython.com/newsletter/)
* [Pycoder's Weekly](http://pycoders.com/)
* [Python Weekly](http://www.pythonweekly.com/)

## Twitter

* [@codetengu](https://twitter.com/codetengu)
* [@getpy](https://twitter.com/getpy)
* [@planetpython](https://twitter.com/planetpython)
* [@pycoders](https://twitter.com/pycoders)
* [@pypi](https://twitter.com/pypi)
* [@pythontrending](https://twitter.com/pythontrending)
* [@PythonWeekly](https://twitter.com/PythonWeekly)
