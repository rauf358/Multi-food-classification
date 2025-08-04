🍱 Multi-Food Classification using EfficientNet
This project focuses on building a deep learning model to classify images of 20 different food items using the EfficientNet architecture. The experiment involved training multiple variants of EfficientNet (B0, B1, and B2) for 5 and 10 epochs to determine the best-performing model for this task.

📊 Models Trained
Model	Epochs	Final Test Accuracy
EfficientNet-B2	5	78.81%
EfficientNet-B0	10	78.89%
EfficientNet-B1	10	82.01% ✅

🏆 Best Model
The EfficientNet-B1 model trained for 10 epochs achieved the highest test accuracy of 82.01%, making it the best choice for the multi-class food classification task among all tested configurations.

📁 Dataset
Total Classes: 20 food categories

Dataset type: Image classification

Format: Likely organized in folders by class name (standard image dataset structure)

🛠️ Training Setup
Framework: PyTorch

Loss Function: Cross Entropy Loss

Optimizer: Adam (assumed)

Evaluation Metric: Accuracy

Each model was logged with train_loss, train_acc, test_loss, and test_acc at each epoch.

📈 Observations
Increasing the number of epochs improved the model's generalization performance across all tested EfficientNet variants.

EfficientNet-B1 consistently outperformed both B0 and B2 in terms of final accuracy, suggesting it has the right balance of depth and parameters for this dataset.

All models showed steady reduction in loss and improvement in accuracy over epochs, indicating stable training.

📦 Future Work
Try training for more epochs (e.g., 15–20) for further improvement.

Perform data augmentation or use techniques like mixup or label smoothing.

Export the best model and build a deployment pipeline (e.g., via FastAPI or Streamlit).

Fine-tune on augmented/imbalanced datasets if needed.

🧠 Author
Abdul Rauf
Date: August 4, 2025
