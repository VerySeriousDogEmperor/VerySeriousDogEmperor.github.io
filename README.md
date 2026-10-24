# Cyrex 的试验博客

独立 Hexo 源码工作区，用于从零验证写作、预览和 GitHub Pages 发布。

- Node.js 24；依赖由 package-lock.json 锁定。
- 安装：`npm ci`。
- 构建：`npm run build`。
- 预览：`npm run server -- --ip 127.0.0.1 --port 4000`。
- 正式文章：`source/_posts`；本地草稿：`source/_drafts`；公共资源：`source/images`。
- 草稿及其资源保持在 `_drafts` 下，默认不提交、不构建。
- 推送 main 后，Actions 自动构建和部署。仓库 Pages 的 Source 需要设为 GitHub Actions。
- `public/version.txt` 保存构建提交，用于确认实际上线的版本。

这是博客源码，不是旧程序所说的“生成产物发布目录”。不要使用旧程序的“同步 public 到 GitHub 仓库”功能覆盖此目录。新版应用的发布流程尚待实现。

示例文章和图片均为本次测试创建，不包含旧博客或用户私人文章。
