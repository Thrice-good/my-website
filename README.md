# My Website

一个应用启动器风格的个人主页，托管在 GitHub Pages。

## 访问地址

👉 https://thrice-good.github.io/my-website/

## 项目结构

```
my-website/
├── index.html          # 主页（应用启动器）
├── apps/
│   └── tools/
│       └── index.html  # 工具箱（计算器/单位换算/颜色转换/Base64）
└── README.md
```

## 如何添加新应用

1. 在 `apps/` 目录下创建新文件夹，如 `apps/myapp/`
2. 在其中创建 `index.html`
3. 在主页 `index.html` 的 `.apps-grid` 中添加卡片：

```html
<a href="apps/myapp/" class="app-card">
    <div class="app-icon icon-xxx">🎯</div>
    <div class="app-name">应用名称</div>
    <div class="app-desc">应用描述</div>
</a>
```

4. 推送到 GitHub

## 图标颜色类

- `icon-todo` - 粉紫渐变
- `icon-tools` - 蓝青渐变
- `icon-games` - 绿青渐变
- `icon-notes` - 粉黄渐变
- `icon-weather` - 浅色渐变
- `icon-music` - 紫渐变
- `icon-calculator` - 粉紫渐变
- `icon-links` - 绿青渐变

## 技术栈

- 纯 HTML/CSS/JavaScript
- 无框架依赖
- 响应式设计
- 深色主题

---

由 QClaw 构建于 2026-04-18
