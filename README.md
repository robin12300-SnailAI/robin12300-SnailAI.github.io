# 🐌 蜗牛 AI 官方网站

> 我们的使命：让 AI 真正成为澳洲华人的"机甲"。

## 🌐 在线访问

**主页**：https://robin12300-snailAI.github.io/

- 📚 [线上课大纲](https://robin12300-snailai.github.io/online-course/) — 24 节课时系统课
- 🏫 [线下课大纲](https://robin12300-snailai.github.io/offline-course/) — 面对面深度实战
- ❓ [常见问题 FAQ](https://robin12300-snailai.github.io/faq/) — 12 个高频问答
- 📺 [YouTube 频道](https://www.youtube.com/@snailai-au) — 公开课 / 直播回放
- 💬 微信公众号：**蜗牛 AI 在澳洲**
- 🎬 视频号：**蜗牛 AI-AU**

---

## 📂 仓库结构

```
robin12300-SnailAI.github.io/
├── index.html              # 官网首页（桌面 + 响应式）
├── mobile.html             # 官网首页（手机版）
├── faq/
│   ├── index.html          # FAQ 桌面
│   └── mobile.html         # FAQ 手机
├── online-course/
│   ├── index.html          # 线上课桌面
│   └── mobile.html         # 线上课手机
├── offline-course/
│   ├── index.html          # 线下课桌面
│   └── mobile.html         # 线下课手机
├── assets/
│   ├── snailai_logo.png
│   ├── team/               # 团队成员二维码
│   ├── posters/            # 课程海报 + 公众号视频号二维码
│   ├── qr_ai_needs.png     # AI 刚需填写二维码
│   └── qr_community.png    # 社群二维码
├── 404.html                # 错误页
├── version.json            # 版本/团队元数据
└── README.md               # 本文件
```

## 🛠️ 技术栈

- **纯 HTML/CSS/JavaScript**（零构建步骤，零依赖）
- **设计风格**：瑞士国际主义（Swiss Design）— 暖白底 + 深墨字 + 珊瑚橙强调
- **双语**：所有文字 `data-zh` / `data-en` 属性 + JS 切换 + localStorage 记忆
- **响应式**：桌面优先 + 移动端 `@media` 适配
- **字体**：Inter（英文）+ PingFang SC（中文）+ JetBrains Mono（代码）
- **部署**：GitHub Pages（自动从 `main` 分支部署）

## 🚀 如何修改网站

### 1. 克隆仓库

```bash
git clone https://github.com/robin12300-SnailAI/robin12300-SnailAI.github.io.git
cd robin12300-SnailAI.github.io
```

### 2. 修改文件

直接用编辑器修改 HTML，保存即可。**无需任何构建步骤**。

### 3. 提交 + 推送

```bash
git add .
git commit -m "feat: 修改 XXX 页面"
git push origin main
```

### 4. 自动上线

推送后 1-2 分钟内，GitHub Pages 自动部署到 https://robin12300-snailai.github.io/

> 💡 **改完不用手动部署** — 这是 GitHub Pages 最大的优势。

## 👥 团队协作

| 成员 | 权限建议 | 负责区域 |
|------|---------|---------|
| Robin (Owner) | Admin | 全站 + 审批 |
| Michael Guo | Admin | 联合管理 |
| James 蒋培 | Write | AI 工具 + FAQ |
| Jason 谢锦 | Write | 社群支持 |
| Sean 吴清 | Write | 算力答疑 |

> ⚠️ 推荐在仓库 Settings → Branches 开启 main 分支保护：
> - Require pull request before merging
> - Require 1 approval

## 🎨 设计规范

- **主色**：`#FF5B1F` 珊瑚橙（Coral Orange）
- **文字**：`#1A1A2E` 深墨色
- **背景**：`#FCFCFA` 暖白 + `#FFF9F5` 暖白渐变
- **金色点缀**：`#D4A574`（用于 logo 和品牌强调）
- **WCAG AA**：4.5:1 文字对比度
- **间距系统**：4px 基础单位，倍数递增（8/12/16/24/32/48/64px）
- **断点**：640px / 768px / 1024px / 1280px

## 📜 版本历史

- **V1.0.0** (2026-07-05) — 首版上线，GitHub Pages 部署
  - 4 个主页面：首页 / FAQ / 线上课 / 线下课
  - 5 人团队展示
  - 6 个服务卡片
  - 4 个 YouTube 视频嵌入
  - 中英双语 + 桌面/手机双版

## 🤝 贡献指南

欢迎团队成员提 PR！建议流程：

1. 开新分支：`git checkout -b feat/your-name-changes`
2. 修改 + 提交
3. 推送到远程
4. 在 GitHub 开 PR，Robin 审批后合并

**禁止**：
- ❌ 不要 commit 学员/客户的个人信息
- ❌ 不要删 `assets/posters/` 里的二维码图（除非是要换）
- ❌ 不要动 `version.json`（除非版本号变更）

---

🐌 **蜗牛虽慢，坚持到底** — 一起把 AI 落地到每个澳洲华人的工作中。
