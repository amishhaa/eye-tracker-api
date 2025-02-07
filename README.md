# 👁️ Eye Lab: Gaze Tracker API

Eye Lab is an open source tool to create eye tracking usability tests. It started as a final undergraduation work for Computer Engineering of student [Karine Pistili](https://www.linkedin.com/in/karine-pistili/) that created the first prototype. The idea is to evolve it to a more complete and useful tool with the help of the community.

The current version of the software allows users to create their usability sessions of an website, recording the webcam, screen and mouse movements and use this information to find out where the user has been looking into the screen by using heatmaps.

## 👩‍💻 Setting up project locally

The project consists of two parts, this repository contains the backend of the application and the frontend can be found [here](https://github.com/uramakilab/web-eye-tracker-front). Install it as well.

### Prerequisites

* [Python 3x](https://www.python.org/downloads/)

### 1. Create virtual environment

Before installing all dependencies and starting your Flask Server, it is better to create a python virtual environment. You can use the [venv package](https://docs.python.org/3/library/venv.html), these commands are examples for creating and activating your virtual enviornment.

**Linux and Mac OS**

```
python3 -m venv /path/to/new/virtual/environment
``` 
```
source name-of-event/bin/activate
```

**Windows**

```
python -m venv /path/to/new/virtual/environment
```
```
name-of-event/Scripts/activate
```

### 2. Install dependencies

Install all dependencies listed on the requirements.txt with:

```
pip install -r requirements.txt
```

### 3. Run the Flask API

```
flask run
```

## 🧑‍🤝‍🧑 Contributing

Anyone is free to contribute to this project. Just do a pull request with your code and if it is all good we will accept it. You can also help us look for bugs, if you find anything create and issue.

## 📃 License

This software is under the [MIT License](https://opensource.org/licenses/MIT). 

Copyright 2021 Uramaki Lab
