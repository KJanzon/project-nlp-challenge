
## Predict Fake News 
Project to predict fake vs real news from a data set of news headlines, attached in dataset folder. We trained the model on data.cvs, then predicted real or fake on validation_data.csv.

The most succesful model was Logistic Regression, with 'bag of words' word representation. 
	precision	recall	f1-score	support
0	0.9514131470308034	0.9266934735539747	0.9388906298965841	3233.0
1	0.9280291527482539	0.9523215955126207	0.9400184558597354	3209.0
accuracy	0.9394597950946911	0.9394597950946911	0.9394597950946911	0.9394597950946911
macro avg	0.9397211498895286	0.9395075345332977	0.9394545428781598	6442.0
weighted avg	0.9397647090220016	0.9394597950946911	0.9394524419915473	6442.0<img width="501" alt="image" src="https://github.com/user-attachments/assets/be4c4122-8014-41fa-bfd0-a73e9e13b605" />


Final result:
Accuracy: 94.74% – The model correctly classified news articles in 94.74% of cases.
F1-Score (Balance of Precision & Recall):
Fake news: 94.86%
Real news: 94.62%

Several data cleaning techniques were tried, but fake news could be predicted better when not cleaning the data. Presumable fake news has more poor formatting in it, such as several exclamation marks.
![unnamed (1)](https://github.com/user-attachments/assets/ecbe4242-cb56-4e14-81e7-010bc2588875)

Certain words proved to be important predictors of fake vs real news. These words were the strongest predictors for each class:
![wordcloudpredictivepower](https://github.com/user-attachments/assets/891c50dd-ba0e-4a59-a989-10c4ce39078e)


## Deliverables

1. **Python Code:** main.ipynb
2. **Predictions:** testing_data_predicted.csv
3. **Accuracy estimation:** 90%
4. **Presentation:**  [View the Google Slides Presentation](https://docs.google.com/presentation/d/13W-eWr5aP89gYyhkcUjtjAsIArgH6lVvheE-Qa5pR1Q/edit#slide=id.p3)

