# Bank-Transaction-Classification 💳🔍
Welcome to my project on bank transaction classification! This project aims to classify bank purchases into different categories such as entertainment, food and drinks, taxes, and more. 📊

## Overview ℹ️
This project was my very first venture into machine learning, and let's just say, it wasn't my finest hour. 😅 However, I've decided to give it another go 2 years later, revamping the code to hopefully yield better performance. 💻

## Approach 🛠️
Utilizing the transaction description column, I employed text classification techniques to categorize bank purchases. 📝 This involved leveraging word embeddings generated through word2vec and deploying various machine learning models for accurate predictions. 🤖 Due to the multitude of classes, I had to group some together, but I'm eyeing a multi-label text classification approach for future improvements. 🌟

## Performance 📈
The overall performance, particularly on the best baseline model (SVM), showed promising results, though there's certainly room for improvement with some fine-tuning (I'll get to it eventually, I promise! 🙈). The only hiccup was with the transportation class, which had a mere 7 samples in the training data. 🚗 On stratified k-fold cross-validation, the model's performance was decent given the data that was provided.

Feel free to explore the code and contribute any insights or enhancements! Happy classifying! 🎉
