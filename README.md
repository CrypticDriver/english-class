# 📚 英语口语课笔记

大哥的英语口语课笔记站点。每周两节课，话题 / 范文 / 句式 / 词组精讲。

**在线查看：** https://crypticdriver.github.io/english-class/

## 结构

```
index.html          目录页（所有课程入口）
style.css           共享样式（暗色主题，手机友好）
lessons/
  YYYY-MM-DD.html   每节课一个文件，按日期命名
```

## 加新课流程（狗蛋自动）

1. 在 `lessons/` 新建 `YYYY-MM-DD.html`（复制上一节课改内容，套 `../style.css`）
2. 在 `index.html` 目录里加一个 `<a class="lesson">` 条目
3. commit + push，GitHub Pages 自动更新

---
🐕 狗蛋 (Goudan) 整理
