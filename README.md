# LSTM-used-in-predicting-the-pollution-in-Telangana-state
Performance Metric is Mean Absolute error(MAE)<br>
Overview of the dataset is as follows:<br>
1)stationcode<br>
2)SO2 <br>
3)NO2<br>
4)PM10<br>
5)PM2.5 <br>
6)date e.t.c<br>
Sorted the dataset with date  <br>
Then I calculated Air Quality Index(AQI) with SO2,NO2, PM10 that is known as Normalization in our terminology.<br>
Then I removed outliers<br>
Then I used a BASELINE Model (Naive Model) to limit the error<br>
Then I used another baseline model Simple Moving Averages<br>
Atlast using LSTM the model is trained i.e, <br>
we cannot train the model as usual but we need to convert the dataset into supervised dataset so I used a method to <br>
overcome the constraint<br>
Atleast the error was about 1.5-2.5(approx.) MAE

Thank You<br>
Hope You enjoy by reading the ipython notebook to get the whole clarity of the project<br>

INSTALLATION GUIDE
1.	At first we need to go to Python official page and need to Install python 3.6+ version which ever possible and Add python to path.<br>
2.	Then after that from Anaconda official page install Anaconda Prompt 3.6+ version and Also Microsoft vs. Code along with Anaconda and Add Anaconda to python.<br>
3.	After installing Anaconda and Python we need to install some packages for that we need to open Command Prompt or Anaconda Prompt:<br>
	pip3 install numpy.
	pip3 install seaborn.
	pip3 install sklearn.
	pip3 install –upgrade tensorflow.
	pip3 install keras.<br>
4.	After installing these packages we need to open Jupyter Notebook and open the PREDICTING_AIR_QUALITY_USING_TIME_SERIES_ANALYSIS.ipynb and Click on run all cells on top left corner.<br>
5.	The outputs are displayed on the next line of each cell.<br>

