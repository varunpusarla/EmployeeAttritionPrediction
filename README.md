1. IMPORTING THE DATASETS: <br>
Imported the training and testing datasets using pandas .read_csv() function. <br>

2. EXPLORATORY DATA ANALYSIS: <br>
a)Placed all the missing values in a seperate list. <br>
b)Placed all thenumeric, categorical and discrete values in different lists. <br>
c)Visualized numerical features with line plot from matplotlib. <br>
d)Visualized continousfeatures with histogram from matplotlib. <br>

3. FEATURE ENGINEERING: <br>
a) Replace all the missing values with the mean of their respective field. <br>
b) Encoded Object datatypes using Label Encoder from sklearn 

4. FEATURE SCALING: <br>
a) Scaled all the data with standard scaler from sklearn. <br>

5. MODEL FITTING: <br>
a) Split the data into training and test sets. <br>
b)Trained the model using XGBoost Regressor. <br>
c) hyperparameter tuning with RandomsearchCV. <br>
d) Stored the predictions in 'MySubmission.csv'. <br>
