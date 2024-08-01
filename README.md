# Mini-Project-Day-23---AI-Aplication-Series

# Sentiment Analysis with Transfer Learning

This repository contains code and dataset for sentiment analysis using transfer learning with models like BERT, DistilBERT, and RoBERTa.

## Background

Model pre-trained seperti BERT, DistilBERT, dan RoBERTa telah menunjukkan keunggulan dalam berbagai tugas NLP karena mereka dilatih menggunakan korpus teks yang sangat besar, memungkinkan mereka untuk memahami konteks kata dalam kalimat dengan sangat baik. Transfer learning memungkinkan kita untuk mengambil pengetahuan yang telah diperoleh oleh model-model ini selama pre-training dan menerapkannya pada tugas-tugas spesifik, bahkan ketika kita hanya memiliki dataset yang relatif kecil untuk tugas tersebut. Dengan cara ini, kita dapat meningkatkan akurasi model dan mengurangi waktu yang diperlukan untuk pelatihan ulang, karena model sudah memiliki pemahaman yang kuat tentang bahasa. Ini sangat berguna dalam berbagai aplikasi, seperti analisis sentimen, pemrosesan bahasa alami, dan tugas-tugas terkait lainnya.

## Evaluation Results

```python
BERT Results:
  eval_loss: 0.356
  eval_accuracy: 0.845
  eval_f1: 0.84
  eval_precision: 0.845
  eval_recall: 0.845

DistilBERT Results:
  eval_loss: 0.365
  eval_accuracy: 0.835
  eval_f1: 0.83
  eval_precision: 0.835
  eval_recall: 0.835

RoBERTa Results:
  eval_loss: 0.348
  eval_accuracy: 0.855
  eval_f1: 0.85
  eval_precision: 0.855
  eval_recall: 0.855
```
