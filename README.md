# master_thesis

The file called <b>untitled</b> is a test on the dataset of 480 patient previously used.<br>
I used the same features selected in the original work and I tried different approaches for feature selection and classification, with also some feature engineering.

In the file called <b>classification (diff number if features)</b> I tried to train the alghoritm on the same dataset by selecting different number of features with mRMR, obtaining an improvement of AUC, ACC and F1 with XGBoost (10 features).<br>

In the file called <b>survival analysis</b> I applied survival analysis to the old dataset, doing the same preprocessing and using RSF, CPH and GradientBoosting. The results are evaluated with c-index .<br>
