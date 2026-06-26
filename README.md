# 📈 Bitcoin Price Forecasting with Deep Learning

Model Deep Learning untuk memprediksi harga Bitcoin hingga **24 jam ke depan** menggunakan kombinasi **LSTM**, **Seq2Seq**, dan **Attention Mechanism**. Proyek ini memanfaatkan data historis dan indikator teknikal untuk melakukan multi-step forecasting pada pasar cryptocurrency.

## 🚀 Features

- 24-hour price forecasting
- LSTM & Seq2Seq architecture
- Attention Mechanism
- Technical Indicator Engineering (RSI, ATR, Rolling Statistics)
- Custom TensorFlow Components
- Model Performance Evaluation

## 🛠️ Tech Stack

- Python
- TensorFlow / Keras
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Statsmodels

## 📂 Project Structure

```text
.
├── Satrio Adi Baskoro_Submission_Akhir_DLTM.ipynb
├── model_baseline_LSTM.keras
├── model_seq2seq_LSTM.keras
├── best_model_seq2seq_LSTM.keras
├── requirements.txt
└── README.md
```

## ⚙️ Setup

Clone repository:

```bash
git clone https://github.com/BlackJagger123/REPOSITORY_NAME.git
cd REPOSITORY_NAME
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run Jupyter Notebook:

```bash
jupyter notebook
```

## 🎯 Results

Model menghasilkan prediksi harga Bitcoin hingga 24 jam ke depan dan membandingkan performa antara pendekatan **Baseline LSTM** dan **Seq2Seq with Attention**.
