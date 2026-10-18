# Transfer Learning XIANGQI

**Nama:** Fitra Adhani Saputra  
**Username GitHub:** fitra123456

## 1. Deskripsi

Proyek ini merupakan implementasi transfer learning untuk klasifikasi dua jenis bidak catur Xiangqi, yaitu horse hitam dan chariot hitam.

Model yang digunakan adalah ResNet-18 dengan tiga pendekatan:
1. Feature Extraction
2. Partial Fine-Tuning
3. Training from Scratch

## 2. Dataset

Dataset terdiri dari dua kelas:
- horse_hitam
- chariot_hitam

Jumlah data:
- 100 gambar per kelas
- Total 200 gambar

Pembagian dataset:
- Training: 80 gambar per kelas
- Validation: 20 gambar per kelas

Sehingga:
- Training: 160 gambar
- Validation: 40 gambar

## 3. Data Augmentation

Pada data training digunakan:
- RandomResizedCrop
  
