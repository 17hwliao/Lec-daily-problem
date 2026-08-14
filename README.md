# LEC 每日两题

纯静态网页，按访问者的本地日期自动显示当天的两道洛谷题。

## 本地预览

直接双击打开 `index.html` 即可。

## 更新题单

在 `index.html` 中编辑 `problemDays`。键名为 `YYYY-MM-DD`，值为当天两道洛谷题号：

```js
'2026-08-31': ['P1000', 'P1001']
```

页面不依赖服务器或定时任务：日期变化后，打开或刷新网页就会自动切换题目。

## 部署

仓库可直接部署到任意静态托管服务，例如 Tencent EdgeOne Pages、Cloudflare Pages 或 Netlify。部署时将根目录作为静态文件目录，入口文件为 `index.html`。
