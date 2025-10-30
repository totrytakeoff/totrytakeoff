# ⚡ 快速参考卡片

这是一个快速查找指南，帮助你快速定位需要的信息。

---

## 🚀 30秒快速开始

```bash
# 1. 选择风格（可选，默认使用完整版）
cp README_MINIMAL.md README.md

# 2. 全局替换用户名
# 用编辑器查找替换： totrytakeoff → 你的用户名

# 3. 提交
git add .
git commit -m "feat: 个性化README"
git push
```

---

## 📁 文件速查

| 你想要... | 查看这个文件 |
|----------|------------|
| 🌟 完整功能的模板 | `README.md` |
| 🎯 简洁的模板 | `README_MINIMAL.md` |
| 🎨 炫酷的模板 | `README_CREATIVE.md` |
| 💼 专业求职模板 | `README_PROFESSIONAL.md` |
| 📖 详细使用说明 | `USAGE_GUIDE.md` |
| 🎨 选择风格帮助 | `STYLE_GUIDE.md` |
| 📊 项目总结 | `PROJECT_SUMMARY.md` |
| ⚡ 快速参考（本文件） | `QUICK_REFERENCE.md` |

---

## 🎨 快速主题切换

在所有组件中查找并替换 `theme=` 参数：

### 热门主题

```markdown
# 炫酷系
theme=radical           # 🔴 红黑 - 动感
theme=synthwave         # 💜 紫粉 - 赛博朋克
theme=dracula           # 🟣 紫色 - 德古拉
theme=algolia           # 🔵 青蓝 - 科技感

# 优雅系
theme=tokyonight        # 🌃 深蓝 - 东京夜景
theme=onedark           # 🌑 深色 - One Dark
theme=nord              # 🧊 冷色 - 北欧风
theme=github_dark       # ⚫ 黑色 - GitHub深色

# 清新系
theme=vue               # 💚 绿色 - Vue风格
theme=gruvbox           # 🟤 大地色 - 复古
theme=buefy             # 🟦 蓝绿 - 清新
```

---

## 🔧 必改项速查

### 全局查找替换

| 查找 | 替换为 | 位置 |
|------|--------|------|
| `totrytakeoff` | 你的GitHub用户名 | 全部文件 |
| `[Your Name]` | 你的姓名 | README头部 |
| `your.email@example.com` | 你的邮箱 | 联系方式部分 |
| `yourprofile` | 你的LinkedIn用户名 | 社交媒体 |
| `yourhandle` | 你的Twitter用户名 | 社交媒体 |
| `yourwebsite.com` | 你的个人网站 | 社交媒体 |

### 项目相关

```markdown
# 查找所有项目引用
project1, project2, project3, project4

# 替换为你的真实仓库名
awesome-app, my-portfolio, cool-project, etc.
```

---

## 🐍 蛇动画快速配置

### 3步启用

1. **启用Actions**
   - 仓库 → Settings → Actions → General
   - 选择 "Allow all actions"

2. **设置权限**
   - 同一页面 → Workflow permissions
   - 选择 "Read and write permissions"
   - ✅ 勾选 "Allow GitHub Actions to create and approve pull requests"

3. **手动运行**
   - Actions 选项卡 → Generate Snake → Run workflow

### 验证
检查是否有 `output` 分支生成

---

## 🎯 组件快速添加

### 添加技术徽章

```markdown
![技术名](https://img.shields.io/badge/显示文字-颜色?style=for-the-badge&logo=图标名&logoColor=white)

# 示例
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
```

