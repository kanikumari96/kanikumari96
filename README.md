■■ Bharat-Intern-Taks

@Task 1

Problem statement:

TO PREDICT THE STOCK PRICE OF ANY COMPANY USING LSTM.

? ABOUT DATASET:

This dataset contains historical data of Google's stock prices and related attributes. It consists of 14 columns and a smaller subset of 1257 rows. Each column represents a specific attribute, and each row contains the corresponding values for that attribute.

The columns in the dataset are as follows:

Symbol: The name of the company, which is

GOOG in this case. Date: The year and date of the stock data.

Close: The closing price of Google's stock on

a particular day.

High: The highest value reached by Google's stock on the given day.

Low: The lowest value reached by Google's

stock on the given day.

Open: The opening value of Google's stock on the given day.

Volume: The trading volume of Google's

stock on the given day, i.e., the number of

shares traded.

adjClose: The adjusted closing price of Google's stock, considering factors such as dividends and stock splits.

adjHigh: The adjusted highest value reached by Google's stock on the given day.

adjLow: The adjusted lowest value reached by Google's stock on the given day. adjOpen: The adjusted opening value of

Google's stock on the given day. adjVolume: The adjusted trading volume of Google's stock on the given day, accounting

for factors such as stock splits.

divCash: The amount of cash dividend paid out to shareholders on the given day.
adjLow: The adjusted lowest value reached by Google's stock on the given day. adjOpen: The adjusted opening value of Google's stock on the given day. adjVolume: The adjusted trading volume of Google's stock on the given day, accounting for factors such as stock splits. divCash: The amount of cash dividend paid out to shareholders on the given day. splitFactor: The split factor, if any, applied to Google's stock on the given day. A split factor of 1 indicates no split.


■■  Task 2

Problem statement:

Titanic Classification: Algorithm which tells whether the person will be save from sinking or not

? About Dataset :

Titanic is one of the most infamous shipwrecks in history. On April 15, 1912, during her maiden voyage, the Titanic sank after colliding with an iceberg, killing 1502 out of 2224 passengers and crew. This sensational tragedy shocked the international community and led to better safety regulations for ships.

While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.

In this challenge, we have to a predictive model that answers the question: "what sorts of people were more likely to survive?"
In this challenge, we have to a predictive model that answers the question: "what sorts of people were more likely to survive?" using passenger data (ie name, age, gender, socio-economic class, etc).

Passengerld: Passenger Identity Survived: Whether passenger survived or not (0 = No, 1 = Yes) Pclass: Class of ticket, a proxy for socio-economic status (SES) (1 = 1st, 2 = 2nd, 3 = 3rd) Name: Name of passenger Sex: Sex of passenger Age: Age of passenger in years SibSp: Number of sibling and/or spouse travelling with passenger Parch: Number of parent and/or children travelling with passenger Ticket: Ticket number Fare: Price of ticket Cabin: Cabin number Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).


■■■ Handwritten-Digit- Recognition-using- MNIST-Dataset- Task-3

Number Recognition!
Key Features:

1. Data Preprocessing: The MNIST dataset is loaded and preprocessed. Images are scaled to have pixel values ranging from 0 to 1.

2. Model Architecture: Two models are constructed. The first is a simple model with a single output layer of 10 neurons using the sigmoid activation function. The second includes an additional hidden layer of 100 neurons with ReLU activation before the output layer.

3. Model Compilation: Both models are compiled using the 'adam' optimizer and the 'sparse_categorical_crossentropy' loss function for multiclass classification. Accuracy is chosen as the evaluation metric.

4. Training: The models are trained on the flattened training data using the fit method. The number of training epochs is set to 5.

5. Evaluation: The models' accuracy is evaluated using the flattened test data.

6. Confusion Matrix: The confusion matrix is computed and visualized using seaborn. It shows how well the model predicted each class.

7. Sample Predictions: Randomly selected test images are displayed alongside their true labels and predicted labels for the model with a hidden layer.

Key Insights and Analysis:

1. Hidden Layer Benefit: The model with a hidden layer (ReLU activation) tends to perform better than the simple model with only an output layer (sigmoid activation). Adding a hidden layer allows the model to learn more complex features and patterns, resulting in improved accuracy.

2. Confusion Matrix: The confusion matrix provides insights into how well the model performs for each class. It helps identify whether the model struggles with particular digits and the degree of confusion between different digits.

3. Sample Predictions: The displayed sample images, along with their true labels and predicted labels, give a visual understanding of the model's performance. It allows you to see instances where the model succeeded or failed in making accurate predictions.

4. Data Visualization: The code includes visualization components that enable a better understanding of the dataset, model performance, and predictions.

5. Model Iterations: The code showcases iterative training with multiple epochs. Typically, models benefit from more training epochs, but there's a risk of overfitting if not monitored closely.
