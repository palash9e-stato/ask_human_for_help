**Ask a Human When the AI Doesn’t Know**

This workflow shows a simple and practical way to build **responsible AI with a human backup**. The AI agent first tries its best to answer the user’s question using conversation memory. If it feels unsure or lacks confidence, it doesn’t guess or hallucinate. Instead, it clearly admits uncertainty and asks for help from a real human.

When triggered, the workflow checks whether the user has shared an email address. If not, the user is politely asked to provide one. Once an email is detected, the query is sent directly to a **Slack support channel**, where a human can step in and respond. The user is then informed that their request has been forwarded.

This approach is perfect for support bots and internal tools where trust matters, combining AI speed with human judgment for a safer, more reliable experience.
