---
title: Calendar Linebot
publishDate: 2024-08-18 00:00:00
img: /assets/stock-4.jpg
img_alt: Pearls of silky soft white cotton, bubble up under vibrant lighting
description: |
  A Linebot can read message and add event to google calendar.
tags:
  - Linebot
  - LLM
  - LLaMA
  - Google API
---

#### 動機
有時候在 line 上面跟別人講好日期後，如果沒有將它紀錄下來的話，有時候會忘記，而記錄到日曆又要另外開一個app，非常的麻煩，因此便想說用設計一個Line Bot來處理line上面一些有關日程的留言，並將他自動在Google calendar上設定。

#### 使用技術
- Line Messaging API
- Google Calendar API
- Python
- Flask
- ngrok
- LLM(llama.cpp)

#### 實作
1. 使用Line Messaging API來接收line上的訊息
2. 使用Google Calendar API來新增事件
3. 使用Flask來建立server
4. 使用ngrok來將本地端的server映射到外部
5. 使用LLM來處理自然語言
6. 將處理好的訊息傳給Google Calendar API
7. 將處理好的訊息回傳給line

#### 成果展示
> line對話

![line](/assets/Calendar_Linebot/line_message.png)
> google calendar結果

![calendar](/assets/Calendar_Linebot/calendar.png)
---
