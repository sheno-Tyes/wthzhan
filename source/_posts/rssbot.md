---
title: rssbot telegram 订阅
---

项目地址：https://github.com/iovxw/rssbot。

申请机器人

首先需要申请一个Telegram机器人，非常简单，直接对话Telegram机器人之父（@BotFather），发送/newbot给它，之后输入你的机器人的名字,获得api

```
wget https://github.com/iovxw/rssbot/releases/download/v1.4.4/rssbot-v1.4.4-linux.zip  
unzip rssbot-v1.4.4-linux.zip  
./rssbot DATAFILE TELEGRAM-BOT-TOKEN  
```

/rss       - 显示当前订阅的 RSS 列表，加 raw 参数显示链接  
/sub       - 订阅一个 RSS: /sub http://example.com/feed.xml  
/unsub     - 退订一个 RSS: /unsub http://example.com/feed.xml  
/unsubthis - 使用此命令回复想要退订的 RSS 消息即可退订, 不支持 Channel  
/export    - 导出为 OPML
