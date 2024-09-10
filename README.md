# 心臟病預測器

## 概述
心臟病預測器專案目的是預測患者是否存在心臟病

## 使用模型
1. **決策樹 (Decision Tree)**
2. **隨機森林 (Random Forest)**
3. **XGBoost**
4. **LightGBM**
5. **CatBoost**
6. **梯度提升 (Gradient Boosting)**
7. **堆疊分類器 (Stacking Classifier)**

## 評估標準
本次比賽用於評估的衡量標準是準確度分數。
$\text{Accuracy} = \frac{TP + TN}{TP + FP + TN + FN}$

## 提交分數
最後使用最佳模型(XGBoost)提交至Kaggle，提交分數為 **0.92016**