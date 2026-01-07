# BMRI.JK-Stock-Forecasting-with-Binomial-Model-Monte-Carlo-CRR-vs-Empirical-

## Model Binomial & Monte Carlo

Proyek ini membahas simulasi pergerakan harga saham **PT Bank Mandiri (Persero).Tbk (BMRI.JK)** menggunakan **Model Binomial** yang dikombinasikan dengan **Simulasi Monte Carlo**.

Parameter model ditentukan menggunakan dua pendekatan:

- **Cox–Ross–Rubinstein (CRR)**
- **Pendekatan Empiris**

Hasil simulasi dibandingkan dengan harga saham aktual menggunakan ukuran error **MAE, MSE, dan MAPE**.

---

## Tujuan

- Memodelkan pergerakan harga saham BMRI secara probabilistik
- Membandingkan performa metode CRR dan empiris
- Menentukan metode dengan hasil prediksi terbaik

---

## Metode

- Binomial Random Walk
- Simulasi Monte Carlo
- Evaluasi error (MAE, MSE, MAPE)

---

## File dalam Proyek

```
├── BMRI.ipynb
├── BMRI.JK.csv
├── BI-7Day-RR.xlsx
├── requirements.txt
└── README.md
```

---

## Cara Menjalankan

1. Install dependensi:
   ```bash
   pip install -r requirements.txt
   ```
2. Jalankan notebook:
   ```bash
   jupyter notebook BRIS.ipynb
   ```

---

## Kesimpulan Singkat

Metode **Cox–Ross–Rubinstein (CRR)** memberikan hasil prediksi yang lebih akurat dan stabil dibandingkan pendekatan empiris dalam memodelkan harga saham BMRI.
