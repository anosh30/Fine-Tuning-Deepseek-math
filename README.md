Overview  

This repository contains fine-tuning models for creative mathematical problem-solving tasks. The assignment consists of three main tasks:  

1. **Math Riddle Factory** – Fine-tuning a model to generate mathematical riddles.  
2. **Math Meme Repair** – Training a model to correct viral math meme mistakes.  
3. **Creative Math Problem Solver** – Solving math problems using creative AI approaches, such as emoji-based math.  

---

## 📁 Project Structure  

📂 GenAI_Assignment4
│── 📜 README.md (This file)
│── 📜 Math Riddle Factory.ipynb (Solution for Task 1)
│── 📜 Math Meme Repair.ipynb (Solution for Task 2)
│── 📜 Creative Math Problem Solver.ipynb (Solution for Task 3)
│── 📜 Creative Math Problem Solver testing.ipynb (Testing notebook for Task 3)

## 🚀 Solutions  

### **1️⃣ Math Riddle Factory**  
**Goal:** Fine-tune GPT-2/TinyLlama to generate mathematical riddles.  
- Created a dataset of **30 riddles with solutions**.  
- Fine-tuned a model for **2-3 epochs**.  
- Generated and evaluated **5 new riddles**.  
- Included the **best 3 riddles with solutions** in the notebook.  

📂 **Solution:** [`Math Riddle Factory.ipynb`](./Math%20Riddle%20Factory.ipynb)  

---

### **2️⃣ Math Meme Repair**  
**Goal:** Train a model to fix incorrect viral math memes.  
- Collected **20 incorrect math memes** and their explanations.  
- Fine-tuned a model to correct and explain errors.  
- Tested on **3 new incorrect math memes**.  
- Added a **before/after meme example** and a funny **“error rating”**.  

📂 **Solution:** [`Math Meme Repair.ipynb`](./Math%20Meme%20Repair.ipynb)  

---

### **3️⃣ Creative Math Problem Solver**  
**Goal:** Solve math problems with creativity and humor.  
- Chose the **Emoji Math Solver** challenge.  
- Created a **dataset of 30 emoji-based problems with solutions**.  
- Fine-tuned a model to **interpret and solve emoji equations**.  
- Tested on **3 new emoji math problems**.  

📂 **Solution:** [`Creative Math Problem Solver.ipynb`](./Creative%20Math%20Problem%20Solver.ipynb)  
📂 **Testing Notebook:** [`Creative Math Problem Solver testing.ipynb`](./Creative%20Math%20Problem%20Solver%20testing.ipynb)  

---

## 🔗 Gradio Deployment  

The solutions have been deployed using **Gradio**

## 🛠️ Setup & Execution  

### **Requirements**  
Ensure you have the following libraries installed:  
```bash
pip install transformers torch datasets numpy pandas gradio
