# **Melodate Clustering Model**

This project implements a clustering model for the Melodate dating app, designed to group users based on their music preferences. The model uses TensorFlow and applies one-hot vectorization for processing.

---

## **Project Overview**
- **Goal**: Cluster users based on music preferences to match them with others sharing similar tastes.
- **Input**: User data from `merged_dataset.csv`.
- **Output**: Clustered data stored in `clustered_data.csv`.

---

## **Project Team**
Alvin Hartono – Universitas Bunda Mulia
Bryan Nathaniel – Universitas Bunda Mulia
Dedy Faradzi – Universitas Pamulang
Lukas Krisna Prastiyan – Sekolah Tinggi Ilmu Komputer Yos Sudarso
Medica Normalika Zakiah – Universitas Pembangunan Nasional Veteran Jawa Timur
Mia – Universitas Bunda Mulia
Vincent Pangdipta – Universitas Bunda Mulia

---

## **Key Steps**

### 1. **Data Preparation**
- Load `merged_dataset.csv` containing user details and music preferences.
- Transform categorical data (e.g., artists, genres, favorite songs) using one-hot encoding.

### 2. **Clustering Model**
- Use the **KMeans algorithm** to cluster users into distinct groups.
- Each user is assigned a **Cluster ID** based on their music preferences.

### 3. **TensorFlow Integration**
- Convert processed data into TensorFlow tensors for model compatibility.

### 4. **Output**
- Save the clustered results to `clustered_dataset.csv` for app integration.

---

## **File Structure**
- **Input**:  
  - `merged_dataset.csv`: Dataset containing user profiles and music preferences.
- **Output**:  
  - `clustered_dataset.csv`: Dataset with added `Cluster ID` for each user.

---

## **Requirements**
- Python 3.7+
- Libraries:
  - `pandas`
  - `scikit-learn`
  - `tensorflow`

---

## **How to Run**

1. **Install Dependencies**:
   ```bash
   pip install pandas scikit-learn tensorflow
   ```

2. **Run the Model**:
   Execute the clustering script:
   ```bash
   python clustering_model.py
   ```

3. **View Results**:
   Check `clustered_dataset.csv` for user clusters.

---

## **Next Steps**
- **Integration**: Use `Cluster ID` in the app backend to match users with similar preferences.
- **Optimization**: Experiment with different `n_clusters` values to improve results.

---

**Author**: Mia - ML-70 (egpelliarmus)
**Date**: November 25, 2024  
