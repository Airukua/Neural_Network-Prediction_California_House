### Neural Network on California Housing Dataset  

This notebook demonstrates the implementation of a neural network model on the California Housing dataset. The model is built and trained in Python using PyTorch, with Google Colab as the runtime environment. The notebook includes data preprocessing, model training, and evaluation steps to predict housing prices.  

---

### Requirements  
- Python 3.x  
- Google Colab  
- PyTorch  
- Additional Python libraries: `numpy`, `pandas`, `sklearn`, `tqdm`  

---

### Features  
#### **1. Data Loading**  
- The California Housing dataset is loaded and split into training and testing sets.  

#### **2. Data Normalization**  
- Data normalization is applied to scale input values, ensuring faster convergence during training.  

#### **3. Model Architecture**  
- A neural network model with one or more hidden layers is defined using PyTorch.  
- Activation functions (e.g., ReLU) are used for non-linearity.  

#### **4. Training**  
- The model is trained on the training set by minimizing the loss function (Mean Squared Error).  
- Optimizers such as Adam or SGD are used to adjust weights.  

#### **5. Validation**  
- After each epoch, validation is performed to monitor the model's performance on unseen data.  

#### **6. Denormalization**  
- Predictions and targets are denormalized to calculate errors in the original price scale.  

#### **7. Error Calculation**  
- Mean Absolute Error (MAE) is calculated on the denormalized predictions to evaluate model accuracy.  

---

### Usage  
1. Run all cells in the notebook to load data, train the model, and evaluate its performance.  
2. Monitor the loss values and denormalized errors printed at the end of each epoch.  

---

### Results  
- The notebook provides training and validation loss values per epoch.  
- Final validation loss and Mean Absolute Error (MAE) are displayed after training.  

---

### Acknowledgments  
This notebook uses the California Housing dataset and leverages PyTorch for machine learning model development and training. The addition of a neural network model enables capturing non-linear relationships in the data, enhancing prediction accuracy.  
