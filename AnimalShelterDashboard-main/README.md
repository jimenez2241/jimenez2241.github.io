# AnimalShelterDashboard

About the Project/Project Title

The web application dashboard is an application that can interact with the database to return a table of that contains different types of animals, with the app users will be able to filter the table to select: water rescue, Mountain or Wilderness Rescue, and Disaster or Individual Tracking animals. 
Motivation
When using the script users will be able to easily find the rescue animals by category.

Getting Started
The steps to develop a Dashboard that can read data from a MongoDB database and interact with the table are: 
•	Import MongoClient from the pymongo distribution into the python script. 
•	Import ObjectId from bson.objectid into the python script
•	Create a __init__ method to access the MongoDB databases and collections by authenticating 
•	Develop a “read” method that accepts key/value pairs (dictionary) as input and find the animal by looking for their information. 
•	On Jupyter notebook import python script created above.
•	Instantiate class and use authentication method to get into mongo database.
•	Import image and any visuals needed to create a dashboard and create layout with HTML.
•	Create update_dashboard method to update layout if user selects a button. 
•	Create update_map method to crate a geolocation chart

Installation
List the tools you need to use the software and how to install them.
•	Python 3 – Install by using the command prompt and run: 
sudo apt-get update
sudo apt-get install python3.6
•	MongoDB - https://docs.mongodb.com/manual/administration/install-on-linux/ 
•	Jupyter notebook – Install by using the command prompt and run with pip:
pip install jupyterlab

Steps

Instantiate AnimalShelter class and authenticate with username and password and import image for logo:

Develop layout for dashboard and add logo:
 ![11](https://user-images.githubusercontent.com/63686603/138618261-594243a3-d2dc-4dfc-bd5e-35cf12c522ac.png)


Define layout for dashboard: 
 ![12](https://user-images.githubusercontent.com/63686603/138618268-73e176f0-2001-442c-9977-a0a5d5e0b7a6.png)

Add method to change data when a button is clicked: 

![13](https://user-images.githubusercontent.com/63686603/138618270-9862bde0-6cec-4b85-a5a4-d0104545c4f7.png)

Create a method to add chart:
 ![14](https://user-images.githubusercontent.com/63686603/138618279-f9299b9d-5a4f-4a8d-8e4d-2942ec3d79dd.png)

Create a method for geolocation chart:
 ![15](https://user-images.githubusercontent.com/63686603/138618282-27a69226-ef02-4196-9a36-dc1ddef0ada8.png)

Test functionalities: 
 
![16](https://user-images.githubusercontent.com/63686603/138618288-7c179fb1-4f22-4dc7-9206-5c965277d43d.png)

Contact
Your name:  Caio Leonardo De Morais

