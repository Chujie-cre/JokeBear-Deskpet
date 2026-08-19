

<div align="center">

# 🐻 自嘲熊桌宠 (JokeBear-Deskpet) 🐻

<img src="http://find.kingdomofown.cn/wp-content/uploads/2025/05/bear.png" alt="自嘲熊桌宠" width="200"/>

<p><strong>用一只会自嘲的小熊，温暖每个奋斗的日子</strong></p>

</div>

> **注意：** 本项目目前仍处于开发阶段，仅供测试使用。

## 📝 项目简介

自嘲熊桌宠是一个基于Electron开发的桌面伴侣应用，它会在您的桌面上呈现一个可爱的熊形象，陪伴您的工作与学习时光。无论是忙碌的工作日还是放松的休息时间，自嘲熊都会用幽默的自嘲金句和可爱的动画为您带来欢乐与放松。

## ✨ 特色功能

- **多样互动**: 点击、拖拽、喂食、抚摸等多种互动方式，每种互动都有不同的动画和反应
- **自嘲金句**: 定期展示幽默的自嘲语录，缓解您的工作压力
- **多种状态**: 工作、休息、奔跑、睡醒等多种状态动画，生动有趣
- **任务系统**: 每日任务和互动记录，增加使用趣味性
- **自定义设置**: 可调整大小、透明度、互动频率等多项设置
- **系统托盘**: 最小化到系统托盘，随时可唤醒

## 🖼️ 预览

<div align="center">
  <img src="http://find.kingdomofown.cn/wp-content/uploads/2025/05/bear1.png" alt="自嘲熊" width="300"/>
  <img src="http://find.kingdomofown.cn/wp-content/uploads/2025/05/bear2.png" alt="UI界面" width="300"/>
</div>

## 📥 安装方法

### 系统要求
- Windows 10/11
- 或其他支持Electron的平台

### 下载安装
1. 从[发布页面](https://github.com/Chujie-cre/JokeBear-Deskpet/releases)下载最新版本
2. 解压文件到您想要的位置
3. 运行`start.bat`或`dist`文件夹中的可执行文件

### 从源码运行
```bash
# 克隆仓库
git clone https://github.com/Chujie-cre/JokeBear-Deskpet.git

# 进入项目目录
cd JokeBear-Deskpet

# 安装依赖
npm install

# 启动应用
npm start
```

## 📖 使用指南

- **启动应用**: 双击应用图标或运行start.bat启动自嘲熊
- **基本互动**: 
  - 鼠标点击熊熊触发随机互动
  - 拖拽熊熊到桌面任意位置
  - 右键点击打开菜单
- **主页面**: 通过系统托盘图标或托盘菜单中的“主页”访问主页面，查看宠物状态、每日任务和互动选项
- **设置页面**: 在主页面中访问设置，自定义宠物外观和行为

## 🛠️ 开发技术

- **框架**: Electron
- **前端**: HTML, CSS, JavaScript
- **UI设计**: 现代化UI界面，采用FontAwesome图标
- **打包工具**: electron-builder

## 📂 项目结构

```
JokeBear-Deskpet/
├── assets/             # 资源文件夹(图片、动画等)
├── src/                # 源代码
│   ├── main.js         # 主进程代码
│   ├── preload.js      # 预加载脚本
│   └── renderer/       # 渲染进程代码
│       ├── index.html  # 主窗口HTML
│       ├── home.html   # 主页面HTML
│       ├── home.js     # 主页面脚本
│       └── ...         # 其他界面和样式文件
├── dist/               # 打包输出目录
└── package.json        # 项目配置
```

## 🤝 参与贡献

我们欢迎所有形式的贡献，无论是新功能、文档改进还是错误修复：

1. Fork本仓库
2. 创建您的特性分支 (`git checkout -b feature/amazing-feature`)
3. 提交您的改动 (`git commit -m '添加了一些很棒的特性'`)
4. 推送到分支 (`git push origin feature/amazing-feature`)
5. 创建一个Pull Request

## 🚀 项目规划

- [ ] 增加更多互动动画
- [ ] 支持用户自定义形象和语录
- [ ] 添加更多主题和皮肤
- [ ] 实现网络同步功能
- [ ] 添加声音效果

## 📄 开源协议

本项目采用[MIT协议](LICENSE)开源。

## 📮 联系方式

- 项目维护者: [Chujie-cre](https://github.com/Chujie-cre)
- 项目链接: [GitHub仓库](https://github.com/Chujie-cre/JokeBear-Deskpet)

---

<div align="center">
  <p>用一只会自嘲的小熊，温暖每个奋斗的日子</p>
  <p>Copyright © 2025 雏结</p>
</div>
