# 暗语宝 / AnyuBao

**暗语宝** — 基于确定性置换加密的隐私通讯工具

> AnyuBao — Deterministic permutation encryption based privacy communication tool

## Features / 功能特点

- 🔒 **确定性加密** — 固定密码本映射，同一明文每次加密结果相同
- 📧 **加密邮件** — 可发送加密/普通邮件，支持好友管理
- 🛠️ **独立工具** — 免费加密/解密工具，不消耗积分
- 👥 **邀请裂变** — 邀请码机制，邀请人/被邀请人均获积分奖励
- 🌙 **暗色主题** — 一键切换明暗模式
- 📱 **移动优先** — 响应式设计，完美适配手机浏览器

## How to Use / 使用方法

1. 打开 暗语宝.html 文件（在浏览器中直接打开）
2. 注册账号（注册赠送 500 积分）
3. 发送加密邮件 / 使用加密工具

> **加密原理**：基于 Fisher-Yates 洗牌 + 固定种子生成字符映射表，对汉字和 ASCII 字符进行确定性替换。
> **Encryption**: Uses Fisher-Yates shuffle with fixed seed to generate character mapping table, performs deterministic substitution on CJK and ASCII characters.

## Points System / 积分系统

| 操作 | 消耗积分 |
|------|---------|
| 注册赠送 | +500 |
| 发送加密邮件 | -30 |
| 阅读解密邮件 | -30 |
| 加密工具（工具页） | 免费 |
| 解密工具（工具页） | 免费 |

## Tech Stack / 技术栈

- 单文件 HTML + CSS + JavaScript（零依赖）
- localStorage 数据持久化
- Fisher-Yates 洗牌算法
- CJK 基本区 20992 汉字 + 95 ASCII = 21087 字符

## License / 许可证

MIT License — 详见 [LICENSE](LICENSE) 文件