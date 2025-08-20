# 🌟 Emoji Prediction

Have you ever wished your text messages could automatically capture the emotions behind your words? That’s exactly what the Emojifier App does! 🎉

Instead of writing plain text like:

> “Congratulations on the promotion! Let’s get coffee and talk. Love you!”

…the emojifier can enrich it with expressive emojis:

> “Congratulations on the promotion! 👍 Let’s get coffee and talk. ☕ Love you! ❤️”

---

## 📖 Overview

This project implements a **machine learning model** that predicts the most suitable emoji for a given text sentence.

For example:

- “Let’s go see the baseball game tonight!” → ⚾  
- “I’m feeling so happy today!” → 😄  
- “This pizza is amazing!” → 🍕

By using **word embeddings**, the model generalizes well even with a small dataset.  
It learns semantic relationships between words, so it can associate unseen words like “adore” with ❤️ even if only “love” appeared in training.

---

## 🛠️ Features
- Predicts emojis based on text input  
- Leverages pre-trained word vectors for better understanding  
- Works effectively with small datasets  
- Can be integrated into messaging/chat applications  

---

## 📂 Project Structure
```text
Emoji-Prediction-Using-ML-main/
|── datasets/             # Training and testing datasets
│   ├── test.py           # Model Testing
│   ├── train.py          # Model training
│   ├── x.py
|── Emoji Prediction Using ML
|── Emoji_Prediction_Using_ML
```
---

## 🚀 Installation
Clone the repository:
```bash
git clone https://github.com/your-username/Emoji-Prediction-Using-ML.git
cd Emoji-Prediction-Using-ML
```
Create and activate a virtual environment (recommended):

```bash
python -m venv venv
source venv/bin/activate   # On Mac/Linux
venv\Scripts\activate      # On Windows
```
Install dependencies:

```bash

pip install -r requirements.txt
```
---
## 📊 Dataset
https://www.kaggle.com
"Twitter Emoji Prediction"

---
## 🧠 Training
To train the model, run:

```bash

python src/train.py
```
---
## 🎯 Usage
Predict an emoji for a sentence:

```bash

python src/predict.py --text "I am feeling great today!"
```
---
## Expected output:

Input: I am feeling great today!  
Predicted Emoji: 😄

---
## 📈 Results
Achieves good accuracy on small training data using pre-trained embeddings.

Generalizes well to unseen words due to semantic understanding.

---

## 🔮 Future Work
Support multiple emojis per sentence

Integration with chat apps (WhatsApp, Messenger, Slack, etc.)

Real-time prediction API

---

## 🤝 Contributing
Contributions are welcome!

Fork the repo

Create a new branch (feature/your-feature)

Commit changes

Open a Pull Request

