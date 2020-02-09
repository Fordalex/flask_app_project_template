# Flask project template

Download zip and open in your preferred IDE.

## Install flask

pip install flask

Then install all the dependencies for your project.

pip freeze --local > requirements.txt

## Creating a virtual environment for linux

- Go to the directory you would like to set up your virtual environment.
- Python3 -m venv .venv
- source .venv/bin/activate

Run your python script with the following command:
python app.py (Normaly named: app.py, run.py)

## Deploying on heroku

The Procfile is used to communicate with heroku and tell it what project type we have.

- create a new app on heroku

When your on the app dashboard go to the Deploy section and down to 'deployment method' select github and link heroku to the relevant project.

- still on Deploy section, continue down to the 'manual deploy' and press 'deploy branch'