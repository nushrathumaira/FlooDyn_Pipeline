
### Project Title: 
    FlooDyn: A Dynamic Web-based Streamflow Prediction Pipeline

### Contributors:
    Nushrat Humaira  
    Sadegh Sadeghi Tabas
    Vidya Samadi
    Nina Hubig
    

### Project Description: 
    In this research a number of data driven (machine learning and deep learning) and data mining methods
    including multi-layer perceptron (MLP), long short-term memory (LSTM) and a hybrid deep learning method 
    of convolutional neural network and LSTM have been implemented in a web designed platform to predict sequential
    flow rate values based on a set of collected runoff factors in a global scale (North America, South America,Africa,Europe, Asia, Australia).

### Dependencies:
    Tensorflow
    Keras
    Numpy
    Pandas
    Scikit-Leran
    Matplotlib
    Seaborn
    FanyImpute
    Hydroeval
    Folium
    JS
    Jquery
    Leaflet
    Django
    


## Repository info

### Datasets: 
    The input dataset retrieved from three sources as follows:
    1- GRDC website(https://portal.grdc.bafg.de/applications/public.html?publicuser=PublicUser#dataDownload/Stations)
    2- NCDS website(https://www.ncdc.noaa.gov/)
    3- CAMELS dataset


### Models:
    Two ipython notebooks fill the missing values using two different deep neural networks
    LSTM_Singlelayer, LSTM_CNN, MLP are three data driven models used in our project
    Web Platform for Dynamical Streamflow Prediction with leaflet, jQuery (Please load test.html to start the webapp)
    Notebooks with continent name demonstrate model results on station data




