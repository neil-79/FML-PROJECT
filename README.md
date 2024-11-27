


🔍 Key Findings
Through our analysis, we observed that certain features consistently play a significant role in determining a song's popularity across all eras:

Loudness: Songs with higher loudness levels are more likely to attract attention and achieve popularity.
Genre: The genre of a song remains a crucial determinant, influencing its reach and audience preference.
Duration: The length of a song has a notable impact, as optimal duration varies based on trends over time.
Harmonic Simplicity: Simpler harmonic structures often resonate better with listeners, enhancing a song's appeal.
Additionally, all acoustic features analyzed (e.g., energy, danceability, and valence) were found to be important contributors to song popularity, highlighting the intricate relationship between musical elements and listener engagement.

These insights provide valuable guidance for music producers and industry professionals aiming to craft successful tracks.


    Dataset: Features over 175,000 western songs from 1921–2020, and 45000 Hindi songs sourced from the Spotify Web API and Kaggle.
    Algorithms: Includes regression, classification, and ensemble methods (e.g., Decision Trees, Random Forests, Boosting).
    Outcome: Decision Tree-based algorithms performed competitively, with ensemble methods showing slight improvements in recall and F1 scores.
    Best model: XGBoost gave the best accuracy with competetive recall and F1 scores


Data Preprocessing:
    Removed irrelevant features like id and duration.
    Applied One-Hot Encoding for categorical variables.
    Merged and aggregated data across tracks, artists, and years.
Machine Learning Approaches:
    Regression: Linear, Polynomial, Lasso, and Decision Tree.
    Classification: SVM, Perceptron, and Decision Tree.
    Ensemble Learning: Random Forest, AdaBoost, Gradient Boosting, and Voting Classifiers.
Metrics:
    R², RMSE, Accuracy, Precision, Recall, and F1 Score.
    Bayesian Optimization:
    Tuned hyperparameters efficiently for boosting algorithms.




Programming Language: Python
Libraries:
    Machine Learning: scikit-learn
    Data Processing: pandas, numpy
    Optimization: scikit-optimize
    Visualization: matplotlib, seaborn
