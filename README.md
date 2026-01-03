# 🎨 AI Pictionary

An interactive sketch-recognition game using **Hybrid Machine Learning**. It combines pre-trained global knowledge with real-time browser training.

### 🚀 Key Technologies
* **DoodleNet (CNN):** A Convolutional Neural Network trained on 50 million sketches to recognize 345+ categories instantly.
* **Transfer Learning:** Uses **MobileNet** to extract visual features, allowing you to "teach" the AI new shapes without retraining the entire model.
* **TensorFlow.js:** Powers hardware-accelerated math directly in the browser for private, local AI.

![CNN Layers](https://upload.wikimedia.org/wikipedia/commons/6/63/Typical_cnn.png)
*Example of a Convolutional Neural Network Architecture.*

### 🧠 How it Works
1. **Feature Extraction:** The AI converts your drawing into a mathematical "feature vector" representing shapes and edges.
2. **Fine-Tuning:** When you click **Train**, the model maps these features to your custom labels using a new classification layer.

![Transfer Learning Process](https://upload.wikimedia.org/wikipedia/commons/thumb/a/ab/Machine_learning_transfer_learning_diagram.png/600px-Machine_learning_transfer_learning_diagram.png)
*Visualizing the Transfer Learning and Fine-Tuning process.*

3. **Real-Time Inference:** The browser predicts your drawing every time you lift the pen.

### 🎮 How to Use
1. **Sketch:** Draw anything to see the AI's default guess.
2. **Teach:** Enter a label → Draw → **Add Example**.
3. **Evolve:** Add at least 2 different labels and click **Train** to activate your custom AI.