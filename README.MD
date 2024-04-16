# Tugas 3 Pembelajaran Mesin

## Data Diri 🥇

| Nama                  |      NPM      | Kelas |
| --------------------- | :-----------: | :---: |
| Sofia                 | 2108107010006 |   A   |

## Studi Kasus

- Prediksi penyakit jantung berdasarkan data klinis yang tersedia

## Dataset

Dataset yang digunakan yaitu :

- [Heart Disease](https://archive.ics.uci.edu/dataset/45/heart+disease)

## Source Code

- [ANN.ipynb](https://github.com/SofiaFei/2108107010006_Pertemuan_11_ANN/blob/main/ANN.ipynb)
- [Contoh ANN pada Artikel](https://github.com/SofiaFei/2108107010006_Pertemuan_11_ANN/blob/main/No.1.ipynb)

## Cara Menjalankan Code

1. Making virtual environment: 
```bash
python3 -m venv nama_env
```
2. Activate virtual environment:
```bash
source env_name/bin/activate
```
3. Install requirements :
```bash
pip install -r requirements.txt
```
4. Jalankan semua code cell secara berurutan

## Perbandingan Akurasi SVM dan ANN
### SVM
Akurasi yang didapat dengan menggunakan model SVM yaitu sebesar 89%. 
![image](https://github.com/SofiaFei/2108107010006_Pertemuan_11_ANN/assets/111619251/cec71600-4b80-448f-93b0-5d0a80a3d4a9)
### ANN
Akurasi yang didapat dengan menggunakan model ANN yaitu sebesar 91,38%. 
![image](https://github.com/SofiaFei/2108107010006_Pertemuan_11_ANN/assets/111619251/06d0ae62-1cf6-46f6-ac91-c0dcd72bacfd)

### Kesimpulan
Dalam kasus heart disease, model dengan menggunakan ANN(Artificial Neural Network) memiliki hasil akurasi yang lebih baik jika dibandingkan dengan SVM(Support Vector Machine). Dimana ANN memiliki akurasi 91,38%, sedangkan SVM 89%.
