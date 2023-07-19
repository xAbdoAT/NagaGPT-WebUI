# ChatGPT WebUI - Chimera Version

## Models
- gpt-3.5-turbo
- gpt-3.5-turbo-poe
- gpt-3.5-turbo-16k
- gpt-3.5-turbo-16k-poe
- gpt-4
- gpt-4-0613
- gpt-4-poe
- gpt-4-32k
- gpt-4-32k-poe
- claude_instant
- claude-instant-100k
- claude-2-100k

<br>

## 🔑 <strong>REQUIRE API KEY BUT IT'S FREE</strong> 
Get your API key from the [ChimeraGPT Discord](https://discord.gg/chimeragpt).

## Project Hosting and Demonstration 🌐🚀
The project is hosted on multiple platforms to be tested and modified.
|Plataform|Status|Repo|Demo|
|--|--|--|--|
|[replit](https://replit.com/)|![Active](https://img.shields.io/badge/Active-brightgreen)|[FreeGPT WebUI](https://replit.com/@xAbdoAT/ChimeraGPT)|[Chat](https://chimeragpt.xabdoat.repl.co/chat/)

## Table of Contents  
- [Getting Started](#getting-started-white_check_mark)  
  - [Cloning the Repository](#cloning-the-repository-inbox_tray)  
  - [Install Dependencies](#install-dependencies-wrench)  
- [Running the Application](#running-the-application-rocket)  
- [Docker](#docker-)  
  - [Prerequisites](#prerequisites)  
  - [Running the Docker](#running-the-docker)
- [Incorporated Projects](#incorporated-projects-busts_in_silhouette)

##

# Getting Started :white_check_mark:  
To get started with this project, you'll need to clone the repository and have [Python](https://www.python.org/downloads/) installed on your system.  
  
## Cloning the Repository :inbox_tray:
Run the following command to clone the repository:  

```
git clone https://github.com/xAbdoAT/ChimeraGPT-WebUI.git
```

## Install Dependencies :wrench: 
In the project directory, install the dependencies:
```
pip install -r requirements.txt
```

## Setting up the API Key and .env :key:
Before starting the application, you need to obtain an API key from ChimeraGPT and set up the .env file.

### Get your API key
Get your API key from the [ChimeraGPT Discord](https://discord.gg/chimeragpt).

### Create .env
In the project directory, create a file called .env.
Open the .env file and add the following line:

```
CHIMERA_API_KEY=<API-Key>  
```

## Running the Application :rocket:
To run the application, run the following command:
```
python run.py
```

Access the application in your browser using the URL:
```
http://127.0.0.1:1338
```
or
```
http://localhost:1338
```

## Docker 🐳
### Prerequisites
Before you start, make sure you have installed [Docker](https://www.docker.com/get-started) on your machine.

### Get your API key
Get your API key from the [ChimeraGPT Discord](https://discord.gg/chimeragpt).

### Running the Docker
Pull the Docker image from Docker Hub:
```
docker pull xAbdoAT/ChimeraGPT-WebUI
```

Run the application using Docker:
```
docker run -p 1338:1338 -e CHIMERA_API_KEY=<API-Key> xAbdoAT/ChimeraGPT-WebUI
```

Access the application in your browser using the URL:
```
http://127.0.0.1:1338
```
or
```
http://localhost:1338
```

When you're done using the application, stop the Docker containers using the following command:
```
docker stop <container-id>
```
