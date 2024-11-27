


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


Regression Models
              Model	    R² (Train)	R² (Test)	RMSE (Train)	RMSE (Test)
  Linear Regression    	0.8290	    0.8292	  9.0358	    9.0564
  Polynomial Regression	0.8428    	0.8421  	8.6646	    8.7082
  Decision Tree	0.8699	0.8565	    7.8841	  8.3014
Classification Models
                Model	Precision	Recall	F1 Score
  Logistic Regression	0.79	0.64	0.70
  SVM                	0.81	0.69	0.74
  Decision Tree	      0.84	0.71	0.77
Ensemble Methods
      Method	        Precision	Recall	F1 Score
  Random Forest	      0.86	    0.69	  0.76
  Gradient Boosting	  0.86	    0.70  	0.77


Programming Language: Python
Libraries:
    Machine Learning: scikit-learn
    Data Processing: pandas, numpy
    Optimization: scikit-optimize
    Visualization: matplotlib, seaborn
