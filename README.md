# 保研攻略

[![Documentation Status](https://readthedocs.org/projects/postgraduate-recommendation/badge/?version=latest)](https://postgraduate-recommendation.readthedocs.io/zh_CN/latest/?badge=latest)

地址：https://postgraduate-recommendation.readthedocs.io/zh_CN/latest/

由南大软院学长学姐编写的保研攻略，希望大家都能更快更高效更少踩坑地成功保研，拥有光明的未来。

# 贡献

## 构建

本项目使用[pipenv](https://pipenv.kennethreitz.org/en/latest/)管理pip依赖，请安装：

- Python 3
- pipenv（`pip install --user pipenv`）

本项目使用[reStructuredText](http://www.sphinx-doc.org/en/master/usage/restructuredtext/basics.html)或者[markdown](https://www.markdownguide.org/)进行写作，请至少学会其中一种格式。

本项目使用[sphinx](http://www.sphinx-doc.org/en/master/contents.html)进行文档生成，如果需要学习对项目进行修改，请查看sphinx的文档。

1. Clone本项目
2. `pipenv install`安装依赖
3. `pipenv shell`进入虚拟环境
4. `.\make run` (Windows)、`make run`（安装了`make`的*nix）构建文档HTML
5. 使用浏览器打开`build/html/index.html`，即可预览已经产生的文档！

## Tips

- sphinx对markdown的支持比较差，比如不支持表格。如果需要用特殊/高级功能可以考虑用reStructuredText。
- 目前暂时没看到一个能用的支持中文的reST表格生成器，可以考虑使用VSCode的[Table Formatter](https://marketplace.visualstudio.com/items?itemName=shuworks.vscode-table-formatter)插件进行表格的格式化
- 要在VSCode里预览，请在VSCode里选择Python解释器为带有**pipenv**字样的那项。

## 贡献

fork项目后发PR。

## 贡献者

# 许可证

本项目所有文本内容在[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)下授权。