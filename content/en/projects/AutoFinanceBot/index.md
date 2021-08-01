---
title: "AutoFinance Telegram Bot"
weight: 850
project_timeframe: Oct 2020
---

Access the Telegram bot <a href="https://t.me/AutoFinanceBot" target="_blank" rel="noopener noreferrer">here</a>!<br>
View the full project <a href="https://github.com/hideyukikanazawa/AutoFinanceBot" target="_blank" rel="noopener noreferrer">here</a>.

---
### Introduction

<br>

#### AutoFinance Bot assists you with managing cash flow, helping you focus on a prudent & healthy lifestyle! 🤙


The Telegram bot is a one stop solution for tracking your daily expenses, income, as well as big ticket purchases. There are two options to view your tracked records; the first way is to view them in a concise `summary` table, the second way in a more detailed `catalogue` page. 

Additional features include a `Premium Plan` which gives paying users extra functionalities and a `Q&A section` to help out with users' burning questions. There is also a `Give Feedback` (WIP) option allowing users to direct their concerns straight to the developer. 

The python-based service is hosted on Heroku, with a the database being a managed PostgreSQL service. 

View the telegram bot [here](https://t.me/AutoFinanceBot)!

---

#### Technology stack
Python | Telegram Bot API | PostgreSQL | Heroku
:-------------------------:|:-------------------------:|:-------------------------:|:-------------------------:
<img src="img/python.png" width="100">  |  <img src="img/telegram_bot.png" width="100"> | <img src="img/postgres.png" width="100"> | <img src="img/heroku.png" width="100">


---

### Motivation

The author of this project and his partner felt it was cumbersome to update their daily expenses over excel spreadsheets. They tried finance management mobile apps that provided similar experiences, however those fell short too. Thus one day the author decided to build something different from the ground up. Being integrated into their main networking app of choice, it was seamless to switch between messaging their loved ones and recording their next pizza expense. 

With [more than 500 million active monthly users](https://cybercrew.uk/blog/telegram-statistics), Telegram has a large global footprint in modern networking and is expected to grow at an accelerated pace. Although WhatsApp was the most downloaded app in 2019, Telegram had not reached its peak and is now the [most downloaded non-gaming app worldwide](https://cybercrew.uk/blog/telegram-statistics/).

Telegram stores users' messages and media over their cloud hosting platform instead of locally on the device. This means your conversations can be easily ported to any device, mobile or web. 

This was an important decisive factor as a finance management bot should remain highly available and easily accessible. Moreover, Telegram Bot API's interface is developer-friendly with easy to manipulate RESTful endpoints. 

---

View the full project <a href="https://github.com/hideyukikanazawa/AutoFinanceBot" target="_blank" rel="noopener noreferrer">here</a>!