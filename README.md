# IELTS 学习打卡系统

一个专为雅思学习打造的桌面应用，帮助你跟踪学习进度、记录成绩、可视化学习数据。

## 功能特性

### 📅 每日打卡
- 每天完成听力和阅读练习的打卡
- 显示当前连续打卡天数
- 累计打卡天数统计

### ⏱ 学习计时
- 精确的学习时长计时器
- 暂停/继续功能
- 今日学习时长和次数统计

### 📝 学习记录
- 记录每次学习的时长和成绩
- 支持听力、阅读、写作、口语四项分数
- 按时间倒序查看历史记录

### 📊 数据统计
- 总学习时长统计
- 平均每日学习时长
- 最高分数和平均分数
- 学习时长趋势图表
- 成绩趋势图表

## 安装和运行

### 安装依赖
```bash
npm install
```

### 运行应用
```bash
npm start
```

### 打包应用
```bash
npm run build
```

## 技术栈

- **Electron** - 跨平台桌面应用框架
- **Chart.js** - 数据可视化图表库
- **原生 JavaScript** - 无框架依赖，轻量高效

## 数据存储

所有数据都存储在本地，使用 Electron 的 userData 目录：
- Windows: `%APPDATA%/ielts-study-tracker`
- macOS: `~/Library/Application Support/ielts-study-tracker`
- Linux: `~/.config/ielts-study-tracker`

## 使用建议

1. **每日打卡**：养成每天完成听力和阅读练习的习惯
2. **使用计时器**：准确记录学习时长，了解自己的学习投入
3. **记录分数**：每次练习后记录分数，追踪进步情况
4. **查看统计**：定期查看数据统计，调整学习策略

## 开发说明

项目结构：
```
ielts/
├── main.js          # Electron 主进程
├── preload.js       # 预加载脚本
├── index.html       # 主界面
├── styles.css       # 样式文件
├── app.js           # 应用逻辑
├── package.json     # 项目配置
└── README.md        # 说明文档
```

## 许可证

MIT License
