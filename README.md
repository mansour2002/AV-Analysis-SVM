# AV-Analysis-SVM
Support Vector Machine (SVM) and Sequential Forward Selection (SFS) for Artery-Vein (AV) Analysis to increase Diabetic Retinopathy (DR) binary and multiclass classifications


To perform one-on-one comparisons of quantitative features between different groups, we utilized the Mann-Whitney U test. In all comparisons, statistical significance was determined with a P-value < 0.05. Subsequently, we conducted pairwise comparisons using the Mann-Whitney U test, denoting significant differences between groups as follows: *, **, and *** for P < 0.05, P < 0.005, and P < 0.0005, respectively. "ns" indicates non-significant differences in pairwise comparisons.
![Fig 2](https://github.com/mansour2002/AV-Analysis-SVM/blob/main/Figures/Fig%202.png)
![Fig 3](https://github.com/mansour2002/AV-Analysis-SVM/blob/main/Figures/Fig%203.png)

 
Our classification model is built around a SVM classifier that utilizes radial basis function (RBF) kernels with hyperparameter values C = 1 and gamma = 'scale'. SVM classifiers were employed for binary and multiclass classification among different groups. In all classification tasks, we implemented sequential forward selection (SFS), a technique rooted in the greedy search algorithm, to identify the optimal subset of features that maximize classification accuracy. 
![AUC](https://github.com/mansour2002/AV-Analysis-SVM/blob/main/Figures/Fig%204.png)


