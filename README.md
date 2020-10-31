# README

This is a and simple Flask project created following different web tutorials. Follow the instructions below to get the app running in a local server in your PC with a local database.

- Clone this repository to a local folder
- Run the following commands for creating a virtual environment, working inside it and installing requirements needed for the project to run: 
``` 
virtualenv --python python3 venv
source venv/bin/activate
pip install -r requirements.txt
nodeenv --python-virtualenv
npm install -g less
``` 
- set correct lessc path in Line 6 of .env file (your_project_path/venv/bin/lessc)
- Run the following command to create a local sqlite database 
``` 
flask db init
``` 
- Finally, run the app in a local server with the following command 
``` 
./start.sh
``` 
- Enter to localhost:5000 in your web browser and start playing around
- To enter as an administrator to the blog, go to http://localhost:5000/admin. For being able to access you must first register and loggin as ADMIN_USER (check .env file ;D )
