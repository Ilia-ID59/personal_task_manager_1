# Personal Task Manager
![Static Badge](https://img.shields.io/badge/python-blue?logo=python&logoColor=white)

A simple taak manager built with Python for learning git & github 

## Features 
- add multiple tasks
- save tasks 
- load saved tasks 
- admin mode 
- set task priority

## Task priority
each task can have one of these priority levels : 
- low 
- medium 
- high

## Requirements
- Python 
- pyhton-dotenv

## Project Structure
```
Personal Task Manager/ 
│   .env.example
│   .gitignore
│   main.py
│   README.md
│   requirements.txt
│   tasks.py
│
├───images
│       animation.gif
│       image_1.jpg
│
└───
```

## Installation
Install the required paskages : 
```bash
pyhton -m pip install -r requirements.txt
```

## Enviroment Setup 
create a `.env` file in the project folder 

Ues `.env.example` as a template 

Add your admin password 

```env 
admin_pass=your_password_here
``` 
replace `your_password_here` with your own admin password 

## Run the Program 
run the main file : 
```bash 
python main.py
``` 

## Screenshot 
![personal_task_manager_screenshot](images/screenshot.jpg) 

## Demo 
![personal_task_manager_demo](images/animation.gif) 
