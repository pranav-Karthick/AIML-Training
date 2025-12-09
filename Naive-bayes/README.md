# Naive Bayes Classifiers – AIML Training

This task demonstrates implementation of **Naive Bayes classifiers**
using synthetic data and sentiment analysis examples.

---

## 1. Multinomial Naive Bayes

Used for **text classification & sentiment analysis** where
features are **word frequencies / counts**.

### Formula

P(Class | Text) ∝ P(Class) × Π P(wordᵢ | Class)

### Example Use Case
- Movie review sentiment classification
- Tweet polarity detection
- Email topic categorization

---

## 2. Bernoulli Naive Bayes

Used when features are **binary (0 or 1)** representing
presence or absence.

### Formula

P(x | y) = Π pᵢˣ (1 − pᵢ)^(1−x)

### Example Use Case
- Spam detection
- Binary sentiment features
- Categorical classification

---

## Dataset

Synthetic datasets were used:
- Multinomial NB → Sentiment texts.
- Bernoulli NB → Feature presence/absence data.

---

## Models Covered

✅ Theory of Bayes Theorem  
✅ Synthetic dataset creation  
✅ Model training (Sklearn)  
✅ Probability prediction  
✅ Visualization of probabilities

---


