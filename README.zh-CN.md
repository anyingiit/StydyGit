[English](README.md) · **简体中文**

> 英文版是规范版本。本页与 [README.md](README.md) 不一致时，以英文版为准。

<!-- translation-of: README.md sha256:646b3ea033d47117 -->

<!-- Source: Best-README-Template BLANK_README (Unlicense) — https://github.com/othneildrew/Best-README-Template -->
<a id="readme-top"></a>

# StydyGit

一个已归档的个人练习仓库，只包含用于练习 Git 命令的草稿文件，没有任何需要安装、构建或运行的应用程序代码。

[![License](https://img.shields.io/github/license/anyingiit/StydyGit)](LICENSE)

[报告问题](https://github.com/anyingiit/StydyGit/issues/new?template=bug_report.yml) · [提出需求](https://github.com/anyingiit/StydyGit/issues/new?template=feature_request.yml)

<details>
  <summary>目录</summary>
  <ol>
    <li><a href="#about-the-project">关于本项目</a></li>
    <li><a href="#getting-started">开始使用</a></li>
    <li><a href="#usage">用法</a></li>
    <li><a href="#contributing">参与贡献</a></li>
    <li><a href="#license">许可证</a></li>
    <li><a href="#contact">联系方式</a></li>
  </ol>
</details>

## 关于本项目

StydyGit 是一个已被所有者归档的公开仓库。它的目录树里只有练习 Git 命令时留下的草稿文件：`readme.txt`，一份重复写着 "Git is a version control system"（Git 是一个版本控制系统）的纯文本笔记；`helly.py`，一个空文件（0 字节）；`TESTFILE`，一个单行的标记文件；以及 `test`，一个至今仍保留着一次「暂存变更」（stash）练习中未解决的 Git 合并冲突标记（`<<<<<<<` / `=======` / `>>>>>>>`）的文件——这正是这个仓库存在的意义。

仓库里没有任何清单文件、没有入口点、也没有任何语言的源代码文件，因此没有什么可以安装、构建或运行的东西。

计划中的功能与已知问题，见 [open issues](https://github.com/anyingiit/StydyGit/issues)。

## 开始使用

### 环境要求

- [Git](https://git-scm.com/)，用于克隆本仓库，也用于重现草稿文件中那次未完成的合并冲突练习。
- （可选）[pre-commit](https://pre-commit.com/)，如果你想在提交前运行 `.pre-commit-config.yaml` 中声明的检查。

### 安装

```sh
git clone https://github.com/anyingiit/StydyGit.git
cd StydyGit
pre-commit install  # 可选 -- 仅当你打算在此仓库中提交更改时才需要
```

## 用法

本仓库中没有可运行的应用程序。这些草稿文件本身就是重点：打开 `test` 查看一次暂存练习遗留下来的未解决合并冲突标记，或者阅读 `readme.txt`，看看这个仓库的所有者当初学习 Git 时留给自己的笔记。

## 参与贡献

欢迎参与。[CONTRIBUTING.md](CONTRIBUTING.md) 说明如何提交 issue 或 pull request，[CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) 说明对所有参与者的行为要求。

请不要在公开的 issue 或 pull request 中报告安全问题。[SECURITY.md](SECURITY.md) 说明了私下报告的方式。

## 许可证

以 MIT 许可证分发。详见 [LICENSE](LICENSE)。

## 联系方式

项目地址：[https://github.com/anyingiit/StydyGit](https://github.com/anyingiit/StydyGit)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
