# AI Chatbot using Python (TF-IDF + Cosine Similarity)

A **simple AI chatbot** implemented in Python that answers basic questions about **AI, programming, and data science**. The chatbot is **data-driven**, using a CSV dataset of questions and answers, and leverages **TF-IDF vectorization** with **cosine similarity** to find the best response.

---

## 🛠 Features

- Reads questions and answers from a **CSV file (`chatbot_data.csv`)**  
- Uses **TF-IDF vectorization** for text analysis  
- Computes **cosine similarity** to match user input with dataset questions  
- Threshold ensures relevant responses; low similarity triggers fallback message  
- Easy to expand by adding more Q&A pairs in the CSV  

---

## 💻 Technologies Used

- Python 3.x  
- Pandas  
- scikit-learn (TF-IDF, cosine similarity)  
- NumPy  
- Google Colab (for interactive use)

---

## 🚀 How to Run

1. Upload the repository to **Google Colab**.  
2. Make sure your **dataset CSV (`chatbot_data.csv`)** is ready.  
3. Run the following to upload the CSV in Colab:

```python
from google.colab import files
uploaded = files.upload()
