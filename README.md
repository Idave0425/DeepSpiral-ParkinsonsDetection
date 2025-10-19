# DeepSpiral: Parkinson’s Disease Detection from Spiral Drawings

## Overview

**DeepSpiral** is a deep learning project that detects Parkinson’s disease from patient spiral drawings. Leveraging the power of MobileNetV2 and ResNet50 architectures, DeepSpiral analyzes handwriting samples and achieves high-accuracy predictions, showcasing the potential of artificial intelligence in early neurological diagnosis.

- **Model Architectures:** MobileNetV2, ResNet50
- **Dataset:** Curated collection of patient spiral handwriting samples
- **Accuracy:** Achieved 91% on detection tasks

---

## Features

- 📈 **State-of-the-art Models:** Utilizes MobileNetV2 and ResNet50 for image classification
- 🖊 **Handwriting Analysis:** Focused on spiral drawing patterns, a key marker in Parkinson’s diagnosis
- 🏥 **Clinical Relevance:** Demonstrates AI’s role in assisting early detection of neurological diseases

---

## Getting Started

### Prerequisites

- Python 3.7+
- Jupyter Notebook
- TensorFlow, Keras, NumPy, Matplotlib

Install dependencies:
```bash
pip install tensorflow keras numpy matplotlib
```

### Usage

1. **Clone the repository:**
    ```bash
    git clone https://github.com/Idave0425/DeepSpiral-ParkinsonsDetection.git
    cd DeepSpiral-ParkinsonsDetection
    ```

2. **Open the Jupyter notebooks:**
    - `MobileNetV2_Analysis.ipynb`
    - `ResNet50_Analysis.ipynb`

3. **Run the cells to train or evaluate models on your dataset.**

---

## Project Structure

- `Automated_Detection_of_Parkinsons_Disease_Patterns_in_Spiral_Drawings_Using_Convolutional_Neural_Networks.pdf` — full research paper
- `create_images.ipynb` — generate spiral images from coordinate data

- `MobileNetV2 - Training.py` — train/evaluate MobileNetV2
- `Training-Resnet50.py` — train/evaluate ResNet50
- `Best_Model_Training_and_Saving.py` — save best model + post-training eval

- `Create_Test_Image_Folders.py` — create test image directory structure
- `Create_Validation_Image_Folders.py` — create validation image directory structure

- `Multiline-plots.py` — plots/metrics for MobileNetV2
- `Multiline-plots - Resnet50.py` — plots/metrics for ResNet50

- `Test-Images-For-Binary-Classification (MobileNetV2)/` — sample outputs (MobileNetV2)
- `Test-Images-For-Binary-Classification (ResNet50)/` — sample outputs (ResNet50)

- `LICENSE` — license
- `README.md` — this file

---

## Results

- **MobileNetV2:** 91% accuracy on test samples
- **ResNet50:** Comparable performance, with robust feature extraction

Visualization example:

![Spiral Drawing Example](path/to/sample_image.png)

---

## Citation

If you use DeepSpiral in your research, please cite:

```
@misc{deepspiral2025,
  author = {Idave0425},
  title = {DeepSpiral: Parkinson’s Disease Detection from Spiral Drawings},
  year = {2025},
  url = {https://github.com/Idave0425/DeepSpiral-ParkinsonsDetection}
}
```

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Contact

- **Author:** [Idave0425](https://github.com/Idave0425)

---

## Contributing

Contributions, suggestions, and feedback are welcome! Please open an issue or submit a pull request.
