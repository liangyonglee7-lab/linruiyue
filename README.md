# 林瑞跃个人学术网站

适用于 GitHub Pages 的静态网站，无需安装依赖或构建。

## 内容

- 中英双语个人简介与研究方向
- 简历中的 37 篇论文，按年份或关键词检索，提供 Google Scholar 检索入口
- 主持和参与的 14 项科研项目
- 教学、研究生招生、教育及工作经历、奖励和学术服务
- 移动端导航、ORCID、邮箱链接、打印样式

内容依据用户提供的《林瑞跃简历》。引用按简历保留，未独立核验论文卷期页码；英文项目及荣誉名称为描述性翻译。部分教育条目未提供专业名称，因此没有补写。未加入未确认的新闻或在审稿件。

## 预览

双击 `preview.html` 即可离线预览完整网站。正式发布使用 `index.html` 和 `assets/`。邮件、ORCID、Google Scholar 链接需要网络。

## GitHub Pages 发布

1. 在自己的 GitHub 账号下创建仓库，例如 `academic-homepage`（项目网站），或 `<用户名>.github.io`（账号主页）。不要覆盖已有仓库。
2. 上传 `index.html`、`assets/` 和 `.github/workflows/pages.yml`，主分支名为 `main`。
3. 在仓库 Settings → Pages → Build and deployment 将 Source 设置为 GitHub Actions。
4. 在 Actions 中运行 `Publish academic website`，等待部署成功。
5. 访问 Pages 设置返回的网址。仓库名及用户名应以实际账号为准。

流程参考：https://docs.github.com/en/pages/getting-started-with-github-pages/using-custom-workflows-with-github-pages

GitHub 未连接时，本地文件和发布配置的完成不表示仓库已创建或网站已上线。

## 修改

- 静态内容：`index.html`
- 论文及履历数据：`assets/data.js`
- 样式：`assets/style.css`
- 搜索、语言切换：`assets/site.js`
- 照片：`assets/portrait.jpg`

修改正式文件后，重新生成 `preview.html` 以同步离线预览。请勿在仓库中存放访问令牌或其他凭据。
