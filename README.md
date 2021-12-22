# Stock-Price-Prediction-using-LSTM
The repo has been created for a basic stock price predictor model designed using LSTM. 
The model was created as a project for the course ELEC 825 - Machine Learning and Deep Learning offered in Fall 2021 at Queen's University.
<br /><br />
Multiple python notebooks with appropriate titles have been uploaded. These notebooks show not only the final code but also various hyperparameter tuning that has been carried out. <br /><br />
Following description guides this repo: <br /><br />
a) File 1 hosts the base code for stock price prediction used in the project and is accurately predicting Tesla Stock Price. <br /><br />
Upcoming files are used for hyperparameter tuning. <br /><br />
b) Removing Dropout Layers:<br />
File 2 tests the model without dropout layers. In our case, this actually helps in predicting data more accurately and code does not smoothen the final result. <br /><br />
c) Varying the number of epochs <br />
Files 3,4,5 play around with epochs. As can be seen having proper number of epochs is necessary for the code so that it does not overfit/underfit. With high number of epochs, the data seemed to be underfitting while for smaller number of epochs, it seemed to be overfitting. <br /><br />
d) Varying the size of dataset <br />
Increasing the size of dataset increases the time of training, while decreasing the size of dataset decreases the time of training. In our case, decreasing the size of dataset corresponded to an underfit data, while increasing the size of dataset made for a well-fit data for the most part. Files 6 and 7 help describe this part.
<br /><br />
e) Varying the number of layers <br /> 
Tuning the number of layers is another hyperparameter variation. From my anaylsis, it is clear that increasing the number of layers does not mean that data will fit well. With two extra layers in File 8, data was overfitting at some points and underfitting at others, while with one extra layer in File 9 similar trend was seen. Increasing the number of layers increases the training time.
