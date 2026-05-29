# 谢斌摄影作品集

线上地址：https://xiebin-x.github.io

---

## 这是什么

爸爸（谢斌）的摄影作品集网站。静态单页应用，部署在 GitHub Pages。

- 30 个作品词条，含系列组图
- 桌面端：2400px/Q88 原图
- 手机端卡片：1200px/Q75 缩略图
- 手机端详情：2400px/Q88 原图（摄影网站不牺牲画质）

---

## 本地路径

```
~/Desktop/谢斌作品集网站/谢斌摄影作品网站设计历史版本/第一版/
```

---

## 文件结构

```
index.html        ← 单页应用，所有 CSS / JS 内联
data.js           ← 30 个作品词条（标题、年份、分类、描述、图片路径）
images/           ← 原图 2400px/Q88
images/mobile/    ← 手机卡片缩略图 1200px/Q75
```

---

## 推送更新

```bash
cd "~/Desktop/谢斌作品集网站/谢斌摄影作品网站设计历史版本/第一版/"
git add -A
git commit -m "描述改动"
git push "https://xiebin-x:[TOKEN]@github.com/xiebin-x/xiebin-x.github.io.git" main
```

Token 从 GitHub Settings → Developer settings → Personal access tokens 生成，勾选 `repo` 权限，用完即删。

---

## 加新照片

把照片放进 `桌面/谢斌作品集网站/新增区/`，对 Claude Code 说：

> 照片助手，处理谢斌摄影新增区

---

## 完整技术文档

在 Obsidian：`YUN/1.人生项目/2.《深耕擅长》.../mvp 实验一：爸爸的摄影作品集网站/`
