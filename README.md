# 标题 + 文案批量生成器 · GitHub Pages 发布包

本目录是一个**可直接部署到 GitHub Pages 的静态网站**：纯前端、零依赖、无需服务器、无需域名，由 GitHub 免费托管。

## 目录内容
- `index.html` —— 生成器主程序（标题+文案批量生成、复制变灰防重复、AI 扩写提示、自定义选题）
- `.nojekyll` —— 告诉 GitHub 跳过 Jekyll 构建（纯静态站不需要）

## 发布步骤（首次约 3 分钟）
1. 注册 / 登录 GitHub：https://github.com
2. 新建仓库（New repository），名字随意，例如 `title-generator`，**可见性选 Public**
3. 把本目录的 `index.html` 和 `.nojekyll` 上传到仓库**根目录**
   - 最简：在 GitHub 网页直接把这两个文件拖进仓库
   - 或用 Git 客户端：`git add . && git commit -m "init" && git push`
4. 进入仓库 **Settings → Pages**（页面）
   - Branch 选 `main`（或 `master`）
   - 目录选 `/ (root)`
   - 点 **Save**
5. 等待 1~2 分钟，访问 `https://<你的用户名>.github.io/<仓库名>/` 即可长期使用

## 更新内容
直接覆盖 `index.html` 重新上传，刷新即生效（GitHub Pages 有约 1 分钟缓存）。

## 当前临时在线版
CloudStudio 托管（沙箱，停运会失效）：
https://595e81caf990469fac6a0993b771896c.bj10.agentos-app.net

> 想要稳定永久地址，按上面步骤发布到 GitHub Pages 即可，无需任何费用。
