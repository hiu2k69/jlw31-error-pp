# 🚀 PP试产不良统计系统

一个基于 **Google Sheets + Google Apps Script** 开发的 **PP试产不良管理平台**，实现不良数据实时同步、图片展示、状态统计及多批次管理，无需数据库即可快速部署。

## ✨ 功能特点

- 📊 Google Sheets 实时同步数据
- 📦 支持多个批次（Sheet自动识别）
- 🖼️ 根据 ID 自动加载对应不良图片
- 🔍 支持 ALL / NG / OK 状态筛选
- 📈 自动统计 NG、OK 及总数量
- 🔄 一键刷新最新数据
- 📱 响应式设计，支持 PC 与手机
- ⚡ Loading 动画、Skeleton Loading、图片预览

## 🛠 技术栈

- HTML5
- CSS3
- JavaScript (ES6)
- Google Sheets
- Google Apps Script (JSONP).

## 📁 项目结构

```
Project/
├── index.html
├── images/
│   ├── JLW31/
│   ├── DRH44/
│   └── ...
└── README.md
```

## 📋 数据格式

| ID | Problem | Cause | Fix | Date | Status |
|----|---------|-------|-----|------|--------|

## 🚀 使用方法

1. 创建 Google Sheets 数据表
2. 部署 Google Apps Script（Web App）
3. 配置 `SCRIPT_URL`
4. 上传对应图片到 `images/{LOT}/`
5. 打开 `index.html` 即可使用

## 🎯 适用场景

- PP试产
- EP试产
- QA / QE
- PE工程
- 不良分析
- 客户审核

---
**Author:** 阮明孝 SMITH 