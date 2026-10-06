<div align="center">

# ⚡ LiveSpark

### Real-time analytics for TikTok LIVE creators

Understand your audience. Track your performance. Grow your LIVE.

[LiveSpark](https://livespark.live)

</div>

---

## About LiveSpark

LiveSpark is an analytics platform built for TikTok LIVE creators.

It provides real-time and historical insights into LIVE sessions, helping creators understand their audience, engagement and performance.

The platform collects and processes LIVE activity to transform raw events into meaningful analytics and actionable insights.

---

## ✨ Features

LiveSpark provides creators with tools to analyze their TikTok LIVE activity, including:

- 📊 Real-time LIVE analytics
- 👥 Audience insights
- 💬 Comments and engagement tracking
- 🎁 Gifts and monetization analytics
- ❤️ Likes tracking
- ➕ Followers tracking
- 🔄 Shares tracking
- 📈 Historical LIVE performance
- ⚡ Real-time dashboard updates
- 📱 Multi-account management

Additional analytics and insights are continuously being developed.

---

## 🏗 Platform

LiveSpark is built as a collection of independent services.

Each service has its own repository, deployment lifecycle and responsibilities.

```text
                    TikTok LIVE
                         │
                         ▼
                 ┌───────────────┐
                 │  Live Engine  │
                 │               │
                 │ Event capture │
                 │ & processing  │
                 └───────┬───────┘
                         │
                         ▼
                 ┌───────────────┐
                 │      API      │
                 │               │
                 │ Business logic│
                 │ & analytics   │
                 └───────┬───────┘
                         │
                ┌────────┴────────┐
                │                 │
                ▼                 ▼
         ┌─────────────┐    ┌─────────────┐
         │  Database   │    │  Realtime   │
         │             │    │   Events    │
         └─────────────┘    └──────┬──────┘
                                   │
                                   ▼
                           ┌───────────────┐
                           │    Web App    │
                           │               │
                           │   Analytics   │
                           │   Dashboard   │
                           └───────────────┘
