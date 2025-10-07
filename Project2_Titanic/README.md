# 🚢 Titanic Survival Prediction

**Goal:** Predict passenger survival on the Titanic using demographic and travel information.

## Dataset
Source: [Kaggle - Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic/data)  
- 891 passengers  
- 12 features → simplified to 7 key variables  

## Methods
- Logistic Regression  
- Random Forest Classifier  
- Data preprocessing: handled missing values, encoded categorical variables, and scaled numerical data.

## Results
| Model | Accuracy |
|--------|-----------|
| Logistic Regression | ~80% |
| Random Forest | ~83% |

### Feature Importance
Top predictors:
1. Sex (females more likely to survive)  
2. Passenger Class (higher class → higher survival)  
3. Fare (higher fare → more survival likelihood)

## Insights
The model captures simple but human-like decision patterns under uncertainty — similar to cognitive heuristics where limited cues (gender, class, age) drive life-or-death judgments.

## Tech Stack
Python, Pandas, scikit-learn, Seaborn, Matplotlib

**Author:** [Marium Faisal](https://github.com/imarium19)

