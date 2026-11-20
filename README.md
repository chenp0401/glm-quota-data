# GLM/Qwen Coding Plan 配额数据

公开只读数据源，供配额看板前端通过 `raw.githubusercontent.com` 加载。

- `data.json` — 智谱 GLM 配额（GitHub Actions 每小时写入）
- `qwen.json` — 阿里云百炼配额（自托管采集机每 30 分钟写入）
- `users.json` — 按用户消耗统计（脱敏 label，无邮箱）

⛔ 不要往本仓库推任何密钥、Token、明文邮箱或上游原始响应。
