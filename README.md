# Sampling-on-CreditCard-dataset
Performed 5 sampling techniques on 5 different models.

# Sampling Techniques Used-
1. Simple random sampling
2. Systematic sampling
3. Stratified sampling
4. Cross-validation sampling
5. Bootstrap sampling

# Models Used-
1. M1: RandomForestClassifier
2. M2: LogisticRegression
3. M3: SVC
4. M4: DecisionTreeClassifier
5. M5: GaussianNB

# Results
| Models | Bootstrap | Cross_Validation | Simple_Random | Stratified | Systematic |
|----------|----------|----------|----------|----------|----------|
| M1    | 0.967741935483871   | 1   |  1   | 1   | 0.903225806451612   |
| M2    | 0.838709677419354   | 0.897540983606557   |  0.935483870967741   |  0.903225806451612   | 0.870967741935483   |
| M3    | 0.935483870967741   | 0.967213114754098   |  0.935483870967741   |  1  | 0.838709677419354   |
| M4   |  1   | 1  | 0.967741935483871   |  1   | 0.935483870967741  |
| M5   | 0.774193548387096  | 0.823770491803278  |  0.774193548387096  |  0.709677419354838  | 0.806451612903225   |
