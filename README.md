# WebScraping2
This project scrapes Flikart for mobile phones and updates a MongoDB collection. An API was built using Flask for CRUD operations on the MongoDB collection. The API was used to build a webpage to query and display the contents of the DB.

# Usage Instructions
Download this repository and run the following commands in your terminal:

`pip install requirements.txt`

`python api.py`

If all the required packages are installed, the website should be hsted at

`http://localhost:5000/`

If the owner decides to pull down the database, the program will be broken. To change the database to which the api connects to, modify `MONGO_DBNAME` & `MONGO_URI` in `api.py`.

The API Docs can be found at `http://localhost:5000/docs` when the Flask app is being hosted.

# Teams
#### Web scraper and writing scraped data to DB
* Ibrahim Kalil
* Pranesh Suresh
* Swetha Mohan
#### Flask API, code integration and docs
* Adithya Ganesan
* Amudhan Manivasagam
#### Visualizing data from DB using JS and the Flask API
* Kamali Suthakaran
* Swarnalatha
* Narmadha
* Rohini
* Lashya

## Postman
![alt text](https://github.com/adithya2411/WebScraping2/blob/main/Postman.JPG?raw=true)

## Webpage
![alt text](https://github.com/adithya2411/WebScraping2/blob/main/Webpage.jpg?raw=true)
