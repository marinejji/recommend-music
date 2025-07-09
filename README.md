 # 基于协同过滤算法的音乐推荐系统

## 项目简介

本项目是一个基于**协同过滤推荐算法**的高端现代化音乐推荐系统，采用 Python3、Django 框架开发，结合 MySQL 数据库和 Echarts 可视化，致力于为用户提供个性化的音乐推荐与数据分析体验。

---

## 主要特色

- 🎵 **协同过滤推荐算法**：根据用户行为和兴趣，智能推荐音乐内容。
- 📊 **Echarts 数据可视化**：多维度展示音乐数据、用户行为、评分分布等，支持词云、曲线、饼图等多种图表。
- 💻 **高端现代化 UI**：采用 Bootstrap 5、Google Fonts、FontAwesome，界面简洁大气，响应式设计适配多端。
- 🔒 **用户系统**：支持注册、登录、个人中心、收藏、评分、评论等功能。
- 🗂️ **标签体系**：音乐多标签分类，支持标签筛选与管理。
- 📈 **后台管理**：Django Admin 后台，便于数据和用户管理。
- 🛠️ **易于部署和扩展**：代码结构清晰，便于二次开发和功能拓展。

---

## 技术栈

- Python 3.x
- Django 框架
- MySQL 数据库
- Echarts 可视化
- Bootstrap 5 + FontAwesome + Google Fonts
- HTML5/CSS3/JavaScript

---

## 快速开始

### 1. 安装 MySQL 数据库

请先安装 MySQL，并记住数据库账号密码。

### 2. 新建数据库并导入数据

使用 Navicat 或其他工具新建数据库 `recommend`，并导入项目根目录下的 `music_recommend.sql` 文件。

### 3. 配置 Python 环境

建议使用虚拟环境，安装依赖：

```bash
pip install -r requirements.txt -i https://pypi.mirrors.ustc.edu.cn/simple/
```

### 4. 启动项目

```bash
python manage.py runserver
```

### 5. 访问系统

浏览器打开 [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

---

## 默认账号

- 管理员账号：admins
- 密码：admins

---

## 目录结构

- `music/`：音乐推荐相关应用
- `templates/`：前端页面模板
- `static/`：静态资源（CSS/JS/图片）
- `media/`：媒体资源（音乐封面等）
- `recomend/`：Django 主配置
- `music_recommend.sql`：数据库结构与初始数据

---

## 部署与开发建议

- 推荐使用 Python 虚拟环境管理依赖
- 数据库字符集建议使用 `utf8mb4`
- 如需二次开发，建议先阅读 `music/` 和 `templates/` 目录下的代码

---

## 交流与反馈

如有问题或建议，欢迎提 Issue 或联系开发者。
