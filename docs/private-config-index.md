# 私密配置索引（本地留存）

更新时间：2026-03-21
说明：本文件仅供当前助手在本地调用，不适合在聊天里原样外发。
备注：Telegram 旧 token 按用户要求忽略，不纳入当前使用重点。

## 1. 飞书
- appId: `cli_a90390a4ffb85cda`
- appSecret: `sRMF8TfozTMylzFezuAVGDUpDGR34h2v`
- domain: `feishu`
- connectionMode: `websocket`

### 飞书多维表格
- app_token: `QJIObOhZna6cvPs1FU1cQGgMnFf`
- table_id: `tblLlr6KwBucbpT0`
- 表格链接: `https://my.feishu.cn/base/QJIObOhZna6cvPs1FU1cQGgMnFf?table=tblLlr6KwBucbpT0`

## 2. 微信公众号
- app_id: `wx5f5e925649098f00`
- app_secret: `1d3706ed0ab9d9d5766e6684c7564f1d`
- 公众号名称（历史记录）: `大师兄段子精选`
- IP 白名单历史记录: `112.32.78.24`

## 3. OpenClaw / 网关
- gateway.port: `18789`
- gateway.auth.mode: `token`
- gateway.auth.token: `5414b42f9ee9ad393666f32dce75e77a497682b44cf19609`

## 4. Web / Search
- Brave Search API Key: `BSA0gagBFb7w0Qm-5t9RlrRhlSpRna_`

## 5. 模型 / 平台相关
- wenwen-ai-claude apiKey: `sk-1QwUH132JW1qW5jXWYZ6jjpZFppP4bXaTvf84IDwPizMiDyY`
- 智谱 API Key（历史记忆）: `ed2d21f19dc349ffb8ab2e44c6c1b4d0.2nbV8ks8blAqlDAQ`
- Gemini API Key（历史记忆）: `sk-kkMwJWRBxFt36JF0IROqckDdPHUdCUmX4nItnxwlihyXx6Xd`
- Coze Token（历史记忆）: `pat_5Z07xUggyn3FaRx2nvr4EVzAINmFjdd8p0cjFcv5dnx44RvKldO1VGrHTOV08SwV`

## 6. 微博采集
- 微博 cookie（历史配置）: 已存在于旧配置中，如需运行再单独读取旧文件，不建议频繁复制
- 关键配置文件:
  - `/home/dsx2025666/.openclaw/memory-backup/0309localbackup/skills/weibo-to-wechat/config.json`

## 7. 旧配置来源
- `/home/dsx2025666/.openclaw/memory-backup/0309localbackup/openclaw.json`
- `/home/dsx2025666/.openclaw/memory-backup/0309localbackup/MEMORY.md`
- `/home/dsx2025666/.openclaw/memory-backup/0309localbackup/skills/weibo-to-wechat/config.json`

## 8. 使用原则
1. 聊天里默认不主动裸露这些值。
2. 真要调用时，优先本地读取，不手抄。
3. 旧 token / key 可能失效，实操前要做有效性判断。
4. Telegram 旧 token 暂不处理。
