# 保研攻略

[![All Contributors](https://img.shields.io/badge/all_contributors-3-green.svg?style=flat-square)](#贡献者-)
![Read the Docs](https://img.shields.io/readthedocs/postgraduate-recommendation?style=flat-square)

地址：https://postgraduate-recommendation.readthedocs.io/zh_CN/latest/

由南大软院学长学姐编写的保研攻略，希望大家都能更快更高效更少踩坑地成功保研，拥有光明的未来。

# 贡献

## 构建

本项目使用[pipenv](https://pipenv.kennethreitz.org/en/latest/)管理pip依赖，请安装：

- Python 3
- pipenv
    - `pip install --user pipenv` (Windows下已测试)
    - 若上命令不可用，请参考[官方教程](https://pipenv.kennethreitz.org/en/latest/install/#installing-pipenv)

本项目使用[reStructuredText](http://www.sphinx-doc.org/en/master/usage/restructuredtext/basics.html)进行写作，请学习它。

本项目使用[sphinx](http://www.sphinx-doc.org/en/master/contents.html)进行文档生成，如果需要学习对项目进行修改，请查看sphinx的文档。

1. Clone本项目
2. `pipenv install`安装依赖
3. `pipenv shell`进入虚拟环境
4. `.\make html` (Windows)、`make html`（安装了`make`的*nix）构建文档HTML
5. 使用浏览器打开`build/html/index.html`，即可预览已经产生的文档！

## Tips

- 目前暂时没看到一个能用的支持中文的reST表格生成器，请使用VSCode的[Table Formatter](https://marketplace.visualstudio.com/items?itemName=shuworks.vscode-table-formatter)插件进行表格的格式化
- 要在VSCode里预览，请在VSCode里选择Python解释器为带有**pipenv**字样的那项，但此操作需要修改`.vscode/settings.json`文件，不要把它提交上来！
- 要从命令行里快速用浏览器打开生成的界面，可以使用如下两个命令：
    - `start build/html/index.html`（Windows）
    - `open build/html/index.html`（*nix）

## 贡献

fork项目后发PR。

在GitHub中本项目使用[all-contributors](https://allcontributors.org/en)维护贡献者列表。在PR即将被合并时，管理员将会使用[all-contributors bot](https://allcontributors.org/docs/en/bot/overview)将您加入贡献者列表中。

在文档中手工维护，若您是第一次贡献本项目，并希望将自己的个人信息写在文档中，请进行以下步骤（若您不想加入，则可以什么都不做）：

- 在`sources/authors.rst`中，根据已有的格式加入您的个人信息
- 在您所修改过的文件的最后`作者`段中，使用`:ref:``authors:您的姓名```加入到自己个人信息的链接
    - 项目提供了内置的VSCode的code snippet用来输入这个信息，输入`authorref`即可自动输入此code snippet

## 贡献者 ✨

本项目不能离开各位慷慨的贡献者们！ ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore -->
<table>
  <tr>
    <td align="center"><a href="https://github.com/exlaw"><img src="https://avatars1.githubusercontent.com/u/32476950?v=4" width="64px;" alt="exlaw"/><br /><sub><b>exlaw</b></sub></a><br /><a href="#ideas-exlaw" title="Ideas, Planning, & Feedback">🤔</a> <a href="#content-exlaw" title="Content">🖋</a> <a href="#review-exlaw" title="Reviewed Pull Requests">👀</a></td>
    <td align="center"><a href="https://viccrubs.me"><img src="https://avatars0.githubusercontent.com/u/8363856?v=4" width="64px;" alt="Chen Junda"/><br /><sub><b>Chen Junda</b></sub></a><br /><a href="#infra-viccrubs" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a> <a href="#content-viccrubs" title="Content">🖋</a> <a href="#review-viccrubs" title="Reviewed Pull Requests">👀</a></td>
    <td align="center"><a href="https://github.com/vivian-jq"><img src="https://avatars1.githubusercontent.com/u/16713101?v=4" width="64px;" alt="vivian"/><br /><sub><b>vivian</b></sub></a><br /><a href="#content-vivian-jq" title="Content">🖋</a></td>
    <td align="center"><a href="https://github.com/tonywang1945yes"><img src="https://avatars0.githubusercontent.com/u/31364471?v=4" width="64px;" alt="Tony Wang"/><br /><sub><b>Tony Wang</b></sub></a><br /><a href="#content-tonywang1945yes" title="Content">🖋</a></td>
  </tr>
</table>

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!

# 许可证

本项目所有文本内容在[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)下授权。
