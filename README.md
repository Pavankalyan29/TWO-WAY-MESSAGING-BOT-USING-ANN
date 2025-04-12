# Two-Way Messaging Bot 🤖💬  
*An AI-powered chatbot for enhanced stakeholder communication at educational institutions*

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-2.0%2B-orange)
![NLTK](https://img.shields.io/badge/NLTK-3.7%2B-green)
![Flask](https://img.shields.io/badge/Flask-2.3%2B-lightgrey)

A conversational AI system designed for **Keshav Memorial Group** to facilitate continuous improvement through stakeholder engagement. Built with natural language processing and neural networks for contextual conversations.

---

## 🚀 Key Features
- **Two-way communication** with contextual awareness
- **500+ pre-defined responses** across 100+ intent categories
- **ANN-based response generation** (5-layer neural network)
- **Multi-domain knowledge base** (Admissions, Academics, Placements, etc.)
- **0.75+ confidence threshold** for accurate responses
- **Customizable interface** with Flask web integration

---

## 🛠 Tech Stack
- **Core AI**: `Python` | `PyTorch` | `NLTK`
- **Backend**: `Flask` | `NumPy`
- **NLP**: Tokenization | Stemming | Bag-of-Words
- **Architecture**: 5-layer Neural Network (128 hidden units)
---

## 📦 Installation
1. **Clone repository:**
   ```bash
   git clone https://github.com/your-username/two-way-bot.git
   cd two-way-bot
2. **Install dependencies:**
   ```bash
   pip install torch nltk flask numpy
3. **Download NLTK data:**
   ```bash
   python -c "import nltk; nltk.download('punkt')"
---

## 🧠 Training the Model
1. **Prepare dataset:** Update `intents.json`

2. **Train the neural network:**
   ```bash
   python train.py

- Trains for 50 epochs (default)
- Saves model to `data.pth`
---

## 💬 Using the Chatbot
1. **Start the bot:**
   ```bash
   python chat.py
2. **Sample interaction:**
   ```bash
   You: What's NGIT's placement record?
   KMES_BOT: In the first outgoing batch, around 23 companies visited campus...
---

## 📂 Project Structure
    ```bash
    .
    ├── train.py             # Model training script
    ├── chat.py              # Chat interface
    ├── model.py             # Neural network architecture
    ├── nltk_utils.py        # NLP functions
    ├── intents.json         # 500+ training patterns
    ├── data.pth             # Trained model weights
    └── requirements.txt
---

## 🔧 Future Improvements
- Add voice interface
- Implement emotion recognition
- Expand to regional languages
- Integrate with institutional databases
- Develop web dashboard (Flask)
---

## 💡 Why This Project?
### Bridging Communication Gaps in Education
Educational institutions like **Keshav Memorial Group** handle thousands of stakeholder queries daily—from students and parents to faculty and recruiters. Traditional communication methods (emails, notices, or static FAQs) are:
- Time-consuming for staff
- Frustrating for users seeking instant answers
- Limited in tracking engagement

This bot solves these challenges by:
✅ **Automating 80%+ of routine queries** (admissions, placements, academics)<br>
✅ **Providing 24/7 instant responses** via natural conversations<br>
✅ **Capturing interaction analytics** to improve institutional services

### Tech-Driven Stakeholder Engagement
Unlike basic chatbots, this project:
🔹 Uses **AI/ANN models** (not just rule-based responses) for contextual understanding<br>
🔹 **Learns from interactions** to improve future responses<br>
🔹 **Scalable across departments** with customizable intents

---

