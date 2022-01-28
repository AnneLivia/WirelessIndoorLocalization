# Wireless Indoor Localization

### In this project, it was trained different Machine Learning models to identify a room based on the Wireless Indoor Signal strengths. The models used were: Decision Tree, AdaBoost, Random Forest, Extra Tree, XGBoost, SVM, KNN, and a Multi-layer Perceptron classifier.
  
### Models implemented by <a href="https://github.com/AnneLivia">Anne Livia</a>.

## Dataset Information:

This data set has **2000 rows and 8 columns**, and contains data collected in indoor place by observing signal strengths of seven WiFi signals visible on a smartphone. **The data is used to predict the location in one of the four rooms**. **It was collected to perform experimentation on how wifi signal strengths can be used to determine one of the indoor locations.** 

### Data Dictionary 

**Each attribute is wifi signal strength observed on smartphone.**



                    | Column  | Atrribute   | Definition     	     | Data Type    	| % Null Ratios |
                    |---------|-------------|-----------------------------------------------|-------------- |
                    | 1       | Wifi 1      | Signal strength of wifi 1  | Quantitative 	| 0             |
                    | 2       | Wifi 2      | Signal strength of wifi 2  | Quantitative 	| 0             |
                    | 3       | Wifi 3      | Signal strength of wifi 3  | Quantitative 	| 0             |
                    | 4       | Wifi 4      | Signal strength of wifi 4  | Quantitative 	| 0             |
                    | 5       | Wifi 5      | Signal strength of wifi 5  | Quantitative 	| 0             |
                    | 6       | Wifi 6      | Signal strength of wifi 6  | Quantitative 	| 0             |
                    | 7       | Wifi 7      | Signal strength of wifi 7  | Quantitative 	| 0             |
                    | 8       | Room        | Rooms (1, 2, 3, 4) 	     | Quantitative     | 0             |

---

### Acknowledgement

This data set has been sourced from the Machine Learning Repository of University of California, Irvine [Wireless Indoor Localization Data Set (UC Irvine)](https://archive.ics.uci.edu/ml/datasets/Wireless+Indoor+Localization). 
The UCI page mentions the following 2 publications as the original source of the data set:

*1. Rajen Bhatt, 'Fuzzy-Rough Approaches for Pattern Classification: Hybrid measures, Mathematical analysis, Feature selection algorithms, Decision tree algorithms, Neural learning, and Applications', Amazon Books*<br/> 
*2. Jayant G Rohra, Boominathan Perumal, Swathi Jamjala Narayanan, Priya Thakur, and Rajen B Bhatt, 'User Localization in an Indoor Environment Using Fuzzy Hybrid of Particle Swarm Optimization & Gravitational Search Algorithm with Neural Networks', in Proceedings of Sixth International Conference on Soft Computing for Problem Solving,2017, pp. 286-295.*


# Software Information

  - Python
  - Pandas
  - Scikit-learn
  - Matplotlib
  - Seaborn
  - XGBoost

# Trained Models 

  - <h3>Decision Tree Model</h3>

                      precision    recall  f1-score   support

          0               1.00      0.97      0.99       104
          1               0.97      0.94      0.95        93
          2               0.91      0.96      0.93       101
          3               0.99      0.99      0.99       102

          accuracy                            0.96       400
          macro avg       0.97      0.96      0.96       400
          weighted avg    0.97      0.96      0.97       400

  - <h3>AdaBoost Model</h3>

                     precision    recall  f1-score   support

          0               1.00      1.00      1.00       104
          1               0.82      0.96      0.89        93
          2               0.95      0.80      0.87       101
          3               0.99      1.00      1.00       102

          accuracy                            0.94       400
          macro avg       0.94      0.94      0.94       400
          weighted avg    0.94      0.94      0.94       400
   
  - <h3>Random Forest Model</h3>
    
                      precision    recall  f1-score   support

          0               0.99      1.00      1.00       104
          1               1.00      0.92      0.96        93
          2               0.93      0.98      0.96       101
          3               0.99      1.00      1.00       102

          accuracy                            0.98       400
          macro avg       0.98      0.98      0.98       400
          weighted avg    0.98      0.98      0.98       400

  - <h3>Extra Tree Model</h3>

                      precision    recall  f1-score   support

          0               1.00      0.99      1.00       104
          1               1.00      0.92      0.96        93
          2               0.93      0.99      0.96       101
          3               0.98      1.00      0.99       102

          accuracy                            0.98       400
          macro avg       0.98      0.98      0.98       400
          weighted avg    0.98      0.98      0.98       400
  
  - <h3>XGBoost model</h3>

                      precision    recall  f1-score   support

          0               0.99      0.99      0.99       104
          1               0.98      0.97      0.97        93
          2               0.95      0.96      0.96       101
          3               0.99      0.99      0.99       102

          accuracy                            0.98       400
          macro avg       0.98      0.98      0.98       400
          weighted avg    0.98      0.98      0.98       400
      
  - <h3>KNN</h3>

                      precision    recall  f1-score   support

          0               0.99      0.99      0.99       104
          1               0.99      0.96      0.97        93
          2               0.95      0.97      0.96       101
          3               0.99      1.00      1.00       102

          accuracy                            0.98       400
          macro avg       0.98      0.98      0.98       400
        weighted avg      0.98      0.98      0.98       400

- <h3>SVM</h3>

                      precision    recall  f1-score   support

          0               0.99      0.98      0.99       104
          1               0.99      0.94      0.96        93
          2               0.93      0.97      0.95       101
          3               0.98      1.00      0.99       102

          accuracy                            0.97       400
          macro avg       0.97      0.97      0.97       400
          weighted avg    0.97      0.97      0.97       400

- <h3>Multi-layer Perceptron classifier</h3>

                     precision    recall  f1-score   support

          0               0.99      0.97      0.98       104
          1               0.97      0.96      0.96        93
          2               0.92      0.93      0.93       101
          3               0.96      0.98      0.97       102

          accuracy                            0.96       400
          macro avg       0.96      0.96      0.96       400
          weighted avg    0.96      0.96      0.96       400