**查找图标：** [Simple Icons](https://simpleicons.org/)  
**生成徽章：** [Shields.io](https://shields.io/)

### 添加统计卡片

```markdown
# 基础统计
![Stats](https://github-readme-stats.vercel.app/api?username=用户名&theme=主题名)

# 语言统计
![Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=用户名&theme=主题名)

# 连续贡献
![Streak](https://github-readme-streak-stats.herokuapp.com/?user=用户名&theme=主题名)
```

### 添加项目卡片

```markdown
[![Repo](https://github-readme-stats.vercel.app/api/pin/?username=用户名&repo=仓库名&theme=主题名)](https://github.com/用户名/仓库名)
```

---

## 🎨 常用参数速查

### GitHub Stats 参数

```markdown
&show_icons=true           # 显示图标
&hide_border=true          # 隐藏边框
&include_all_commits=true  # 包含所有提交
&count_private=true        # 包含私有仓库
&hide=stars,issues         # 隐藏特定数据
&theme=radical             # 主题
&bg_color=000000           # 背景颜色
&title_color=00FF00        # 标题颜色
&text_color=FFFFFF         # 文字颜色
```

### Top Languages 参数

```markdown
&layout=compact            # 紧凑布局
&layout=donut              # 甜甜圈图
&langs_count=8             # 显示语言数
&hide=html,css             # 排除语言
&exclude_repo=repo1,repo2  # 排除仓库
```

### Streak Stats 参数

```markdown
&theme=radical             # 主题
&hide_border=true          # 隐藏边框
&date_format=M%20j%5B%2C%20Y%5D  # 日期格式
```

---

## 📐 布局技巧

### 居中对齐

```markdown
<div align="center">
  内容
</div>
```

### 左右并排

```markdown
<img align="left" width="47%" src="图片1" />
<img align="right" width="47%" src="图片2" />
```

### 表格布局

```markdown
| 列1 | 列2 | 列3 |
|-----|-----|-----|
| A   | B   | C   |
```

---

## 🐛 常见问题快速解决

| 问题 | 解决方案 |
|------|---------|
| 卡片不显示 | 检查用户名，等待3-5分钟 |
| 主题不生效 | 检查拼写，确保 `theme=名称` 格式正确 |
| 蛇不动 | GitHub显示为静态，下载文件查看动画 |
| 图片加载慢 | 减少组件数量或更换主题 |
| 链接失效 | 检查URL拼写，确保仓库公开 |
| 排版错乱 | 检查Markdown语法，删除多余空格 |

---

## 📊 推荐组合方案

### 🥇 极简主义者

```
组件选择：
✓ 简洁标题
✓ GitHub Stats (1个)
✓ Top Languages (1个)
✓ 技术徽章 (10个以内)
✓ 社交链接 (3-4个)

主题：tokyonight
文件：README_MINIMAL.md
```

### 🥈 视觉系开发者

```
组件选择：
✓ 动态打字标题
✓ 波浪横幅
✓ Stats + Streak
✓ Trophy
✓ 蛇动画
✓ 技术徽章 (全部)
✓ 项目卡片

主题：algolia / synthwave
文件：README_CREATIVE.md
```

### 🥉 求职者

```
组件选择：
✓ 专业标题
✓ 工作经验
✓ 技能表格
✓ 认证列表
✓ Stats
✓ 项目表格
✓ 联系方式

主题：nord / github_dark
文件：README_PROFESSIONAL.md
```

### 🏆 开源贡献者

```
组件选择：
✓ 全部统计卡片
✓ Trophy
✓ Contribution Graph
✓ 蛇动画
✓ 精选项目
✓ 技术栈完整展示

主题：radical
文件：README.md (完整版)
```

---

## 🎨 配色方案速查

### 红色系
```
radical, merko, synthwave
```

### 蓝色系
```
tokyonight, algolia, nord, cobalt, react
```

### 紫色系
```
dracula, onedark, monokai
```

### 绿色系
```
vue, gruvbox, chartreuse-dark
```

### 黑白系
```
highcontrast, github_dark, default
```

---

## ⌨️ 快捷操作

### VS Code 快捷键

```
Ctrl+H (Win) / Cmd+H (Mac)    # 查找替换
Ctrl+F (Win) / Cmd+F (Mac)    # 查找
Ctrl+D (Win) / Cmd+D (Mac)    # 选择下一个相同项
Alt+Click                      # 多光标编辑
```

### Git 命令

```bash
git status              # 查看状态
git add .               # 添加所有文件
git commit -m "消息"    # 提交
git push                # 推送

# 回退修改
git checkout README.md  # 撤销单个文件
git reset --hard        # 撤销所有修改（危险！）
```

---

## 📱 测试检查单

- [ ] 桌面浏览器查看
- [ ] 手机浏览器查看
- [ ] 所有图片加载正常
- [ ] 所有链接可点击
- [ ] 主题颜色统一
- [ ] 没有拼写错误
- [ ] 用户名全部替换
- [ ] 个人信息准确

---

## 🔗 有用链接

| 资源 | 链接 |
|------|------|
| **GitHub Stats** | https://github.com/anuraghazra/github-readme-stats |
| **Streak Stats** | https://github.com/DenverCoder1/github-readme-streak-stats |
| **Trophy** | https://github.com/ryo-ma/github-profile-trophy |
| **Typing SVG** | https://readme-typing-svg.demolab.com/demo/ |
| **Shields.io** | https://shields.io/ |
| **Simple Icons** | https://simpleicons.org/ |
| **Color Picker** | https://htmlcolorcodes.com/ |
| **Markdown Guide** | https://www.markdownguide.org/ |

---

## 💡 专业提示

### ✅ 推荐做法

- 保持信息真实
- 定期更新内容
- 统一视觉风格
- 移动端友好
- 链接都有效

### ❌ 避免做法

- 过度夸大技能
- 过多组件导致加载慢
- 混乱的配色
- 失效的链接
- 拼写错误

---

## 🎯 效率提升

### 批量操作

使用编辑器的**多光标**功能：
1. 选中一个 `totrytakeoff`
2. `Ctrl+D` (或 `Cmd+D`) 多次
3. 一次性全部替换

### 预览技巧

安装 VS Code 插件：
- **Markdown Preview Enhanced**
- **Markdown All in One**

---

## 📞 需要更多帮助？

| 如果你想... | 查看 |
|------------|------|
| 了解每个组件详细配置 | `USAGE_GUIDE.md` |
| 选择合适的风格 | `STYLE_GUIDE.md` |
| 查看项目概览 | `PROJECT_SUMMARY.md` |
| 快速开始（本文件） | `QUICK_REFERENCE.md` |

---

<div align="center">

## 🎉 你已经准备好了！

**现在就开始定制你的GitHub个人主页吧！** 🚀

### 记住：简单开始，逐步完善！

</div>

---

**最后更新：** 2025-10-30  
**版本：** 1.0  
**作者：** AI Assistant

