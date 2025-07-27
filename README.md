# 海外网站导航 (Bookmark Site)

一个专为海外用户设计的网站导航页面，提供精选的优质海外网站链接。

## 🌐 网站地址

访问地址：https://shipnav.shop/

## ✨ 功能特点

- 🎨 现代化响应式设计
- 🔍 实时搜索功能
- 📱 移动端友好
- 🎯 分类清晰的网站导航
- 📊 Google Analytics 数据追踪

## 📊 Google Analytics 集成

本项目已集成 Google Analytics 4 (GA4) 用于网站数据分析：

### 追踪代码
```html
<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-88G6VFT7P8"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-88G6VFT7P8');
</script>
```

### 追踪事件
- **页面浏览**：自动记录页面访问
- **链接点击**：追踪用户点击的导航链接
- **搜索行为**：记录用户搜索关键词

### 数据收集
- 页面浏览量
- 用户行为分析
- 热门链接统计
- 搜索关键词分析

## 🏗️ 技术栈

- HTML5
- CSS3 (Grid & Flexbox)
- JavaScript (ES6+)
- Google Analytics 4

## 📁 项目结构

```
bookmark-site/
├── index.html          # 主页面文件
├── README.md           # 项目说明文档
└── .gitignore          # Git忽略文件
```

## 🚀 部署说明

1. 将项目文件上传到您的Web服务器
2. 确保 `index.html` 文件位于网站根目录
3. 访问您的域名即可使用

## 📈 数据分析

通过 Google Analytics 可以查看：
- 实时访问数据
- 用户来源分析
- 页面性能指标
- 用户行为路径
- 热门内容排行

## 🔧 自定义配置

如需修改 Google Analytics 配置：
1. 在 Google Analytics 控制台获取新的跟踪ID
2. 替换 `index.html` 中的 `G-88G6VFT7P8` 为您的跟踪ID
3. 根据需要添加自定义事件追踪

## 📝 更新日志

### v1.0.0 (2024-01-XX)
- ✨ 初始版本发布
- 🎨 现代化UI设计
- 📊 集成Google Analytics
- 🔍 添加搜索功能
- 📱 响应式设计优化

## 📄 许可证

MIT License

## 🤝 贡献

欢迎提交 Issue 和 Pull Request！

---

**让世界触手可及** 🌍 