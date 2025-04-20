# Image Retrieval System using SIFT and TF-IDF

This project implements a **Content-Based Image Retrieval (CBIR)** system using **SIFT feature extraction**, **visual words clustering**, and **TF-IDF weighting**. It allows for retrieving visually similar images based on local image descriptors.

## 🔍 Key Features

- SIFT-based keypoint detection and descriptor extraction
- Visual vocabulary creation using K-Means clustering
- Quantization of image features into visual words
- TF-IDF vector generation for image representation
- Cosine similarity-based image search
- Support for Bag-of-Words (BoW) vs. TF-IDF comparison
- Experimental variations:
  - Different sample sizes for clustering
  - Different numbers of centroids (k)
  - BoW vs. TF-IDF comparison

## 🛠️ Technologies Used

- Python
- OpenCV
- NumPy
- SciPy
- Matplotlib
- scikit-learn

## 🧪 Experiments Included

- **Experiment 1:** Varying the number of sampled descriptors for K-Means
- **Experiment 2:** Varying the number of cluster centroids (visual words)
- **Experiment 3:** Comparison of TF-IDF and Bag-of-Words for image similarity

## 🚀 How to Run

1. Clone the repo and place your dataset in the `images/` folder.
2. Install dependencies:
   ```bash
   pip install opencv-python numpy matplotlib scipy
   ```
3. Run the main script:
   ```bash
   python scripts/main.py
   ```

## 📈 Sample Results
The project visualizes:

 - Detected SIFT keypoints
 - Top K most similar images for a given query
 - Comparison between BoW and TF-IDF results

## 🧠 Project Goals
The project aims to explore and compare classical computer vision techniques for building scalable, unsupervised image retrieval systems. It showcases how traditional descriptors and frequency-based weighting can still achieve high performance in similarity-based tasks.
