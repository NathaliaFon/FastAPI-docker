### Step-by-step:
#### Docker Setup:
1. Search for the file `docker-compose.yml`;
1. Open the **Integrated file explorer** (_`CTRL + B`_ + `CTRL + SHIFT + E`);
1. Within the file explorer click on the file with the **RMB** and select: "**_Open in integrated terminal_**" ;
1. Check if your **Docker** is up using the command:
```docker ps```;
1. If **Docker** is viable run the command:
```docker compose up -d```;
1. Wait for the initialization to be completed.
#### Virtual Envinronment setup:
Within the project folder follow the steps below:
1. Create a directory in the `backend` folder: ```cd backend```;
1. Within the directory run the command: ```python -m venv venv_name```;
1. After creation, run the activation command: ```venv_name\Scripts\activate```;
1. Wait for the virtual environment's activation.
#### Package instalation:
In the activated virtual environment follow the steps below:
1. Open the integrated terminal (_`CTRL + J`_);
1. Install **Fastapi** and **uvicorn** packages: ```pip install -r requirements.txt```;
1. Wait for the instalation to be completed.
#### 

