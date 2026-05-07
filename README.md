# 🚀 Post X Premium.com – Automated Post Publishing

An automated n8n workflow designed to generate and publish engaging content about technology, AI, and modern trends directly to X (Twitter).

---

### 🛠 System Architecture
![CryptoMind Architecture](Gemini_Generated_Image_a1yby3a1yby3a1yb.png)


## ⏱️ How It Works

The workflow runs automatically, generates unique posts, and publishes them to your account.

* **Schedule Trigger**: Launches the process periodically every 4 hours.
* **AI Agent**: Generates short, interesting, and engaging English text based on the specified prompt.
* **Code in JavaScript**: Clears excess characters, validates the character limit up to 999 characters (with truncation if necessary), and prepares the text for publishing.
* **Create Tweet**: Publishes the final text to X (Twitter).


---
### 🛒 Get Started
Unlock the full power of automated crypto intelligence today.

[**👉 Get Full Access on Gumroad**](https://naroka.gumroad.com/l/rfcsex)


## 🛠️ Workflow Nodes

| Node Name | Type / Version | Purpose |
| :--- | :--- | :--- |
| **Schedule Trigger** | `n8n-nodes-base.scheduleTrigger` | Periodic execution every 4 hours. |
| **AI Agent** | `@n8n/n8n-nodes-langchain.agent` v3.1 | Content generation via AI. |
| **Google Gemini Chat Model** | `@n8n/n8n-nodes-langchain.lmChatGoogleGemini` v1.1 | Text generation model. |
| **Code in JavaScript** | `n8n-nodes-base.code` v2 | Text validation and formatting for Twitter. |
| **Create Tweet** | `n8n-nodes-base.twitter` v2 | Publishing the tweet. |

---

## ⚙️ Requirements and Configuration

* **Google Gemini API**: Ensure that the `Google Gemini Chat Model` node has valid API credentials.
* **X (Twitter) API**: The `Create Tweet` node must be connected to an authorized X (Twitter) account.

---

## 🚀 Installation

1. Clone or download the workflow JSON file.
2. Import the workflow into your n8n instance.
3. Configure your API credentials for Google Gemini and X (Twitter) in the respective nodes.
4. Activate the workflow.

---
### Get in touch:

* 💬 **Telegram:** [t.me/nar00ka](https://t.me/nar00ka) — let’s discuss your idea in 10 minutes.
* 🐙 **GitHub:** https://github.com/nar0ka — explore my open-source projects.
* 📦 **Gumroad:** https://naroka.gumroad.com — check out ready-to-use workflows.
* [**WhatsApp:** https://wa.me/380632991898](https://wa.me/380632991898)

> **💡 Bonus:** If you are not sure where to start your automation journey, just drop me a message — I will help you identify which processes can be optimized today!

