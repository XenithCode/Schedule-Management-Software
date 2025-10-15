# Schedule-Management-Software README

## 项目介绍

`Schedule-Management-Software` 是一款基于 Gradle 构建的日程管理软件，旨在帮助用户高效规划、管理个人或团队的日程安排，提升时间管理效率。该项目采用现代化技术栈，支持日程的创建、编辑、提醒与统计等功能。


## 技术栈

- 构建工具：Gradle
- 语言：Java（推测，基于 Gradle 构建体系）


## 功能特点

- **日程创建与编辑**：支持添加、修改、删除各类日程事项，设置标题、时间、优先级等属性。
- **日程提醒**：自定义提醒时间，确保重要日程不被遗漏。
- **日程统计**：直观展示日程分布、完成情况等数据，辅助时间规划决策。
- **多端兼容**：（待实现）支持桌面、移动端等多端同步日程。


## 快速开始

### 环境依赖

- JDK 1.8+
- Gradle 7.0+（或使用项目内置的 `gradlew`/`gradlew.bat` 脚本）


### 运行步骤

1. 克隆仓库：
   ```bash
   git clone https://github.com/XenithCode/Schedule-Management-Software.git
   cd Schedule-Management-Software
   ```

2. 构建项目：
   ```bash
   #  Unix/Linux/Mac
   ./gradlew build
   # Windows
   gradlew.bat build
   ```

3. 运行应用：
   ```bash
   #  Unix/Linux/Mac
   ./gradlew run
   # Windows
   gradlew.bat run
   ```


## 项目结构

```
Schedule-Management-Software/
├── src/                  # 源代码目录，包含主程序、工具类等
├── .gitignore            # Git 忽略规则配置
├── build.gradle          # Gradle 构建配置
├── gradle.properties     # Gradle 属性配置
├── gradlew               # Unix/Linux/Mac 下的 Gradle 脚本
├── gradlew.bat           # Windows 下的 Gradle 脚本
├── local.properties      # 本地环境配置（如 SDK 路径等）
├── settings.gradle       # Gradle 项目设置
└── README.md             # 项目说明文档
```


## 贡献指南

欢迎对本日程管理软件进行贡献：
1. Fork 本仓库
2. 创建特性分支（`git checkout -b feature/your-feature`）
3. 提交修改（`git commit -m 'Add some feature'`）
4. 推送到分支（`git push origin feature/your-feature`）
5. 发起 Pull Request


## 许可证

本项目采用 [MIT 许可证](https://opensource.org/licenses/MIT)，详情请查看 `LICENSE` 文件
