# 📘 LSTM (Long Short-Term Memory) – README

## 🔍 Overview
**LSTM (Long Short-Term Memory)** is a type of Recurrent Neural Network (RNN) designed to model sequential data while overcoming the **vanishing gradient problem** present in traditional RNNs.

### Common Use Cases
- Time series forecasting  
- Natural language processing (NLP)  
- Speech recognition  
- Sequence prediction  

---

## ⚠️ Why Not Vanilla RNN?
Standard RNNs struggle with long sequences because:
- Gradients **vanish** or **explode**
- They fail to capture long-term dependencies  

👉 LSTM solves this using a **memory cell and gating mechanism**

---

## 🧠 Core Concept
LSTM introduces a **cell state (Cₜ)** that carries long-term information, controlled by three gates:

1. **Forget Gate** – removes irrelevant information  
2. **Input Gate** – adds new information  
3. **Output Gate** – determines the output  

---

## ⚙️ Architecture
Each LSTM cell consists of:
- Hidden state: `hₜ`  
- Cell state: `Cₜ`  
- Gates:
  - Forget gate: `fₜ`  
  - Input gate: `iₜ`  
  - Candidate state: `C̃ₜ`  
  - Output gate: `oₜ`  

---

