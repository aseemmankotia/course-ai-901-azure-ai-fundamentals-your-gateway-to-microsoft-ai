## Chapter 3: Teaching Machines to Learn: ML Fundamentals — Practice Questions

### Multiple Choice

**Q1.** In a dataset used to predict house prices, which of the following would be considered the "label"?

A) The number of bedrooms
B) The square footage of the house
C) The selling price of the house
D) The year the house was built

<details>
<summary>Answer</summary>

**Correct: C**

The label is what the model is trying to predict—in this case, the selling price. The number of bedrooms (A), square footage (B), and year built (D) are all features (inputs) that help the model make its prediction.

</details>

---

**Q2.** Why do we split data into training and validation datasets?

A) To make the dataset smaller and easier to process
B) To test if the model can perform well on data it hasn't seen before
C) To create backup copies of the data
D) To remove errors from the original dataset

<details>
<summary>Answer</summary>

**Correct: B**

We use validation data to evaluate how well the model generalizes to new, unseen data. This helps detect overfitting, where a model performs well on training data but poorly on new data. Options A, C, and D describe purposes unrelated to the actual goal of data splitting.

</details>

---

**Q3.** A company wants to group customers into segments based on purchasing behavior without any predefined categories. Which type of machine learning should they use?

A) Supervised learning - regression
B) Supervised learning - classification
C) Unsupervised learning - clustering
D) Deep learning - neural networks

<details>
<summary>Answer</summary>

**Correct: C**

Clustering is an unsupervised learning technique that groups similar data points together without predefined labels. Since the company doesn't have predefined categories, they need unsupervised learning. Regression (A) predicts continuous values, classification (B) requires predefined categories, and while neural networks (D) could potentially be used, clustering specifically addresses this grouping need.

</details>

---

**Q4.** Which evaluation metric would be MOST appropriate for a model that predicts whether an email is spam or not spam?

A) Mean Absolute Error (MAE)
B) R-squared (R²)
C) Accuracy or Precision/Recall
D) Root Mean Squared Error (RMSE)

<details>
<summary>Answer</summary>

**Correct: C**

Spam detection is a classification problem (spam vs. not spam), so accuracy, precision, and recall are appropriate metrics. MAE (A), R² (B), and RMSE (D) are all regression metrics used when predicting continuous numerical values, not categories.

</details>

---

**Q5.** What is a key characteristic of the transformer architecture used in modern AI systems?

A) It can only process one word at a time in sequence
B) It uses attention mechanisms to understand relationships between all parts of the input
C) It requires labeled data for every training example
D) It only works with numerical data, not text

<details>
<summary>Answer</summary>

**Correct: B**

Transformers use attention mechanisms that allow the model to consider relationships between all parts of the input simultaneously, rather than processing sequentially. This is what makes them powerful for language tasks. Option A describes older sequential models, C is not specific to transformers, and D is incorrect since transformers excel at processing text.

</details>

---

### True / False

**Q6.** A neural network with multiple hidden layers is called a "deep" neural network, which is where the term "deep learning" comes from. — **True / False**

<details>
<summary>Answer</summary>

**True**

The term "deep learning" refers to neural networks with multiple hidden layers between the input and output layers. The "depth" comes from these stacked layers, which allow the network to learn increasingly complex and abstract representations of the data.

</details>

---

**Q7.** In supervised learning, the model learns from data that has no labels or correct answers provided. — **True / False**

<details>
<summary>Answer</summary>

**False**

Supervised learning specifically requires labeled data—data where the correct answers (labels) are provided during training. The model learns by comparing its predictions to these known correct answers. Learning without labels is called unsupervised learning.

</details>

---

### Short Answer

**Q8.** Explain the difference between regression and classification in supervised learning, and provide one example of each.

<details>
<summary>Answer</summary>

Regression predicts continuous numerical values (e.g., predicting a person's salary based on experience, or forecasting temperature). Classification predicts discrete categories or classes (e.g., determining if an image contains a cat or dog, or diagnosing whether a patient has a disease). The key difference is that regression outputs a number on a continuous scale, while classification assigns data to predefined categories.

</details>

---

**Q9.** What is Azure Machine Learning, and name two capabilities it provides?

<details>
<summary>Answer</summary>

Azure Machine Learning is Microsoft's cloud-based platform for building, training, and deploying machine learning models. Capabilities include: automated machine learning (AutoML) that automatically selects algorithms and tunes models, a visual designer for building ML pipelines without code, model management and versioning, scalable compute resources for training, model deployment as web services, MLOps for managing the ML lifecycle, and integration with popular ML frameworks like TensorFlow and PyTorch.

</details>

---

### Scenario-Based

**Q10.** A retail company has historical sales data including product type, price, day of week, weather conditions, and total units sold. They want to predict how many units of a new product will sell next week. Additionally, they want to discover if there are natural groupings in their customer purchase patterns that they haven't identified yet.

Identify which type of machine learning (and specific technique) should be used for each goal, and explain what would serve as features and labels where applicable.

<details>
<summary>Answer</summary>

**Goal 1 - Predicting units sold:** This requires **supervised learning with regression** because they're predicting a continuous numerical value (number of units). The features would be product type, price, day of week, and weather conditions. The label would be total units sold.

**Goal 2 - Discovering customer groupings:** This requires **unsupervised learning with clustering** because they want to find natural patterns without predefined categories. There are no labels in this case—the algorithm will analyze customer purchase behavior features (purchase frequency, average order value, product categories bought, etc.) to identify similar customer groups.

The company could use Azure Machine Learning to build both models, potentially using AutoML to quickly identify the best regression algorithm and clustering configuration for their data.

</details>