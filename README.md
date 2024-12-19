<h1 align="center"> NLP With HuggingFace Transformers </h1>
<p align="center"> Berisi tentang pipeline dari HuggingFace Transformers untuk keperluan NLP (Natural Language Processing)</p>

<div align="center">

<img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54">
<img src="https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white">

</div>

<h2 align="center"> Analisis </h2> 
Hasil Sentimen:

    Sebagian besar teks bernada positif (3 dari 5 teks).
    Contoh: "I love this product!" → POSITIVE, Confidence: 0.9996.

Distribusi Sentimen:

    Sentimen positif lebih dominan dibanding negatif.
    Bias ke arah sentimen positif terlihat dalam dataset.

Confidence Score:

    Mayoritas prediksi memiliki confidence tinggi (>0.99).
    Teks ambigu seperti "Not bad, could be better." memiliki confidence lebih rendah (0.6784).

Kesimpulan:

    Model bekerja dengan baik pada teks jelas.
    Ambiguitas pada teks tertentu memerlukan perhatian lebih.