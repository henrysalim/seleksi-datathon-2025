# Pemanfaatan Computer Vision dan Explainable Artificial Intelligence untuk Mendeteksi Cacat Mikro Hasil Produksi Manufaktur

## Penyusun
1. Livia Junike [(GitHub)](https://github.com/junikxz)
2. Henry Salim [(GitHub)](https://github.com/henrysalim)
3. John Isaac Witness [(GitHub)](https://github.com/akunjone)

## Abstrak Penelitian

<p style="text-align: justify">
Lambatnya proses quality control dalam manufaktur di Indonesia mengakibatkan skala produksi menjadi kecil. Selain itu, quality control secara manual tidak efektif karena menimbulkan berbagai kerugian kesehatan dan keuangan manufaktur. Penelitian ini bertujuan untuk merancang dan mengimplementasikan sistem pengecekan kualitas produk berbasis Computer Vision, Machine Learning, dan Explainable Artificial Intelligence (XAI) untuk membantu melakukan quality control otomatis dengan mendeteksi cacat mikro pada produk pengecoran logam. Sistem yang dikembangkan, EXACT (Explainable & Autonomous Correction AI for Smart Quality Manufacturing) memanfaatkan arsitektur Convolutional Neural Network (CNN) berbasis Xception untuk melakukan klasifikasi biner produk cacat dan tidak cacat. Sistem dilengkapi visualisasi dengan bounding box, Grad-CAM untuk interpretasi visual dan output file JSON dan .txt untuk informasi mengenai cacat.  Hasil uji menunjukkan model mencapai akurasi 100% dan presisi, recall, dan F1-score yang mencapai nilai maksimum. Visualisasi prediksi dan interpretasi Grad-CAM menunjukkan kemampuan model mendeteksi dan memetakan cacat secara akurat. Harapannya penelitian ini dapat mentransformasi solusi untuk industri manufaktur modern dengan sistem cerdas yang aplikatif untuk mengurangi ketergantungan inspeksi manual dan pengambilan keputusan cepat dan presisi.
</p>

## Requirements
<ul>
<li>kagglehub</li>
<li>matplotlib</li>
<li>numpy</li>
<li>pandas</li>
<li>ipython</li>
<li>tensorflow</li>
<li>seaborn</li>
<li>Pillow</li>
<li>opencv-python</li>
<li>scikit-learn</li>
<li>scikit-image</li>
</ul>