# Operations reporting

**A live performance dashboard, and a layer that keeps a whole company informed through WhatsApp, on time, every day.**

*Showcase page. The code is private because it runs a live business; a walkthrough is available on request.*

---

## What it does

- **Live dashboard:** the CRM's home page shows the day, the week, agents, technicians, the call center and the money, as it happens.
- **Scheduled reports:** snapshots of the dashboard go out to the team's WhatsApp groups on a schedule, morning and evening, daily and weekly.
- **Hourly AI analysis:** every hour the numbers go to Gemini, which writes a short analysis of the agents and the call center: what's going well, what's slipping, what to do now.
- **Instant alerts:** possible lost leads, escalations, callbacks and customer payment findings arrive in the right group within minutes, with the call recording and a voice clip attached.
- **Small touches:** automatic reactions to the team's messages, such as a good-morning reaction.
- **Control:** every send is scheduled, sent once and only once, logged, and editable from the CRM's settings, from the wording to the time.

Built after the AI QA system (see [ai-qa-coaching](https://github.com/alon005/ai-qa-coaching)), to get its findings and the day's numbers to the people who act on them.

It is part of [Ava Connects](https://github.com/alon005/ava-connects).

**Stack:** WhatsApp API (WHAPI) · Twilio · Gemini · Cloudflare Workers · automated dashboard screenshots

— Alon Schneidman · [GitHub](https://github.com/alon005) · [LinkedIn](https://www.linkedin.com/in/alonschneidman)
