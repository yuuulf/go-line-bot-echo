# go-line-bot-echo
echo bot

### 環境変数を設定

```
$ export CHANNEL_SECRET="your_line_channel_secret"
$ export CHANNEL_TOKEN="your_line_channel_access_token"
$ export PORT="8080"
```

### Webhook設定
[Line Developers](https://developers.line.biz/en/)で、サーバのグローバルIPアドレスかドメインをWebhookに設定する。  
例："https://myLinebot.com/callback"