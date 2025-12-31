---
title: "我的第一篇博客文章"
date: 2025-12-31 10:30:00 +0800
categories: [记录, 博客]
tags: [Jekyll, GitHub Pages]
---

# 欢迎阅读我的博客

这是我的第一篇博客文章，使用 **Jekyll** 和 **GitHub Pages** 搭建。

## 为什么选择 Jekyll？

- 静态网站，加载速度快
- 支持 Markdown，写作方便
- 可以免费部署到 GitHub Pages

### 代码示例

```python
print("Hello, World!")
```

## 三、本地测试和预览

### 1. 启动本地服务器
在项目根目录运行以下命令启动 Jekyll 本地服务器：
```powershell
# 确保已安装依赖（首次运行需要）
bundle install

# 启动本地服务器
bundle exec jekyll serve
```

### 2. 访问本地预览
打开浏览器访问：`http://127.0.0.1:4000/`
- 本地服务器会自动检测文件变化并重新构建
- 刷新浏览器即可看到最新修改

## 四、Git提交和推送

### 1. 查看修改状态
```powershell
git status
```

### 2. 添加所有修改到暂存区
```powershell
git add .
```

### 3. 提交修改
```powershell
git commit -m "添加新文章：我的第一篇博客文章"
```

### 4. 推送到远程仓库
```powershell
git push origin master
```

## 五、验证部署结果

### 1. 等待部署完成
GitHub Pages 会在推送后自动构建和部署，通常需要 1-2 分钟。

### 2. 访问博客网站
打开浏览器访问：`https://kepler-10.github.io/`

### 3. 检查构建状态（可选）
- 登录 GitHub
- 进入你的仓库 `kepler-10.github.io`
- 点击 "Settings" > "Pages"
- 查看构建状态和日志

## 六、常用操作技巧

### 1. 添加图片
在 `assets` 目录下创建 `images` 文件夹，将图片放入其中，然后在文章中引用：
```markdown
![图片描述](/assets/images/图片文件名.jpg)
```

### 2. 调整文章布局
在文章头部添加布局设置：
```yaml
---
# ... 其他配置
layout: single
excerpt: "文章摘要"
---
```

### 3. 添加表格
```markdown
| 列1 | 列2 | 列3 |
|-----|-----|-----|
| 内容1 | 内容2 | 内容3 |
| 内容4 | 内容5 | 内容6 |
```

### 4. 添加引用
```markdown
> 这是一段引用文字
```

遵循以上步骤，你就可以轻松地经常更新你的博客了！