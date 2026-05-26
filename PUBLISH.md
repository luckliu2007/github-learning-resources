# 发布到 GitHub

当前文件夹已经可以作为一个 GitHub 仓库发布：

```text
C:\Users\liuq\Documents\Codex\2026-05-26\github-github\github-learning-resources
```

## 方法一：GitHub 网页上传

1. 打开 GitHub，创建一个新仓库，建议命名为 `github-learning-resources`。
2. 不要勾选自动生成 README，因为本地已经有 README。
3. 上传本文件夹中的所有文件和 `categories` 文件夹。
4. 提交后，这个仓库就可以作为你的学习资源导航。

## 方法二：命令行推送

在你自己的终端里进入这个文件夹，然后运行：

```powershell
git init
git add .
git commit -m "Add curated GitHub learning resources"
git branch -M main
git remote add origin https://github.com/YOUR_NAME/github-learning-resources.git
git push -u origin main
```

把 `YOUR_NAME` 换成你的 GitHub 用户名。

## 如果要拆成多个仓库

先看 [REPO_SPLIT_PLAN.md](REPO_SPLIT_PLAN.md)。建议先发布总仓库，后续再按方向拆分：

- `git-github-starter-kit`
- `computer-science-roadmap`
- `coding-projects-lab`
- `algorithm-interview-notes`
- `web-backend-engineering`
- `ai-ml-data-roadmap`
- `chinese-dev-learning`
