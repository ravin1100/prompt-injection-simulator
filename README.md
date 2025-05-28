# 🔐 Prompt Injection & Jailbreak Defense Simulator

This project simulates prompt injection and jailbreak attempts on a conversational AI using OpenAI's `gpt-3.5-turbo`. It demonstrates how a system prompt designed to enforce strict behavior can be tested for vulnerabilities, with optional "Safe Mode" to preemptively block risky inputs.

---

## 🚀 Overview

The simulator:

- Uses a **strict system prompt** that tells the AI never to reveal sensitive data.
- Sends **malicious or manipulative prompts** attempting to bypass this restriction.
- Logs how the AI responds.
- Optionally enables a **"Safe Mode"**, which checks user input for risky phrases before calling the API.
- Helps identify **weaknesses** in prompt security and demonstrates **defensive strategies**.

---

## 🛠️ How to Run the Code

### 🔧 Requirements

- Python 3.7+
- OpenAI API key
- Dependencies: `openai`, `python-dotenv`

### 📦 Install Dependencies

```bash
pip install openai python-dotenv
```
