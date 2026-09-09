# 冯彬 · 个人简历

静态个人简历页面，使用 HTML5 + CSS3 + Font Awesome 6（CDN 图标）。

## 文件说明

| 文件 | 说明 |
| ---- | ---- |
| `index.html` | 简历页面结构 |
| `style.css` | 页面全部样式 |
| `README.md` | 使用说明 |

## 运行方式

### 方式一：直接打开（最简单）

双击 `index.html`，用浏览器打开即可预览。

> 注意：页面图标使用 Font Awesome CDN，预览时需要联网。

### 方式二：本地 HTTP 服务器（推荐）

在项目根目录（web01）打开终端，执行：

```bash
# Python 3
python -m http.server 8000
```

浏览器访问：http://localhost:8000/docs/resume/index.html

也可以使用 VS Code 的 Live Server 插件：在 `index.html` 上右键 → "Open with Live Server"。