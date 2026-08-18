# my-first-repo

这是一个用于学习 Git 和 GitHub 基础工作流的练习仓库。你可以在这里熟悉仓库克隆、文件编辑、提交、分支管理和 Pull Request 等常用操作。

## 项目介绍

本项目用于记录和实践 GitHub 的基本使用方式，适合刚开始接触版本控制的学习者。目前仓库保持轻量，只包含说明文档，不依赖特定编程语言、框架或运行环境。

你可以把它作为一个安全的练习空间，用来：

- 熟悉 Git 仓库的基本结构
- 练习创建分支和提交更改
- 学习将本地提交推送到 GitHub
- 体验通过 Pull Request 合并改动的协作流程

## 当前内容

```text
my-first-repo/
└── README.md    # 项目介绍与使用说明
```

> 当前项目没有可执行程序或第三方依赖，因此无需安装额外软件包。

## 使用说明

### 1. 准备环境

开始前，请确保电脑已安装 [Git](https://git-scm.com/)。

验证 Git 是否可用：

```bash
git --version
```

### 2. 克隆仓库

```bash
git clone https://github.com/oliviathomas97994/my-first-repo.git
```

### 3. 进入项目目录

```bash
cd my-first-repo
```

### 4. 查看项目

使用任意文本编辑器或 Markdown 阅读器打开 `README.md` 即可查看内容。例如：

```bash
# macOS / Linux
cat README.md

# Windows PowerShell
Get-Content README.md
```

### 5. 练习提交更改

建议在独立分支上修改文件：

```bash
git checkout -b feature/my-change
# 编辑 README.md 或添加练习文件
git add README.md
git commit -m "Update README"
git push -u origin feature/my-change
```

推送完成后，可在 GitHub 上创建 Pull Request，将改动合并到 `main` 分支。

## 项目状态

项目目前处于基础练习阶段，主要用于学习和验证 Git/GitHub 工作流。后续可以逐步加入示例代码、练习任务或更详细的学习记录。

## 参与贡献

欢迎通过 Issue 提出建议，或通过 Pull Request 补充内容。提交改动前，请尽量：

1. 从 `main` 分支创建新的功能分支。
2. 保持每次提交内容清晰、范围单一。
3. 在 Pull Request 中说明改动内容和原因。
