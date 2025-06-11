# 🎨 K-Means Image Compression

A project that demonstrates how to compress images by reducing the number of unique colors using the **K-Means Clustering** algorithm. This unsupervised machine learning approach groups similar RGB values to minimize image size while retaining perceptual quality.

---

## 📌 Features

- ✅ Color quantization using K-Means clustering  
- 📉 Reduces image file size  
- 🧠 Applies unsupervised learning on pixel data  
- 🖼️ Maintains visual similarity with original image  
- ⚙️ Simple, clean, and configurable Python implementation  

---

## 🧰 Technologies Used

- Python 3.x  
- NumPy  
- scikit-learn  
- Pillow (PIL)  
- Matplotlib  

---

## 🗂️ Project Structure

kmeans-image-compression/
│
├── image.jpg # Input image
├── compressed_image.jpg # Output compressed image
└── README.md # Project documentation

---

## 🚀 How to Run

1. **Clone the repository**
git clone project repository
cd kmeans-image-compression
Install dependencies
pip install -r requirements.txt
Run the script
python main.py

Check the output

compressed_image.jpg will be generated in the project folder.


📊 Results

Significant reduction in image size depending on the value of K.

Minimal perceptual loss for most images with K=16 or higher.

📌 Use Cases
Mobile image optimization

Web asset compression

Efficient image transmission

Educational tool for unsupervised learning

🧠 Concepts Applied
Unsupervised Learning

K-Means Clustering

Image Quantization

RGB Color Space Compression

📄 License
This project is open-source and available under the MIT License.

