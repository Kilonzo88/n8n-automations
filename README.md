# ⚡ n8n Automations

A simple, growing collection of **n8n workflow exports**.

This repo is intentionally lightweight. It’s mainly for me — but structured clearly enough that anyone curious can follow along.

---

## 📁 Repo structure

Automations are grouped by folder. Each folder represents a **theme or domain**.

```
/
├── email-automation/
│   ├── *.json
│   └── *.json
└── (more folders coming)
```

* Each `.json` file = one n8n workflow export
* No nested folders (for now)
* Folder count will grow over time

---

## 🗂 Automations

### 📧 email-automation/

| Workflow file | Description                                                 |
| ------------- | ----------------------------------------------------------- |
| `*.json`      | Email-related automations (parsing, sending, routing, etc.) |

> Workflow descriptions are intentionally short — details live inside n8n.

---

## ▶️ How to use

1. Open n8n
2. Import the JSON workflow
3. Configure credentials
4. Activate

Nothing fancy.

---

## 🧠 Notes

* Secrets are **never** stored in this repo
* This README is an index, not documentation
* New folders = new automation domains

---

*Last updated whenever I add something worth keeping.*
