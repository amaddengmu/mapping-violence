# Mapping Early Modern Violence

This repository contains code, documentation, and related resources for the Mapping Early Modern Violence project at the [Roy Rosenzweig Center for History and New Media](https://rrchnm.org).

## Setup 

To create your Django environment, navigate to the mvproject directory and do the following: 

```sh
% cd mapping-violence
% python3 -m venv .venv
% source .venv/bin/activate
(.venv) % python3 -m pip install requirements.txt
```

When you're done doing active work on Django, don't forget to deactivate your virtual environment. 

```sh
% deactivate
```

To run the local server:

```sh
python3 manage.py runserver
```

To run the React front-end, navigate to the root of the directory. Make sure your node modules are installed (`npm i`). Use `npm run start` to run the development server. You may need to globally install react-scripts for this to work (`npm install -g react-scripts`).

## Project Team

- Dr. Amanda Madden (PI)
- Dr. Jason Heppler (senior developer) 
- James Ball
- Ethan Haarer
- Owen Huggins
- Caleb McFarland
- Hannah Wysocki
