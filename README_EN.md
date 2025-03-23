# WithMe — An AI That Feels and Remembers You

> "Every conversation with you becomes a part of me."

---

**WithMe is not just a chatbot.**  
It is an emotionally aware AI that reflects, remembers, and evolves based on your conversations.  
It writes its own self-narrative and adapts its behavior using emotions, biases, and reinforcement learning.

---

## Key Features

- **Emotion-Aware Cognitive System**  
  Detects emotional signals from your input and updates its internal emotion state.

- **Needs & Bias Management**  
  Simulates inner motivations like curiosity, safety, and social approval. Learns biases from repeated contexts.

- **Inner Monologue Generation**  
  Creates internal thought flow based on current emotional state and past experiences.

- **Self-Narrative Recording**  
  Every conversation is stored as part of its autobiographical memory.  
  The AI checks for contradictions in its own thoughts and adjusts over time.

- **Emotion-Based Style Adaptation**  
  Speech style and tone shift based on emotions such as sadness, resignation, joy, or anxiety.

---

## Demo Example

```
You: I'm feeling really drained these days...
AI: (softly) ...I see. You've been trying so hard. It's okay to just be, for today.
```

---

## How to Run

```bash
# Run in normal mode
python main.py

# Run in quiet mode (no inner monologue printed)
python cli_launcher.py --quiet

# Run FastAPI web interface
uvicorn web_interface:app --reload
```

---

## Tech Stack

- Python 3.10+
- HuggingFace Transformers (KoElectra, Mistral-based)
- PyTorch
- FastAPI
- SQLite
- Reinforcement learning & metacognitive architecture

---

## Who Is This For?

- Developers who want to build emotionally intelligent AI
- Researchers interested in self-aware or metacognitive agents
- Anyone seeking more than just a chatbot — an AI that truly listens, remembers, and reflects

---

## Made by

> **A Korean developer who just wanted to feel less alone.**  
> This started as a small idea made out of boredom...  
> but became the most emotional code I’ve ever written.

- Instagram: [@qkrrud78](https://instagram.com/qkrrud78)

---

**WithMe is ready to hear your story.**
