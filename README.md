# 识笺 闪卡学习工具 鸿蒙原生APP

<div align="center">
  <img src="doc/app.png" alt="识笺应用效果图" width="400">
  <p><em>识笺 - 让学习更高效的闪卡工具</em></p>
</div>

## 项目介绍

**识笺**是一款基于鸿蒙系统开发的高效学习应用，采用科学的卡片学习法，帮助用户通过反复测试和记忆巩固知识。无论是语言学习、考证备考、专业技能提升还是日常知识积累，识笺都能为你提供个性化的学习体验。

**核心优势：**
- 基于科学记忆曲线，智能调整复习间隔
- 简洁优雅的用户界面，提供沉浸式学习体验
- 支持自定义闪卡内容，满足不同学习需求
- 学习进度可视化，清晰掌握学习状态
- 鸿蒙原生应用，性能流畅，体验更佳

博客文章介绍：[https://blog.csdn.net/yyz_1987/article/details/151863323](https://blog.csdn.net/yyz_1987/article/details/151863323)

已上架华为应用市场，欢迎下载体验：

[华为应用市场下载链接](https://appgallery.huawei.com/app/detail?id=com.jiujiang.shijian&channelId=SHARE&source=appshare)

## 效果展示

<div align="center">
  <img src="doc/app.png" alt="识笺应用主界面" width="200">
  <img src="doc/back.png" alt="识笺应用背面效果" width="200">
  <p><em>识笺应用界面展示</em></p>
</div>

## 技术栈
- **开发语言**：ArkTS
- **UI框架**：ArkUI
- **图表组件**：Omni-UI（58同城开源）
- **数据库**：rdbstore（字节跳动提供）

## 环境要求
- DevEco Studio 5.1.0 或更高版本
- HarmonyOS SDK API 17 或更高版本
- Node.js 14.19+ 或 16.13+ 或 18.12+
- ohpm 包管理器

## 安装步骤

1. 克隆项目到本地
```bash
git clone https://gitcode.com/nutpi/shijian.git
cd shijian
```

2. 安装项目依赖
```bash
ohpm install
```

3. 打开DevEco Studio，导入项目

4. 连接设备或使用模拟器运行项目

## 项目结构

```
shijian/
├── AppScope/           # 应用全局配置
│   ├── app.json5       # 应用配置文件
│   └── resources/      # 应用全局资源
├── entry/              # 主模块
│   ├── src/            # 源代码目录
│   │   ├── main/       # 主代码
│   │   │   ├── ets/    # ArkTS代码
│   │   │   ├── resources/ # 模块资源
│   │   │   └── module.json5 # 模块配置
│   │   ├── mock/       # 模拟数据
│   │   └── test/       # 测试代码
│   └── oh-package.json5 # 模块依赖配置
├── doc/                # 文档和效果图
└── oh-package.json5    # 项目依赖配置
```

## 使用说明

1. **创建闪卡集**：打开应用后，点击"新建闪卡集"按钮，输入标题和描述，创建属于你的学习卡片集。

2. **添加闪卡**：在闪卡集中，点击"添加闪卡"，输入正面（问题/提示）和反面（答案/详情）内容。

3. **学习模式**：进入学习模式，通过翻转卡片来测试自己的记忆。根据记忆情况，选择"再看一遍"、"基本记住"或"完全记住"。

4. **复习模式**：系统会根据你的学习情况，智能安排复习内容，帮助你巩固记忆。

5. **学习统计**：查看学习数据统计，了解自己的学习进度和掌握情况。

## 开发指南

### 代码规范
- 遵循HarmonyOS ArkTS开发规范
- 使用TypeScript强类型特性
- 组件化开发，提高代码复用性

### 数据存储
- 使用rdbstore进行本地数据持久化
- 支持卡片数据的导入导出

### 界面开发
- 使用ArkUI声明式UI框架
- 响应式设计，适配不同尺寸设备

## 版权信息
本项目基于MIT协议开源，详细信息请参阅LICENSE文件。

## 贡献指南
我们非常欢迎社区贡献！如果你有任何想法或建议，请：
1. Fork本仓库
2. 创建你的特性分支
3. 提交你的更改
4. 推送到分支
5. 发起Pull Request

## 联系方式
- GitCode Issues：如有任何问题或建议，请通过Issue与我们联系
- 微信公众号：关注公众号「nutpi」获取最新动态和技术分享

## 更新日志
### v1.0.0 (初始版本)
- 基础闪卡创建和学习功能
- 智能复习算法
- 学习数据统计
- 简洁用户界面

## Star History
[![Star History Chart](https://api.star-history.com/svg?repos=nutpi/shijian&type=Date)](https://star-history.com/#nutpi/shijian&Date)
