# 🔍 ATML Lab 7 — Attention Encoder-Decoder (English → Hindi)

## 📌 Course

**Advanced Topics in Machine Learning (ATML)**
SVKM's NMIMS

---

## 🎯 Objective

* Implement **Bahdanau Attention** in Seq2Seq models
* Improve translation quality over simple Encoder-Decoder
* Visualize attention weights
* Build an interactive application using **Gradio**

---

## 🧠 Concepts Covered

* Encoder-Decoder Architecture
* Attention Mechanism (Bahdanau Attention)
* Sequence-to-Sequence Learning
* Machine Translation (English → Hindi)
* Attention Heatmap Visualization

---

## ⚙️ Model Architecture

| Component      | Details          |
| -------------- | ---------------- |
| Encoder        | LSTM             |
| Decoder        | LSTM + Attention |
| Embedding Size | 128              |
| Hidden Size    | 256              |
| Layers         | 2                |
| Dropout        | 0.3              |

---

## 🚀 Features

* Translate English sentences to Hindi
* Compare:

  * ✅ Attention Model (Lab 7)
  * ❌ Simple Encoder-Decoder (Lab 6)
* Visualize **attention heatmap**
* Interactive **Gradio frontend**

---

## 🖥️ Application Preview

![App UI](ATML_Lab7_image.png)

---

## 📊 Results & Observations

* Attention model produces **more meaningful translations**
* Simple model often:

  * Outputs incorrect or incomplete translations
* Attention mechanism:

  * Focuses on relevant input words
  * Reduces context bottleneck

---

## 🔍 Example

| Input       | Attention Output | Simple Output |
| ----------- | ---------------- | ------------- |
| how are you | आप क्या है       | यह भी         |

---

## 📈 Key Insights

* Attention improves alignment between source and target words
* Helps handle longer sequences
* Provides interpretability via heatmaps

---

## 🛠️ Tech Stack

* Python
* PyTorch
* NumPy
* Matplotlib / Seaborn
* Gradio

---

## 📁 Project Structure

```text
I010_ATML_Lab7/
│
├── I010_ATML_Lab7.ipynb
├── ATML_Lab7_image.png
├── README.md
```

---

## 🏁 Conclusion

The Attention mechanism significantly improves the performance of Seq2Seq models by allowing the decoder to dynamically focus on relevant parts of the input sequence, resulting in better translation quality.

---

## 📌 Author

**Jaden Castelino**
