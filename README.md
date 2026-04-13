# Guild Workshop – 创意工坊系统

> 一个基于 [Guild Plugin](https://github.com/chenasyd/-GuildPlugin) 构建的创意工坊系统，允许服主和玩家轻松扩展服务器功能、共享模块与配置。

---

## 简介

**Guild Workshop** 是一个为 Guild Plugin 生态打造的创意工坊系统。  
服主可以直接从工坊下载、安装、管理由社区贡献的各种功能模块（如公告系统、成员等级、红包机制等），无需手动处理依赖或配置文件。

---

## 特性

- **一键安装** – 从工坊下载模块后放入 `modules` 文件夹，执行 `/guildmodule load` 即可加载
- **模块化设计** – 每个功能独立打包，互不干扰
- **版本兼容提示** – 自动检测插件版本，提醒配置更新
- **支持多语言** – 内置 `messages_*.yml` 外置语言文件
- **Folia 兼容** – 核心已适配 Folia 服务端

---

## 模块下载与安装

1. 从 [Releases](https://github.com/chenasyd/-GuildPlugin/releases) 下载所需模块的 `.jar` 文件
2. 将文件放入 `\plugins\GuildPlugin\modules\` 目录
3. 执行以下命令之一加载模块：
   ```bash
   /guildmodule load <模块文件名>.jar
   ```
   或直接重启服务器
4. 在游戏内使用 `/guild` 相关 GUI 管理功能

---

## 开发者指南

你可以为创意工坊贡献自己的模块。  
- 参考 [SDK 开发者指南](https://github.com/chenasyd/-GuildPlugin/blob/main/SDK-Developer-Guide.md)（请自行补充）
- 模块必须遵循 Guild Plugin 的模块规范

---

## 📄 许可证

本项目基于 [MIT License](LICENSE) 开源。

---

## 🔗 相关链接

- [Guild Plugin 主仓库](https://github.com/chenasyd/-GuildPlugin)
- [问题反馈 / 建议](https://github.com/chenasyd/-GuildPlugin/issues)

---

> ⚠️ 注意：不同版本的插件数据可能不兼容，升级前请务必备份配置文件。
