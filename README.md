# ZH-rgb-create.github.io

朱瀚钊的个人简历与项目展示网站。

## 页面内容

- 个人简介与教育背景
- GPA、专业排名和英语成绩
- 全国大学生电子设计竞赛项目
- 有源 IRS 辅助通信系统保密速率优化项目
- 学生工作、竞赛获奖与技术能力
- 联系方式与简历下载

## 技术方案

网站使用原生 HTML、CSS 和 JavaScript，无第三方框架及构建依赖，适合直接由 GitHub Pages 托管。

## 本地预览

在仓库根目录启动任意静态文件服务器，例如：

```bash
python -m http.server 8080
```

浏览器访问 `http://localhost:8080`。

## 发布

将文件提交到 `ZH-rgb-create/ZH-rgb-create.github.io` 仓库的 Pages 发布分支。对于用户主页仓库，通常提交到默认分支后即可更新：

```bash
git add .
git commit -m "Redesign personal portfolio"
git push
```

## 内容维护

- 页面主体：`index.html`
- 视觉样式：`styles.css`
- 交互逻辑：`script.js`
- 图片资源：`assets/`
- 简历下载：`downloads/`
