# Privacy

WeChat Radar is designed as a local-first tool.

- Chat data is stored in a local SQLite database under `~/.wechat-radar` by default.
- The app does not upload chat records to a hosted service.
- The app reads data through your local `wx` CLI installation.
- Do not commit `*.db`, `.env.local`, logs, or generated runtime data.
- If you enable optional LLM/Codex workflows, review what data those tools receive before using them.

You are responsible for complying with local law, platform terms, and group member expectations before reading, storing, or processing chat data.

This project is for learning, research, personal evaluation, and non-commercial experimentation only. Commercial profit, commercial monitoring, paid reporting, hosted services, consulting delivery, data resale, or other revenue-generating use is prohibited. See [DISCLAIMER.md](DISCLAIMER.md) and [LICENSE](LICENSE).

## WeChat account safety

- 建议使用注册半年以上的小号或测试号，不建议直接使用主力微信号。
- 当前只建议读取历史聊天记录，用于本地检索、聚合和摘要。
- 不建议读取朋友圈，也不要自动点赞、评论、发消息、加好友、改资料或做任何写入/社交操作。
- 已测试通过的微信版本是 `4.1.9.58`；不建议在更高版本上贸然测试，版本变化可能带来不可预期的账号风险。
- 不要把包含真实聊天内容的数据库、截图或导出文件上传到公开仓库。

## Third-party and platform disclaimer

- 本项目与腾讯、微信、wx-cli 均无官方关联，未获得腾讯或微信授权、认可、赞助或背书。
- 你需要自行确认使用方式符合微信客户端规则、当地法律、组织制度和群成员隐私预期。
- 项目作者和贡献者不对账号限制、数据丢失、隐私泄露、法律纠纷、平台处罚或其它使用后果承担责任。
