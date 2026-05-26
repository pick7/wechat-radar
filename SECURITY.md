# Security

## Reporting

Please open a GitHub security advisory or a private issue if you find a vulnerability.

This project is for learning, research, personal evaluation, and non-commercial experimentation only. Commercial profit or commercial advantage is prohibited. See [DISCLAIMER.md](DISCLAIMER.md) and [LICENSE](LICENSE).

## Local data

The most sensitive asset is your local SQLite database. Keep it outside synced folders and do not publish it. The default path is `~/.wechat-radar/radar.db`.

## WeChat usage boundary

- 建议使用注册半年以上的小号或测试号，不建议直接使用主力微信号。
- 当前只建议读取历史聊天记录。
- 不建议读取朋友圈，也不要自动点赞、评论、发消息、加好友、改资料或做任何写入/社交操作。
- 已测试通过的微信版本是 `4.1.9.58`；不建议在更高版本上贸然测试。
- 本项目与腾讯、微信、wx-cli 均无官方关联，未获得腾讯或微信授权、认可、赞助或背书。
- 用户自行承担账号、数据、合规和平台风险。

## No warranty

The software is provided as-is. The authors and contributors do not guarantee availability, accuracy, security, legal compliance, account safety, or compatibility with any WeChat, wx-cli, Node.js, macOS, or third-party service version.

## Command execution

The app invokes `wx` via `child_process.execFile` with argument arrays. Avoid changing this to shell string execution.
