# Microblog Flask

Access the system: https://microblog-rhsm.onrender.com

Solution developed during the course: Web Developer Bootcamp with Flask and Python in 2023 and implemented some tweaks and features.

![Microblog](https://github.com/rafael-hsm/microblog_flask/blob/main/static/microblog.png)

Microblog created during the course: Web Developer Bootcamp with Flask and Python in 2023

I implemented some visual features, but there are others to be implemented, and if you want to suggest some improvement, you can open an Issue.

To use locally:

## Tools
1. Python
2. VScode
3. MongoDB

## Create a path and clonning the repository
```cmd
mkdir microblog && cd microblog
git clone https://github.com/rafael-hsm/microblog_flask.git
```

## Navigate to path and active a virtual enviroment

```
cd microblog_flask
python -m venv venv
venv\Scripts\activate
```

## Install requirements and settings MongoDB 

```
pip install -r requirements.txt
```
Create a file with name .env and set data for access your MongoDB, you can see a example in file `.env.example`
```
MONGODB_URI=mongodb+srv://<your_username>:<your_password>@<name_your_db>.dbjo0y7.mongodb.net/
```

## Running application
```
flask run
```
If you can activate debug mode type this command:
```
set FLASK_DEBUG=True
```