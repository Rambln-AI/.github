# 🤖 Rambln.AI

Rambln.AI is an AI-powered assistant that streamlines communication between product managers and engineering teams by automatically gathering, organizing, and summarizing key updates — reducing the need for status meetings and accelerating decision-making.

---

## 🚀 Features

- 🔌 Integrates with GitHub, Jira, and Slack
- 📥 Collects daily or weekly updates automatically
- 🧠 Summarizes technical updates into digestible formats
- 📤 Sends summaries to Slack, Email, or Web Dashboard
- 📊 PM-friendly dashboard for updates and queries

---

## 🛠️ Tech Stack

- **Frontend:** React + Tailwind CSS
- **Backend:** FastAPI
- **LLM Integration:** OpenAI GPT / Claude / Local LLM
- **Integrations:** GitHub API, Jira API, Slack API

---

## 📁 Project Structure

**ATTENTION:** This is just for the README atm. Will change accordingly as time goes on.
```
ai-pm-assistant/
├── backend/
│   ├── app/
│   │   ├── main.py
│   │   ├── summarizer.py
│   │   ├── connectors/
│   │   │   ├── github.py
│   │   │   ├── jira.py
│   │   │   └── slack.py
│   └── requirements.txt
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── App.jsx
│   └── package.json
│
├── prompts/
│   └── engineering_updates_prompt.txt
│
├── docs/
│   └── architecture-diagram.png
│
├── .env.example
├── README.md
└── LICENSE
```

---

## ✅ MVP Checklist

- [ ] Set up backend with FastAPI
- [ ] Implement GitHub and Jira connectors
- [ ] Design prompt and test summarization
- [ ] Slack bot integration for sending summaries
- [ ] React dashboard to display summaries

---

## 📌 Example Prompt

```text
Summarize the following updates for a product manager:
- Focus on what is done, in progress, and blocked
- Use clear, non-technical language

[User] Alice
[Update] Finished implementing login flow. Awaiting review from Bob.
[Blocker] Waiting on backend API.
```

---

## 📜 License

MIT License. See `LICENSE` file for details.

---

## 🙌 Contributing

We welcome contributions! Feel free to open issues, fork the repo, and submit PRs.

---

## 📬 Contact

Questions or suggestions? Open an issue or reach out via GitHub Discussions.

---

> Save time. Improve communication. Let AI handle the daily syncs.
