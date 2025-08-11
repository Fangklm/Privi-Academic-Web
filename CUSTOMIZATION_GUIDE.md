# 🎨 网站定制化指南

这是一份详细的指南，教你如何进一步定制这个学术网站模板。

## 📁 文件结构说明

```
Privi-Academic-Web/
├── index.html          # 主页文件 (核心)
├── main.css            # 主要样式文件
├── stylesheet.css      # 附加样式
├── CNAME              # 域名配置
├── images/            # 图片资源文件夹
│   ├── myself.jpg     # 个人头像 (需要替换)
│   └── ...           # 其他项目图片
├── work/              # 简历和工作文件
├── css/               # CSS样式文件
└── data/              # 数据文件
```

## 🖼️ 必须更换的内容

### 1. 个人头像
- 替换 `images/myself.jpg` 为你的照片
- 建议尺寸: 400x400px，正方形
- 格式: JPG 或 PNG

### 2. 个人信息
已在 `index.html` 中更新了基础信息，你需要根据实际情况修改：

```html
<!-- 在 index.html 第124行附近 -->
<div id="my-name" class="text-grey-dark">
  你的姓名<br>
</div>
<div id="my-title" class="text-grey">
  你的职位/学校
</div>
<div id="my-email" class="text-grey-light">
  你的邮箱
</div>
```

### 3. 社交媒体链接
更新第135-158行的链接：
- Google Scholar: 替换为你的学术档案
- GitHub: 已更新为 @zixuanfang
- LinkedIn: 更新为你的实际LinkedIn
- 简历: 上传你的简历到 `work/` 文件夹

### 4. About 部分
已更新基础描述，你可以进一步个性化：
- 第223-228行: 个人简介
- 第236-249行: 技能和兴趣
- 第256-271行: 教育背景

## 🎨 高级定制

### 1. 添加项目展示
在 Publications 部分 (约第400行) 添加你的项目：

```html
<div class="timeline-item">
  <div class="timeline-date">2024</div>
  <div class="timeline-content">
    <h3>Football Prediction System</h3>
    <p>A comprehensive multi-league sports analytics platform...</p>
    <a href="https://github.com/Fangklm/football-prediction-system" target="_blank">GitHub</a>
  </div>
</div>
```

### 2. 更新经验时间线
在 Experiences 部分添加你的工作/教育经历。

### 3. 自定义颜色主题
编辑 `main.css` 文件中的颜色变量：

```css
:root {
  --primary-color: #your-color;
  --secondary-color: #your-color;
  --text-color: #your-color;
}
```

### 4. 添加新的项目图片
1. 将项目截图放入 `images/` 文件夹
2. 在 HTML 中引用: `<img src="images/your-project.png" alt="Project Name">`

## 🚀 部署到 GitHub Pages

### 1. 推送更改
```bash
git add .
git commit -m "Customize website for Zixuan Fang"
git push origin main
```

### 2. 启用 GitHub Pages
1. 去到 GitHub 仓库设置
2. 找到 "Pages" 部分
3. 选择 "Deploy from a branch"
4. 选择 "main" 分支
5. 点击 "Save"

### 3. 自定义域名 (可选)
如果你有自己的域名：
1. 更新 `CNAME` 文件中的域名
2. 在域名提供商处设置 DNS 记录指向 GitHub Pages

## 📝 内容建议

### 必要内容:
- [ ] 个人头像
- [ ] 真实的联系方式
- [ ] 教育背景
- [ ] 技能列表
- [ ] 项目展示

### 可选内容:
- [ ] 工作经历
- [ ] 学术论文
- [ ] 获奖经历
- [ ] 博客文章
- [ ] 志愿活动

## 🔧 技术细节

### 响应式设计
网站已经是响应式的，会自动适配不同设备。

### SEO 优化
- 更新 `<title>` 标签
- 填写 `<meta>` 描述
- 使用有意义的 alt 文本

### 性能优化
- 压缩图片文件
- 使用适当的图片格式
- 移除不使用的 CSS/JS

## 📞 需要帮助？

如果在定制过程中遇到问题：
1. 查看浏览器开发者工具的错误信息
2. 参考原始模板文档
3. 搜索相关 HTML/CSS 教程
4. 联系技术社区求助

## 🎯 下一步

1. **立即行动**: 替换个人头像和基本信息
2. **内容完善**: 添加真实的项目和经历
3. **样式调整**: 根据个人喜好调整颜色和布局
4. **定期更新**: 保持内容的新鲜度

---

*祝你打造出独特的个人网站！* 🌟 