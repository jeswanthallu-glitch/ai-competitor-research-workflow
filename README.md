# 🔎 AI-Powered Competitor Research Workflow

## 📌 Project Overview

This project is an AI-powered workflow built using n8n and Google Gemini. It analyzes a company's website, summarizes its services, and researches its top three competitors.

## ✨ Features

- Accepts user input through a chat trigger.
- Analyzes website content and identifies the services provided.
- Identifies three relevant competitors.
- Collects official website URLs.
- Researches annual revenue and company valuation where publicly available.
- Requests source URLs for financial information.
- Presents results in a professional comparison table.

## 🛠️ Technologies Used

- n8n — workflow automation
- Google Gemini — AI language models
- AI Agent nodes — website analysis and competitor research
- Chat Trigger — user interaction

## 🔄 Workflow Process

1. **Chat Trigger:** Receives the user's company or website request.
2. **AI Agent 1:** Summarizes the website and its services in no more than 100 words.
3. **Google Gemini Chat Model:** Powers the first AI agent.
4. **AI Agent 2:** Researches three competitors, their websites, annual revenue, and valuations.
5. **Google Gemini Chat Model 2:** Powers the second AI agent.

## 🚀 How to Use

1. Download the workflow JSON file from this repository.
2. Import it into your n8n instance.
3. Configure your Google Gemini credentials.
4. Test the workflow with a company or website.
5. Review the generated competitor comparison and verify the cited sources.

## 🔗 Project Links

- **GitHub Repository:** Add your repository URL here.
- **Live Demo:** Add your public n8n chat URL here, if available.

## 🔐 Security and Accuracy

- Keep API keys and credentials private.
- Configure Google Gemini credentials securely in n8n.
- Verify competitor information and financial figures against reliable sources.
- Treat estimates as estimates and distinguish company valuation from annual revenue.

## 📚 Learning Outcomes

- Building AI workflows in n8n.
- Connecting Google Gemini to AI agents.
- Automating website and competitor research.
- Designing multi-agent workflows.

## 👨‍💻 Author

Jeswanth Allu

## 📄 License

This project is intended for educational and learning purposes.
