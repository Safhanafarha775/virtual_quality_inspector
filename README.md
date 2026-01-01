# 🏭 Virtual Quality Inspector - AI-Powered Defect Detection

A computer vision system simulating manufacturing quality control using OpenCV and Python. Detects defects, analyzes sharpness, and provides pass/fail decisions without physical hardware.

## 🚀 Live Demo
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1qN9bs29Ht7C7gkJw4bhOw4sdlPCWvJqk?usp=drive_link)

## 📸 Sample Results
| Good Sample | Defective Sample |
|-------------|------------------|
| ![Good Sample](Scattered Desk Essentials_simple_compose.png) | ![Defective Sample](samples/sample_defective.jpg) |
*Output: "PASS - No defects detected"* | *Output: "REJECT - Multiple defects found"*

## 🛠️ How It Works
1.  **Image Preprocessing**: Converts to grayscale and applies filters.
2.  **Defect Detection**: Uses the Canny Edge algorithm and contour analysis to identify anomalies.
3.  **Decision Logic**: Classifies the product based on the count and size of detected defects.

## 🧠 Skills Demonstrated
- **Python & OpenCV** for image processing
- **Algorithm Implementation** (Edge Detection, Contour Analysis)
- **Problem-Solving** in a simulated manufacturing context
- **Analytical Reporting** with visual and quantitative outputs

## ✨ Features
- **Defect Detection**: Identifies scratches, dents, anomalies via edge analysis
- **Quality Metrics**: Measures sharpness, brightness, dimensions
- **Visual Reports**: Side-by-side comparison with defect highlighting
- **Automated Decision**: PASS/FAIL based on configurable thresholds


## 🎯 How to Use
1. Click "Open in Colab" above
2. Upload any product image
3. Run all cells
4. View defect analysis and quality report

## 📊 Sample Output
![Defect Detection Sample](samples/Scattered Desk Essentials_simple_compose.png)

## 🔮 Future Enhancements
- Deep learning-based defect classification
- Real-time video inspection
- Integration with robotic inspection systems

