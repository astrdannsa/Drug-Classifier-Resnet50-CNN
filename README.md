# Drug-Classifier-Resnet50-CNN
Kode ini dibuat sebagai proof-of-concept pengklasifikasian obat (drug) menggunakan CNN dengan ResNet50 pada dataset ["Pharmaceutical Drugs and Vitamins Synthetic Images dataset" yang disediakan Marionette](https://www.kaggle.com/datasets/vencerlanz09/pharmaceutical-drugs-and-vitamins-synthetic-images)

##Cara Penggunaan##
1. Install semua library yang dibutuhkan dengan menjalankan code pada bagian "Menyiapkan Workspace"
Siapkan dataset pada folder "MedClass" pada Google Drive anda. Dataset terdiri dari folder "train", "valid", dan "test" yang masing-masing berisi folder jenis obat dan file gambar untuk setiap jenis obat tersebut.
2. Load dataset dan train model dengan menjalankan code pada bagian "Melatih Model". Model akan otomatis disimpan di folder "models".
3. (Opsional) Gunakan model untuk melakukan prediksi dengan menjalankan code pada bagian "Memprediksi dengan Model". Pastikan model sudah di load dari folder "models".
