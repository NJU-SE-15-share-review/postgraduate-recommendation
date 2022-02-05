# 保研攻略

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

- 插入本地图片可用如下语法：
    - `.. image:: ../assets/test.png`

## 贡献

您可以用如下两种方式对此项目进行贡献：

- fork项目之后发PR
- 联系**Chen Junda** ([GitHub](https://github.com/ddadaal))获取本项目写权限后，往本项目中**非master**分支提交您的内容，再发PR

在GitHub中本项目使用[all-contributors](https://allcontributors.org/en)维护贡献者列表。在PR即将被合并时，管理员将会使用[all-contributors bot](https://allcontributors.org/docs/en/bot/overview)将您加入贡献者列表中。

在文档中手工维护，若您是第一次贡献本项目，并希望将自己的个人信息写在文档中，请进行以下步骤（若您不想加入，则可以什么都不做）：

- 在`sources/authors.rst`中，根据已有的格式加入您的个人信息
- 在您所修改过的文件的最后`作者`段中，使用以下格式加入到自己个人信息的链接。您的姓名要与`authors.rst`中您的姓名相对应。
    - 项目提供了内置的VSCode的code snippet用来输入这个信息，输入`authorref`即可自动输入此code snippet

```
:ref:`authors:已有的用户1` :ref:`authors:已有的用户2` :ref:`authors:您的姓名` 
```

## 贡献者 ✨

本项目不能离开各位慷慨的贡献者们！ ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://github.com/exlaw"><img src="https://avatars1.githubusercontent.com/u/32476950?v=4?s=64" width="64px;" alt=""/><br /><sub><b>exlaw</b></sub></a><br /><a href="#ideas-exlaw" title="Ideas, Planning, & Feedback">🤔</a> <a href="#content-exlaw" title="Content">🖋</a> <a href="https://github.com/NJU-SE-15-share-review/postgraduate-recommendation/pulls?q=is%3Apr+reviewed-by%3Aexlaw" title="Reviewed Pull Requests">👀</a></td>
    <td align="center"><a href="https://ddadaal.me"><img src="https://avatars0.githubusercontent.com/u/8363856?v=4?s=64" width="64px;" alt=""/><br /><sub><b>Chen Junda</b></sub></a><br /><a href="#infra-ddadaal" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a> <a href="#content-ddadaal" title="Content">🖋</a> <a href="https://github.com/NJU-SE-15-share-review/postgraduate-recommendation/pulls?q=is%3Apr+reviewed-by%3Addadaal" title="Reviewed Pull Requests">👀</a></td>
    <td align="center"><a href="https://github.com/vivian-jq"><img src="https://avatars1.githubusercontent.com/u/16713101?v=4?s=64" width="64px;" alt=""/><br /><sub><b>vivian</b></sub></a><br /><a href="#content-vivian-jq" title="Content">🖋</a></td>
    <td align="center"><a href="https://github.com/tonywang1945yes"><img src="https://avatars0.githubusercontent.com/u/31364471?v=4?s=64" width="64px;" alt=""/><br /><sub><b>Tony Wang</b></sub></a><br /><a href="#content-tonywang1945yes" title="Content">🖋</a></td>
    <td align="center"><a href="https://github.com/zhanglingzhe0820"><img src="https://avatars2.githubusercontent.com/u/24886743?v=4?s=64" width="64px;" alt=""/><br /><sub><b>zhanglingzhe0820</b></sub></a><br /><a href="#content-zhanglingzhe0820" title="Content">🖋</a></td>
    <td align="center"><a href="http://hanxinhu.github.io"><img src="https://avatars3.githubusercontent.com/u/24485000?v=4?s=64" width="64px;" alt=""/><br /><sub><b>韩新虎</b></sub></a><br /><a href="#content-hanxinhu" title="Content">🖋</a></td>
    <td align="center"><a href="http://wensun.today"><img src="https://avatars1.githubusercontent.com/u/35923278?v=4?s=64" width="64px;" alt=""/><br /><sub><b>Wen Sun</b></sub></a><br /><a href="#content-HermitSun" title="Content">🖋</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/Moonquakes"><img src="https://avatars0.githubusercontent.com/u/38858895?v=4?s=64" width="64px;" alt=""/><br /><sub><b>Yuhao Xue</b></sub></a><br /><a href="#content-Moonquakes" title="Content">🖋</a></td>
    <td align="center"><a href="https://github.com/GitOfCharlie"><img src="https://avatars1.githubusercontent.com/u/37411016?v=4?s=64" width="64px;" alt=""/><br /><sub><b>Charlie_Young</b></sub></a><br /><a href="#content-GitOfCharlie" title="Content">🖋</a></td>
    <td align="center"><a href="https://github.com/HeimingZ"><img src="https://avatars2.githubusercontent.com/u/43991780?v=4?s=64" width="64px;" alt=""/><br /><sub><b>Alan Choo</b></sub></a><br /><a href="#content-HeimingZ" title="Content">🖋</a></td>
    <td align="center"><a href="https://caesarroot.github.io/"><img src="https://avatars2.githubusercontent.com/u/35787647?v=4?s=64" width="64px;" alt=""/><br /><sub><b>羊男</b></sub></a><br /><a href="#content-CaesarRoot" title="Content">🖋</a> <a href="https://github.com/NJU-SE-15-share-review/postgraduate-recommendation/pulls?q=is%3Apr+reviewed-by%3ACaesarRoot" title="Reviewed Pull Requests">👀</a></td>
    <td align="center"><a href="https://github.com/Green-Wood"><img src="https://avatars3.githubusercontent.com/u/31267545?v=4?s=64" width="64px;" alt=""/><br /><sub><b>Wenqi Zhao</b></sub></a><br /><a href="#content-Green-Wood" title="Content">🖋</a></td>
    <td align="center"><a href="https://github.com/stormbroken"><img src="https://avatars.githubusercontent.com/u/46039728?v=4?s=64" width="64px;" alt=""/><br /><sub><b>ZhangHongYin</b></sub></a><br /><a href="#content-stormbroken" title="Content">🖋</a></td>
    <td align="center"><a href="https://www.cnblogs.com/Sparrow612"><img src="https://avatars.githubusercontent.com/u/44128608?v=4?s=64" width="64px;" alt=""/><br /><sub><b>Rongxin Cheng</b></sub></a><br /><a href="#content-Sparrow612" title="Content">🖋</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/xidao4"><img src="https://avatars.githubusercontent.com/u/47544757?v=4?s=64" width="64px;" alt=""/><br /><sub><b>xidao4</b></sub></a><br /><a href="#content-xidao4" title="Content">🖋</a></td>
  </tr>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!

# 许可证

本项目所有文本内容在[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)下授权。
