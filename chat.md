## F1 score kya batata hai ??
F1 score ek performance metric hai jo binary classification models ke liye use hota hai, jaise ki k-Nearest Neighbors (KNN), 
Logistic Regression, Decision Trees, etc. Ye metric precision (sanchaaransh) aur recall (smaran) ke 
beech ka balance measure karta hai. 

# Precision aur Recall
1. **Precision** : Ye metric batata hai ki model kitne accurately positive predictions 
  (jo ki true positives aur false positives ka sum hota hai) ko classify karta hai.
  Precision ko is formula se calculate kiya jata hai:

-- ***PRECISION = TRUE POSITIVES/ (TRUE POSITIVES + FALSE POSITIVES)***

2. **Recall**: Ye metric batata hai ki model kitne accurately
   positive instances ko identify karta hai, matlab true positives ko
  kitna cover karta hai. Recall ko is formula se calculate kiya jata hai:

-- ***RECALL = TRUE POSITIVES/(TRUE POSITIVES + FALSE NEGATIVES)***

# F1 SCORE
F1 score precision aur recall ke harmonic mean ka measure hai, jo in dono metrics ke beech ka balance indicate karta
hai. F1 score zyada tab hota hai jab precision aur recall dono high hote hain.
F1 score ko is formula se calculate kiya jata hai:

-- ***F1 SCORE= 2X(PRECISION X RECALL)/(PRECISION + RECALL)***

# IMPORTANCE
F1 score ka use primarily un situations mein kiya jata hai jahan aapko precision
aur recall dono ko consider karna hai, especially jab aapke dataset mein class imbalance ho ya fir false 
positives aur false negatives ka impact critical ho.
Is metric ka use model ki overall performance ko evaluate karne mein kiya jata hai,
especially binary classification tasks mein.

Isliye, jab aap apne model ki performance ko evaluate kar rahe hain aur aapko accuracy ke alawa precision
aur recall ka bhi consideration hai, tab F1 score ek valuable metric sabit ho sakta hai.
