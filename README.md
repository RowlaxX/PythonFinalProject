# PythonFinalProject

This project is a python approch for studying a dataset. The studied dataset is 'Online Shoppers Purchasing Intention Dataset' wich can be found at https://archive.ics.uci.edu/dataset/468/online+shoppers+purchasing+intention+dataset  

It should be useless to download the dataset since the python script download it in RAM

# API note

The API server is contained inside the ipynb file  
Just run the ipynb from the start to launch the server on port 5000  

You can test the API using this command :

```
curl -X POST -H "Content-Type: application/json" -d '{"Administrative": 3,"Administrative_Duration": 87.83333333,"Informational": 0,"Informational_Duration": 0.0,"ProductRelated": 27,"ProductRelated_Duration": 798.3333333,"BounceRates": 0.0,"ExitRates": 0.012643678,"PageValues": 22.9160357,"SpecialDay": 0.8,"Month": "Feb","OperatingSystems": 2,"Browser": 2,"Region": 3,"TrafficType": 1,"VisitorType": "Returning_Visitor","Weekend": false}' http://127.0.0.1:5000/predict
```

# Environment setup

```
pip install sklearn
pip install imblearn
pip install pandas
pip install seaborn
pip install matplotlib
```
