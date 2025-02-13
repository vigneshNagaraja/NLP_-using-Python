# NLP_-using-Python

TF-IDF It helps capture the importance of words while reducing the impact of common words.
Logistic Regression: Simple, efficient for text classification.
Naïve Bayes: Works well for spam detection due to its probabilistic nature.
Random Forest: Captures complex relationships for better accuracy.
Precision is high but Recall is low → Model avoids false positives but misses actual spam.
If Recall is high but Precision is low → Model catches most spam but wrongly flags many ham messages.
F1-score finds a balance → Ensures the model is both accurate and useful.
                   Accuracy	      Precision (Spam)	        Recall (Spam)	         F1-Score (Spam)
Logistic Regression	 94.26%  	       95%	                        61%	                      74%
Naïve Bayes       	 96.59%	         100%	                        75% 	                    85%
Random Forest	       97.93%	         99%	                         85%	                     92%


Random Forest is the best choice as it balances both high precision and recall.
Naïve Bayes is also good (high precision, but lower recall).
Logistic Regression performs the worst due to its low recall (many spam messages are missed)
