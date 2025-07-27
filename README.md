# 📈 LSTM Autoencoder for Time Series Anomaly Detection

This project demonstrates how to detect anomalies in time series data using an LSTM Autoencoder built with TensorFlow and run entirely in Google Colab.

It learns normal patterns in the data, reconstructs the time series, and flags any points with high reconstruction error as anomalies.

The notebook covers:
- Data normalization
- Sequence generation
- LSTM Autoencoder model
- Reconstruction error calculation
- Visualizing flagged anomalies on a plot

## 🚀 Run in Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](YOUR_NOTEBOOK_LINK)

## 📂 Project Structure

```
.
├── notebook.ipynb
├── requirements.txt
├── README.md
└── data/ (optional sample CSV)
```

## 📌 CSV Format

```
timestamp,value
2013-12-21 17:00:00,25.0
2013-12-21 18:00:00,26.1
...
```

## 📦 Requirements

See `requirements.txt`.

## ✅ How to Use

1. Upload your CSV file in Colab.
2. Run the notebook to normalize, sequence, train, and plot anomalies.
3. Adjust parameters like time steps or threshold as needed.

## 🏆 Tech Stack

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## 📚 License

Free to use for learning and portfolio projects!
