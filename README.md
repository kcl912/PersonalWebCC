# 个人作品集网站

一个现代化、响应式的个人作品集网站，展示个人技能和项目作品。

## 项目特点

- 🎨 现代化设计风格
- 📱 完全响应式布局
- ⚡ 流畅的交互动画
- 🎯 清晰的导航结构
- 📧 联系表单功能

## 项目结构

```
PersonalWebWINcc/
├── index.html          # 主页面文件
├── styles.css          # 样式文件
├── main.js             # JavaScript 交互文件
├── images/             # 图片资源目录
└── README.md           # 项目说明文档
```

## 技术栈

- **HTML5** - 语义化标记和现代HTML特性
- **CSS3** - Flexbox/Grid布局、动画效果、响应式设计
- **JavaScript ES6+** - DOM操作、事件处理、交互效果

## 功能特性

### HTML 特性
- 响应式设计 meta 标签
- 语义化 HTML5 结构
- 可访问性友好的标记

### CSS 特性
- CSS Reset 重置样式
- Flexbox 和 Grid 布局
- 响应式媒体查询
- 平滑过渡动画
- 渐变背景效果

### JavaScript 特性
- 平滑滚动导航
- 表单验证和提交
- 滚动效果监听
- 元素动画出现效果
- DOM 事件处理

## 运行说明

### 本地运行

1. **克隆或下载项目文件**
   ```bash
   # 如果使用 Git
   git clone <项目地址>
   cd PersonalWebWINcc
   ```

2. **直接在浏览器中打开**
   - 双击 `index.html` 文件
   - 或右键选择"打开方式" → "浏览器"

3. **使用本地服务器（推荐）**
   ```bash
   # 使用 Python 3
   python -m http.server 8000
   
   # 使用 Python 2
   python -m SimpleHTTPServer 8000
   
   # 使用 Node.js
   npx http-server
   ```
   然后在浏览器中访问 `http://localhost:8000`

### 在线部署

可以部署到以下平台：
- GitHub Pages
- Netlify
- Vercel
- Firebase Hosting

## 自定义配置

### 修改内容
1. 编辑 `index.html` 中的文本内容
2. 替换 `images/` 目录中的图片
3. 在 `styles.css` 中调整颜色和样式
4. 在 `main.js` 中添加更多交互功能

### 添加新项目
在 `index.html` 的项目部分添加新的项目卡片：
```html
<div class="project-card">
    <img src="images/your-project.jpg" alt="项目名称">
    <h3>项目名称</h3>
    <p>项目描述</p>
</div>
```

## 浏览器兼容性

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 许可证

MIT License - 可自由使用和修改

## 贡献

欢迎提交 Issue 和 Pull Request 来改进这个项目！