# ✈️ Airline AI Chatbot with Function Calling

An AI-powered assistant for airlines that answers customer queries and retrieves real-time ticket prices using OpenAI's function calling API. Built with Python, Gradio, and OpenAI.

![image](https://github.com/user-attachments/assets/7125c4b7-32a4-4915-97b2-e09f6f106836)

---

## 🚀 Features
- **Dynamic Ticket Pricing**: Fetches prices for destinations like London, Paris, Tokyo, etc.
- **Function Calling**: Uses OpenAI's `tools` parameter to call `get_ticket_price` autonomously.
- **Conversational UI**: Gradio-based chat interface with dark mode.
- **Short & Accurate Responses**: Follows airline guidelines for concise answers.

---

## ⚙️ Setup

### Prerequisites
- Python 3.11+
- OpenAI API key (set in `.env`)

### Installation
1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/AI-Chatbot-for-Airline-with-Function-Calling.git
   cd AI-Chatbot-for-Airline-with-Function-Calling

2. Install dependencies:
   ```bash
   pip install -r requirements.txt

3. Add your OpenAI API key to .env:
   ```bash
   OPENAI_API_KEY=your-key-here
