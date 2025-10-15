# ToneCrafter Bot Web

一个最简的“智能体网页入口”。将 `index.html` 中的 `YOUR_BOT_URL` 替换为你的智能体链接（例如 Coze 生成的公开访问链接），即可发布到 GitHub Pages。

## 使用步骤（GitHub Desktop）
1. **创建仓库**
   - GitHub Desktop → File → New Repository → Name: `tonecrafter-bot`（或任意）→ Create

2. **加入网页文件**
   - 把本项目的 `index.html`、`README.md` 放进仓库文件夹
   - 在 GitHub Desktop 中 Commit 到 main，然后 Publish 到 GitHub

3. **开启 GitHub Pages**
   - 在 GitHub 网站端进入仓库 → Settings → Pages
   - Source 选择 `main` 分支，Folder 选择 `/ (root)` → Save
   - 稍等片刻，GitHub 会生成网址：`https://你的用户名.github.io/你的仓库名/`

4. **替换链接**
   - 编辑 `index.html`，将 `YOUR_BOT_URL` 替换为你的智能体链接。
   - 若平台禁止 iframe，将自动显示“在新窗口打开智能体”的按钮。

## 常见问题
- **页面空白或不显示聊天窗口**：目标平台禁止 iframe。此时页面会显示跳转按钮，请点击按钮在新窗口打开。
- **麦克风/相机权限**：iframe 上已添加 `allow` 权限。若仍受限，请在目标平台内授权。
- **手机适配**：页面已做基础适配。

---

© ToneCrafter · 吉他音色智能体
