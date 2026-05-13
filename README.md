# Spotify Genre Classification

## Giới thiệu
Project Machine Learning dùng để dự đoán thể loại nhạc Spotify dựa trên các đặc trưng âm thanh của bài hát.

Dataset sử dụng:
Spotify Tracks Dataset trên Kaggle.

## Công nghệ sử dụng
- Python
- Pandas
- Scikit-learn
- Jupyter Notebook
- VSCode

## Các bước thực hiện

### 1. EDA
- Đọc dataset
- Kiểm tra missing values
- Xem các feature
- Phân tích genre

### 2. Data Preprocessing
- Xóa cột không cần thiết
- Chọn feature
- Chia train/test set

### 3. Modeling
Sử dụng:
- Random Forest Classifier

### 4. Evaluation
Sử dụng:
- Accuracy
- Classification Report

### 5. Save Model
Model được lưu dưới dạng:
- spotify_model.pkl

## Features sử dụng
- popularity
- duration_ms
- danceability
- energy
- key
- loudness
- mode
- speechiness
- acousticness
- instrumentalness
- liveness
- valence
- tempo

## Cấu trúc project

```text
spotify-ml-project
│
├── data
├── notebooks
│   ├── 01_eda.ipynb
│   ├── 02_preprocessing.ipynb
│   ├── 03_modeling.ipynb
│   ├── 04_predict.ipynb
│
├── models
│   └── spotify_model.pkl
│
├── README.md