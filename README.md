# kaggle-titanic

Summary of Changes Made to the Data (listed for the purpose of supporting my own learning)

1. Missing values were inspected using **`train_df.info()`**.
2. Data was reviewed using **`train_df.describe()`**.
3. The impact of the **`Pclass`** feature on survival was examined.
4. The effect of the **`Sex`** feature on survival was analyzed.
5. The influence of the **`SibSp`** feature on survival was investigated.
6. The impact of the **`Parch`** feature on survival was investigated.
7. The **`Age`** feature was visualized to understand its effect on survival.
8. The effects of **`Embarked`**, **`Pclass`**, and **`Pclass`** features on survival were examined.
9. **`Ticket`** and **`Cabin`** were dropped from the dataset.
10. Titles from names were extracted, and their effect on survival was analyzed.
11. Rare titles in names were grouped under common titles and numbered.
12. Gender was converted into numerical type.
13. Missing values in the **`Age`** variable were estimated based on **`Sex`** and **`PClass`** variables.
14. The **`Age`** feature was grouped into 5 categories.
15. The impact of family size feature, which combines **`Parch`** and **`SibSp`**, on survival was examined.
16. The family size feature was removed, and a new feature **`IsAlone`** was added.
17. A new feature was added by multiplying **`Age`** and **`PClass`** features.
18. Finally, the data was prepared for experimentation with models.
