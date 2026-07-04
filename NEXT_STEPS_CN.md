# BigJck.github.io 下一步操作

这个目录已经是 Hugo Blox Academic CV 项目：

```text
E:\Github\BigJck.github.io
```

## 本地预览

在 PowerShell 中运行：

```powershell
cd E:\Github\BigJck.github.io
$env:Path = [System.Environment]::GetEnvironmentVariable('Path','Machine') + ';' + [System.Environment]::GetEnvironmentVariable('Path','User')
hugo server
```

然后打开：

```text
http://localhost:1313/
```

## 你最需要替换的内容

- `data/authors/me.yaml`：姓名、单位、邮箱、教育经历、研究兴趣、技能、获奖。
- `content/_index.md`：首页研究介绍和首页模块。
- `content/publications/`：论文页面。
- `content/projects/`：项目页面。
- `static/uploads/resume.pdf`：你的 CV PDF。

## 发布到 GitHub Pages

1. 在 GitHub 创建仓库：`BigJck.github.io`
2. 在本目录执行：

```powershell
git remote remove origin
git remote add origin https://github.com/BigJck/BigJck.github.io.git
git branch -M main
git add .
git commit -m "Create academic homepage"
git push -u origin main
```

3. 打开 GitHub 仓库 `Settings -> Pages`。
4. Source 选择 `GitHub Actions`。
5. 等 Actions 完成后访问：

```text
https://BigJck.github.io/
```

## 备注

当前站点里仍包含 Hugo Blox 的演示论文、博客和项目内容。等你给出真实论文、项目、照片和 CV 后，再逐步替换这些内容。
