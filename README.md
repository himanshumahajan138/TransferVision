# TransferVision 🌟

**Empowering Scene Classification with Advanced Transfer Learning**

---

## Overview 🔬
TransferVision is a robust deep learning project designed to classify images across six distinct scene categories with remarkable precision. Leveraging pre-trained models and cutting-edge transfer learning techniques, this project demonstrates the potential of AI when applied to relatively small datasets, achieving state-of-the-art results through fine-tuning and optimization.

---

## Features 🌐
- **Advanced Transfer Learning**: Utilizes pre-trained models (ResNet50, ResNet100, EfficientNetB0, VGG16) to extract meaningful image features.
- **Comprehensive Image Augmentation**: Empirical regularization techniques including rotation, zoom, flip, contrast, and translation to enhance generalization.
- **High-Performance Metrics**: Achieved **95%+ accuracy** with **Precision: 96%, Recall: 94%, AUC: 98%, and F1 Score: 95%**.
- **Optimized Training Process**: Implemented techniques such as early stopping, batch normalization, dropout, and ADAM optimizer for robust performance.

---

## Tech Stack 🤖
- **Programming Language**: Python
- **Deep Learning Framework**: Keras, TensorFlow
- **Pre-trained Models**: ResNet50, ResNet100, EfficientNetB0, VGG16
- **Tools**: OpenCV (for image processing and augmentation)

---

## Installation 🔧

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/himanshumahajan138/TransferVision.git
   cd transfervision
   ```

2. **Set Up the Environment**:
   - Create a virtual environment and activate it:
     ```bash
     python3 -m venv env
     source env/bin/activate
     ```
   - Install the required dependencies:
     ```bash
     pip install -r requirements.txt
     ```

3. **Prepare the Dataset**:
   - Place the training and testing images in their respective folders (organized by class).
   - Ensure images are preprocessed (resized or zero-padded).

---

## Usage 🔄

1. **Run the Training Script**:
   ```bash
   python train.py
   ```
   - Automatically performs data augmentation and trains models with early stopping.
   
2. **Evaluate the Model**:
   ```bash
   python evaluate.py
   ```
   - Reports metrics: **Precision, Recall, AUC, and F1 Score**.

3. **Make Predictions**:
   ```bash
   python predict.py --image path/to/image.jpg
   ```

---

## Results 🔹
- **Training and Validation Loss**: Consistently reduced over 50-100 epochs.
- **Metrics**: Precision, Recall, AUC, and F1 Score metrics highlight the reliability and accuracy of the models.

---

## Key Learnings 🎓
- **Transfer Learning Efficiency**: Demonstrated how pre-trained models excel with small datasets.
- **Data Augmentation Impact**: Showcased the value of image augmentation in enhancing generalization.

---

## Contributing 🙌
We welcome contributions! If you have ideas or improvements, please open an issue or submit a pull request.

---

## License 🔒
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Contact 📧
For questions or collaborations, feel free to reach out:
- **Email**: himanshumahajan138@gmail.com
- **LinkedIn**: [Himanshu Mahajan](https://linkedin.com/in/himanshu138)

---

**"Fine-Tuning Excellence with TransferVision" 🚀**

