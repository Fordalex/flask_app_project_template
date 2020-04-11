# Flask project using mongoDB template

Download zip and open in your preferred IDE.

## Creating a virtual environment for linux

    python3 -m venv .venv
    source .venv/bin/activate

## Install flask

Using the command line:

    pip install flask
    pip install flask_pymongo

Run your python script with the following command:
    python app.py 
(Normaly named: app.py, run.py)

## Deploying on heroku

After you have installed all the dependencies for your project, run the following commands.

    pip freeze --local > requirements.txt

This will create the list of dependencies your project will rely on.
The Procfile is used to communicate with heroku and tell it what project type we have.

- create a new app on heroku

When your on the app dashboard go to the Deploy section and down to 'deployment method' select github and link heroku to the relevant project.

- still on the Deploy section, continue down to the 'manual deploy' and press 'deploy branch'
