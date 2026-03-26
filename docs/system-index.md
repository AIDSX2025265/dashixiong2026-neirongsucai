# 基础资料总表

更新时间：2026-03-21
来源：塔斯历史备份 / 旧工作区 / old OpenClaw 配置
说明：这份是给当前助手长期接手用的“总索引”，Telegram 旧 token 按用户要求忽略。

## 1. 当前确认存在的系统

### 飞书
用途：主通信 / 多维表格 / 文档与知识库
现状：历史资料完整，包含应用配置、表格信息、故障排查记录

已确认：
- 飞书应用配置存在
- 飞书多维表格配置存在
- 飞书断联 / WebSocket 问题排查记录存在
- 飞书 wiki / doc 相关链接存在

### 微博 → 飞书 → 公众号 自动化
用途：采集微博内容，同步飞书，再上传公众号草稿箱
现状：历史资料完整，包含配置、脚本、流程、问题记录

已确认：
- 微博采集配置存在
- 飞书同步配置存在
- 公众号配置存在
- 项目目录结构和脚本说明存在

### OpenClaw 历史配置
用途：模型、渠道、网关、插件、搜索能力配置
现状：存在完整旧配置文件，可作为追溯来源

### 小红书 / Coze / 生图工作流
用途：小红书链接读取、工作流调用、图片生成
现状：历史资料存在，含 token 痕迹和流程经验

## 2. 关键链接索引

### 飞书
- 小墨 7 天指南：
  https://my.feishu.cn/wiki/YkWgwqSchi9xW3kEuZscAm0lnFf
- 微博采集飞书表格：
  https://my.feishu.cn/base/QJIObOhZna6cvPs1FU1cQGgMnFf?table=tblLlr6KwBucbpT0

### GitHub
- 主仓库：
  https://github.com/AIDSX2025265/dashixiong2026.git
- xiaomo-starter-kit：
  https://github.com/mengjian-github/xiaomo-starter-kit
- Pi Coding Agent：
  https://github.com/badlogic/pi-mono

### 平台 / 服务
- 智谱 AI 开放平台：
  https://open.bigmodel.cn/
- OpenClaw 社区（历史记录里写作 ClawdHub）：
  https://clawdhub.com

## 3. 项目与目录痕迹

### 历史 Windows 工作目录
- `C:\Users\chuanheng\.openclaw\workspace\weibo-crawler\`
- `C:\Users\chuanheng\.openclaw\workspace\skills\weibo-to-wechat\`
- `C:\Users\chuanheng\.openclaw\workspace\skills\weibo-to-wechat-extension\`
- `C:\Users\chuanheng\.openclaw\workspace\weibo-to-wechat-simple\`

### 当前可参考备份位置
- `/home/dsx2025666/.openclaw/memory-backup/0309localbackup/`
- `/home/dsx2025666/.openclaw/workspace-tars/`

## 4. 对当前助手最有用的长期结论

1. 飞书资料不是没有，而是主要沉在塔斯历史备份里。
2. API、链接、项目配置确实有保留，且比较完整。
3. Telegram 旧 token 不作为当前整理重点。
4. 真正需要长期保留的是：
   - 飞书资产
   - API / 密钥索引
   - 项目入口
   - 自动化工作流说明
5. 后续优先从这些文件继续追：
   - `memory-backup/0309localbackup/MEMORY.md`
   - `memory-backup/0309localbackup/openclaw.json`
   - `memory-backup/0309localbackup/skills/weibo-to-wechat/config.json`

## 5. 下一步建议

如果继续整理，优先补三份：
- `docs/feishu-assets.md`
- `docs/private-config-index.md`
- `docs/automation-projects.md`
