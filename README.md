# Facebook 聊天機器人簡單範例
修改自 [Facebook 官方文件](https://developers.facebook.com/docs/messenger-platform/quickstart)

## 使用

```
git clone https://github.com/aszx87410/fb-bot.git
```

把 `config.js` 裡面的兩個 key 換成自己的

再來先裝必要的套件

```
npm install
```


裝好之後，如果要 debug 的話，就是

```
npm run dev
```

如果想直接跑的，那就

```
npm run build
node bin/fb-bot
```

記得每一次重開的時候，都要 subscribe 一下，不然會沒反應

```
curl -ik -X POST "https://graph.facebook.com/v2.6/me/subscribed_apps?access_token=<token>"

```

## 教學
[[教學] Facebook Messenger API](http://huli.logdown.com/posts/709641-teaching-facebook-messenger-api)

