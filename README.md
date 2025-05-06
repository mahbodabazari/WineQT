# پروژه دسته‌بندی کیفیت شراب (باینری)

## 📌 توضیح کلی

در این پروژه از دیتاست [Wine Quality Dataset](https://www.kaggle.com/datasets/yasserh/wine-quality-dataset) استفاده شده است که شامل ویژگی‌های فیزیکوشیمیایی نمونه‌های شراب قرمز می‌باشد.

هدف پروژه، دسته‌بندی کیفیت شراب به دو دسته‌ی "خوب" و "بد" است. این کار با استفاده از مدل‌های یادگیری ماشین و ابزارهای مرتبط انجام شده است.

---

## ⚙️ جزئیات فنی

- **نوع مسأله**: کلاسه‌بندی باینری
  - امتیازهای کیفیت **6، 7 و 8** → برچسب **خوب (1)**
  - امتیازهای کیفیت **3، 4 و 5** → برچسب **بد (0)**

- **کتابخانه‌های اصلی مورد استفاده**:
  - `Scikit-learn`
  - `imblearn` برای بالانس کردن کلاس‌ها (مانند `SMOTE`)
  - `GridSearchCV` برای جستجوی بهینه پارامترها

- **مدل‌های یادگیری ماشین استفاده شده**:
  - Random Forest
  - XGBoost
  - LightGBM
  - SVM
  - Logistic Regression

- **معیارهای ارزیابی عملکرد**:
  -  (Accuracy)
  -  (Precision)
  -  (Recall)
  -  F1 (F1 Score)

---

## 🎯 نتایج

- بهترین مدل به دقت حدودی **78٪** روی داده‌های تست رسیده است.
- این پروژه شامل تنظیم دقیق هایپرپارامترها و بررسی تأثیر تکنیک‌های مختلف نرمال‌سازی و بالانس داده می‌باشد.

---

## 📎 لینک دیتاست

دیتاست مورد استفاده در این پروژه از Kaggle دریافت شده است:  
🔗 [https://www.kaggle.com/datasets/yasserh/wine-quality-dataset](https://www.kaggle.com/datasets/yasserh/wine-quality-dataset)

---

# Wine Quality Classification Project (Binary)

## 📌 Overview

This project is based on the [Wine Quality Dataset](https://www.kaggle.com/datasets/yasserh/wine-quality-dataset) from Kaggle, which contains physicochemical properties of red wine samples.

The main objective is to classify the wine quality as either **good** or **bad**, using supervised machine learning techniques.

---

## ⚙️ Technical Details

- **Problem Type**: Binary Classification  
  - Quality scores **6, 7, 8** → Labeled as **Good (1)**  
  - Quality scores **3, 4, 5** → Labeled as **Bad (0)**

- **Main Libraries Used**:
  - `Scikit-learn`
  - `imblearn` for class balancing (e.g., `SMOTE`)
  - `GridSearchCV` for hyperparameter tuning

- **Machine Learning Models Trained**:
  - Random Forest
  - XGBoost
  - LightGBM
  - SVM
  - Logistic Regression

- **Evaluation Metrics**:
  - Accuracy
  - Precision
  - Recall
  - F1 Score

---

## 🎯 Results

- The best-performing model achieved an approximate **78% accuracy** on the test set.
- The project includes detailed grid search tuning and the effect of different scalers and samplers.

---

## 📎 Dataset Link

Dataset used in this project is publicly available on Kaggle:  
🔗 [https://www.kaggle.com/datasets/yasserh/wine-quality-dataset](https://www.kaggle.com/datasets/yasserh/wine-quality-dataset)
