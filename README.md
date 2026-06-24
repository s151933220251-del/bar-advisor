# The Sommelier — AI 調酒顧問

> 輸入你今晚的心情與偏好，由 Claude AI 幫你挑選最適合的飲品。

**[Live Demo →](https://YOUR_USERNAME.github.io/bar-advisor)**

---

## 功能

- 根據心情、場合、口味、酒類偏好推薦飲品
- 顯示風味描述、酒精濃度、調製食材與份量
- 串接 Anthropic Claude API，每次都是個人化推薦
- 深色奢華介面，純前端，無需後端伺服器

## 使用方式

1. 前往 Live Demo 網址
2. 填入今晚心情與場合
3. 選擇口味偏好與酒類
4. 輸入你的 [Anthropic API Key](https://console.anthropic.com)
5. 點擊 **Ask the Bartender**

> API Key 只在你的瀏覽器中使用，不會被記錄或傳送至任何第三方。

## 本機執行

```bash
git clone https://github.com/YOUR_USERNAME/bar-advisor.git
cd bar-advisor
# 用任何 HTTP server 開啟，例如：
npx serve .
# 或直接用瀏覽器開啟 index.html
```

## 部署到 GitHub Pages

1. 將此 repo push 到你的 GitHub
2. 進入 repo Settings → Pages
3. Source 選擇 `main` branch，`/ (root)` 資料夾
4. 儲存後等約 1 分鐘即可透過 `https://USERNAME.github.io/bar-advisor` 存取

## 技術棧

- 純 HTML / CSS / JavaScript（無框架）
- [Anthropic Claude API](https://docs.anthropic.com) (`claude-sonnet-4-6`)
- [Tabler Icons](https://tabler.io/icons) 圖示
- 部署於 GitHub Pages

## License

MIT
