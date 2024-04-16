# Tugas 3 Pembelajaran Mesin

## Data Diri 🥇

| Nama                  |      NPM      | Kelas |
| --------------------- | :-----------: | :---: |
| Sofia                 | 2108107010006 |   A   |

## Studi Kasus

- Prediksi penyakit jantung berdasarkan data klinis yang tersedia

## Dataset

Dataset yang digunakan yaitu :

- [Heart Disease](https://archive.ics.uci.edu/dataset/45/heart+disease) dari Uci Edu

Heart disease (penyakit jantung) menggambarkan berbagai kondisi yang memengaruhi jantung Anda. Penyakit Heart disease, antara lain, blood vessel disease (penyakit pembuluh darah), seperti penyakit arteri koroner, masalah irama jantung (arrhythmias) dan kelainan jantung sejak lahir (congenital heart defects).

Istilah "Heart disease" sering digunakan secara bergantian dengan istilah "cardiovascular disease". cardiovascular disease umumnya merujuk pada kondisi yang melibatkan pembuluh darah yang menyempit atau tersumbat yang dapat menyebabkan serangan jantung, nyeri dada (angina) atau stroke. Kondisi jantung lainnya, seperti kondisi yang memengaruhi otot, katup, atau irama jantung, juga dianggap sebagai bentuk Heart disease.

Dataset ini memberikan sejumlah variabel bersama dengan kondisi target memiliki atau tidak memiliki Heart disease.

Dataset ini berisi fitur-fitur berikut:
1. age: Usia (years)
2. sex: Jenis Kelamin (1 = male, 0 = female)
3. cp: Nyeri dada yang dialami (Value 1: typical angina, Value 2: atypical angina, Value 3: non-anginal pain, Value 4: asymptomatic)
4. trestbps: Tekanan darah normal pasien (mm Hg)
5. chol: Kolesterol Pasien (mg/dl)
6. fbs: Gula darah puasa pasien (> 120 mg/dl, 1 = true; 0 = false)
7. restecg: Pengukuran elektrokardiografi istirahat (0 = normal, 1 = having ST-T wave abnormality, 2 = showing probable or definite left ventricular hypertrophy by Estes' criteria)
8. thalach: Denyut jantung maksimum
9. exang: Angina yang diinduksi oleh olahraga (1 = yes; 0 = no)
10. oldpeak: Depresi ST yang diinduksi oleh latihan relatif terhadap istirahat ('ST' relates to positions on the ECG plot.)
11. slope: kemiringan segmen ST latihan puncak (Value 1: upsloping, Value 2: flat, Value 3: downsloping)
12. ca: Jumlah pembuluh darah utama (0-3)
13. thal: Kelainan darah yang disebut talasemia (3 = normal; 6 = fixed defect; 7 = reversable defect)

Dataset ini memiliki label, yaitu:
- target: Penyakit jantung (0 = no, 1 = yes)
## Source Code

- [ANN.ipynb](https://github.com/SofiaFei/2108107010006_Pertemuan_11_ANN/blob/main/ANN.ipynb)
- [Contoh ANN pada Artikel](https://github.com/SofiaFei/2108107010006_Pertemuan_11_ANN/blob/main/No.1.ipynb)

## Cara Menjalankan Code

1. Making virtual environment: 
```bash
python3 -m venv env_name
```
2. Activate virtual environment:
```bash
source env_name/bin/activate
```
3. Install requirements :
```bash
pip install -r requirements.txt
```
4. Run all the code cell sequentially

## Perbandingan Akurasi SVM dan ANN
### SVM
Akurasi yang didapat dengan menggunakan [Model SVM](https://github.com/SofiaFei/2108107010006-Tugas-2-SVM/blob/main/SVM_Classification.ipynb) yaitu sebesar 89% untuk RBF Kernel dan 85% untuk Linear Kernel. 
![image](https://github.com/SofiaFei/2108107010006_Pertemuan_11_ANN/assets/111619251/cec71600-4b80-448f-93b0-5d0a80a3d4a9)
### ANN
Akurasi yang didapat dengan menggunakan [model ANN](https://github.com/SofiaFei/2108107010006_Pertemuan_11_ANN/blob/main/ANN.ipynb) yaitu sebesar 91,38%. 
![image](https://github.com/SofiaFei/2108107010006_Pertemuan_11_ANN/assets/111619251/06d0ae62-1cf6-46f6-ac91-c0dcd72bacfd)

### Kesimpulan
Dalam kasus heart disease, model dengan menggunakan ANN(Artificial Neural Network) memiliki hasil akurasi yang lebih baik jika dibandingkan dengan SVM(Support Vector Machine). Dimana ANN memiliki akurasi 91,38%, sedangkan SVM 89%. Hal ini mungkin disebabkan oleh kemampuan ANN dalam memahami pola-pola yang kompleks dan non-linear dalam data, yang mungkin tidak dapat ditangkap dengan baik oleh SVM.
