# Juncheng Liu — Personal Homepage

Personal research homepage, hosted at **https://yimengqian.github.io/**.

A responsive, accessible static site built with HTML, CSS, and JavaScript. No build step, package installation, tracking, or API keys are required.

## Content

- About and research interests
- PolyBench publication with paper, code, and BibTeX links
- Research experience and selected projects
- Education and technical skills
- Contact and email link to request a CV

## Edit

Edit `index.html` to update the biography, publications, projects, education, or email. CSS and JavaScript are embedded in the same file, so it can be published or opened directly without extra assets. Standalone copies of the CSS and JavaScript are also included in the local project for reference.

The content is based on the October 2026 Agentic AI / Model Comparison research CV. PolyBench's title, authors, arXiv link, and code repository were checked against the public paper. Conference review status is omitted because it may change.

## Preview locally

From this directory:

```sh
python -m http.server 8000 --bind 127.0.0.1
```

Open http://127.0.0.1:8000 in a browser.

## GitHub Pages

In **Settings → Pages**, choose **Deploy from a branch**, branch **main**, folder **/ (root)**, and save. Updates pushed to `main` are published automatically.

## 中文维护说明

- 修改 `index.html` 可更新个人介绍、论文、项目、教育背景和联系邮箱。
- 页面样式和交互已内嵌在 `index.html` 中，可直接修改其中的 `<style>` 和 `<script>` 部分。
- 完整简历文件未公开上传；访客可通过邮件索取。
- 网站通过 GitHub Pages 从 `main` 分支根目录自动发布。
