# Crime-Spot

**Crime-Spot is a data-driven platform for monitoring, graphing, and modeling crime risks to identify the possible hotspots/clusters on the Google Map in the San Francisco area based on the existing or historical crime data.**

![PySpark](https://i.ibb.co/PNgMCXz/landing-page-policing.png)

The model is trained using the data available on San Francisco Data Portal over a period of 10 years. Find more details about the data here: https://data.sfgov.org/Public-Safety/SF-Crime-Heat-Map/q6gg-sa2p/data

## What It Does?👇

+ **Dashboard for visualization to see the crime numbers (Per Day, Month, and by Co-ordinates).**
+ **Real time identifcation of  hotspots/clusters of crime on the Google Map around the SFO area.**
+ **Morning, Noon, and Night based identification of crimes on the Google Map.**

See the Snapshot below:

<a href="https://ibb.co/rFJT9RC"><img src="https://i.ibb.co/bQnqtMS/Dashboard.png" alt="Dashboard" border="0"></a>

<a href="https://ibb.co/LhfWDv8"><img src="https://i.ibb.co/QjGR7Xf/Prediction-night.png" alt="Prediction-night" border="0"></a>


## Tech Stack: 👇
Crime-Spot uses a number of languages, libraries, frameworks, and APIs to work properly:

- **Python** - General Purpose Language **(For Machine Learning in this case)**.
- **JavaScript** - For integration of Google Maps, model functions and all related web functionalities in the front-end.
- **Flask** - Awesome microservice of Python for Web Apps.
- **Google Map API**- You will need "Google Map API Key" from your Google Cloud Console. It is chargable. 
- **Heroku** - For deploying the model on a PaaS.



## How to Run? 👇
For installation of required packages...

```sh
pip3 install requirements.txt
```
+ Replace your Google Map API Key in **prediction.html** file in templates folder.

Then run the below command to open the app in browser, 
```sh
python3 app.py
```

## Todo: 👇

+ User Authentication and Management
+ Patrolling management system
+ Push notification to the Patrolling department
+ PDF Report generation of the predicted hotspots on the Map


## Want to contribute? 👇
You can connect on 
+ Sonu1000raw@gmail.com
+ LinkedIn: https://www.linkedin.com/in/sonucr7/













