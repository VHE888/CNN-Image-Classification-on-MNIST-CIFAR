# CNN Image Classification on MNIST×CIFAR

This project builds a **convolutional neural network (CNN)** to classify MNIST digits embedded within CIFAR-10 image backgrounds. The model achieved **99.3% accuracy** and was developed during the **Oxford University Summer Program**.

---

## Project Overview
- **Goal:** Recognize MNIST digits even when placed on noisy, complex CIFAR-10 backgrounds.  
- **Approach:** Constructed a CNN with convolutional + pooling layers, batch normalization, and dropout to improve generalization.  
- **Outcome:** The model successfully extracted digit features while ignoring background clutter, achieving state-of-the-art performance on the custom dataset.  

---

## Technologies Used
- Python
- TensorFlow / Keras  
- NumPy, Pandas  
- Matplotlib

---

## Dataset
- **MNIST:** Handwritten digits (28×28 grayscale).  
- **CIFAR-10:** Natural images (32×32 color).  
- **Combined Dataset:** MNIST digits were embedded into CIFAR-10 backgrounds, creating a more challenging classification task.

---

## Results
- **Test Accuracy:** 99.3%  
- Robust to background noise and visual clutter.  
- Demonstrated the effectiveness of CNNs in feature separation.
