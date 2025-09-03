# Regression Transformations for Boston Housing Dataset

I completed this project as part of the **IBM Machine Learning Specialization**.  
In this project, I applied **logarithmic, square root, and other transformations** to the **target variable** to make it more normally distributed for **Regression** tasks.  
I used the **Boston Housing Dataset** and visualized the data distribution before and after transformations to evaluate the impact.

---

## Project Overview
In regression modeling, if the **target variable** (dependent variable) is **skewed** or **non-normally distributed**,  
it can negatively affect the model’s performance.  
To solve this, I learned to apply **mathematical transformations** on the **target variable** to approximate a normal distribution,  
and then applied **inverse transformations** to interpret results back in their original scale.

Key highlights of the project:
- Understand why **normality** of the target variable matters in regression.
- Apply transformations like:
    - Logarithmic
    - Square root
    - Exponential
- Implement **inverse transformations** for model interpretability.
- Visualize and compare target variable distributions before and after transformations.

---

## Learning Objectives
By the end of this project, I was able to:
- Apply transformations to make the **target variable** more normally distributed.
- Use **inverse transformations** to interpret regression predictions back to their original scale.
- Visualize transformed vs. non-transformed distributions using **Matplotlib**.
- Prepare datasets for better regression performance.

---

## Dataset Information
I used the **Boston Housing Dataset**, which includes information on housing prices in Boston suburbs.

### **Features (Inputs)**
- Crime rate  
- Average number of rooms per dwelling  
- Distance to employment centers  
- Accessibility to highways  
- Property tax rate  
- Pupil-teacher ratio  
- And several other housing-related attributes

### **Target (Output)**
- **Median value of owner-occupied homes** (in $1000s)

---

## Installation
Clone this repository and install the required dependencies:

```bash
git clone https://github.com/your-username/regression-transformations-boston-housing.git
cd regression-transformations-boston-housing
pip install -r requirements.txt
