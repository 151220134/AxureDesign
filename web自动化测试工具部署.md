# 自动化测试工具Selenium部署
---
- 环境及语言：python2（其实也支持Java只不过我选了python）

- 下载及配置：conda install selenium/pip install selenium

- Selenium这个web自动化测试工具支持多平台（Windows/Linux/MacOS）、多浏览器（IE/Safari/Firefox/Chrome），对于不同的浏览器只需下载相应的浏览器driver即可。
    - 以Chrome为例，在 http://chromedriver.chromium.org/downloads 下载Chrome对应版本的驱动，将下载好的驱动文件放入/usr/local/bin目录下。
    - 测试是否正确：
        ```python
        from selenium import webdriver
        dr = webdriver.Chrome()
        ```
        如果能呼出Chrome浏览器，则说明安装正确。

- 教程：https://legacy.gitbook.com/book/easonhan007/selenium-webdriver/details