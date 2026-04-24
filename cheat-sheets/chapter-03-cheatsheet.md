## Chapter 3: Teaching Machines to Learn: ML Fundamentals — Quick Reference

### Core Concepts
| Concept | One-line explanation |
|---------|---------------------|
| Features | Input variables used to make predictions (e.g., square footage, bedrooms) |
| Labels | The target value you're trying to predict (e.g., house price) |
| Training dataset | Data used to teach the model patterns |
| Validation dataset | Separate data used to test model performance |
| Supervised learning | Learning from labeled examples (knows the "right answers") |
| Unsupervised learning | Finding patterns in unlabeled data (no "right answers") |
| Regression | Predicts continuous numbers (price, temperature, age) |
| Classification | Predicts categories (spam/not spam, cat/dog) |
| Clustering | Groups similar items together without predefined labels |
| Neural networks | Layered algorithms mimicking brain structure for complex patterns |
| Transformers | Architecture using "attention" to process sequences (powers GPT, BERT) |

### Key Syntax / Commands
```
Azure ML Studio Workflow:
1. Create Workspace → 2. Upload Data → 3. Create Pipeline
4. Train Model → 5. Evaluate → 6. Deploy Endpoint
```

### Common Patterns
**Pattern 1: Choose Your Algorithm**
Have labels? → Supervised (Predict numbers = Regression, Predict categories = Classification)
No labels? → Unsupervised (Clustering)

**Pattern 2: Model Evaluation**
Regression → Use RMSE, MAE, R² | Classification → Use Accuracy, Precision, Recall, F1

### Things to Remember
✅ Always split data into training (70-80%) and validation (20-30%) sets
✅ More quality data generally improves model performance
✅ Azure Machine Learning provides no-code designer AND code-first options
❌ Don't test your model on the same data you trained it with (overfitting!)

### Quick Quiz
1. Predicting customer churn (yes/no)? → **Classification**
2. Grouping customers by behavior without categories? → **Clustering**
3. Predicting next month's sales revenue? → **Regression**