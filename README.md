# Meng CHU - Personal Academic Homepage

一个现代化的学术个人主页，融合了极简设计与丰富内容展示。

## 🎨 设计特点

- **深色科技主题**：深海蓝配色 + 渐变点缀
- **响应式设计**：完美适配桌面端和移动端
- **平滑动画**：滚动渐入效果
- **优雅字体**：Instrument Serif (标题) + Outfit (正文) + JetBrains Mono (代码/日期)

## 📁 文件结构

```
new-homepage/
├── index.html      # 主页面
├── style.css       # 样式文件
├── script.js       # 交互脚本
├── images/
│   └── profile.jpeg  # 个人照片
└── README.md
```

## 🚀 部署方式

### 方式一：GitHub Pages
1. 将此文件夹内容推送到 GitHub 仓库
2. 在仓库 Settings → Pages 中启用 GitHub Pages
3. 选择 `main` 分支作为源

### 方式二：本地预览
```bash
cd /Users/mengchu/Downloads/web/new-homepage
python3 -m http.server 8000
# 然后访问 http://localhost:8000
```

## ✏️ 自定义内容

### 更换头像
将新图片命名为 `profile.jpeg` 放入 `images/` 文件夹

### 修改个人信息
编辑 `index.html` 中的以下部分：
- Hero Section: 姓名、职位、简介
- Publications: 论文列表
- Experience: 工作经历
- Education: 教育背景

### 修改颜色主题
编辑 `style.css` 中的 CSS 变量：
```css
:root {
    --accent-primary: #38bdf8;   /* 主色调 */
    --accent-secondary: #818cf8; /* 次色调 */
    --bg-primary: #0a0f1a;       /* 背景色 */
}
```

## 📱 浏览器兼容性

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

---

Made with ❤️ for academic excellence

