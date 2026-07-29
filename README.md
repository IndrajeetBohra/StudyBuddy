# StudyBud

StudyBud is a Django-based web application where users can create and join study rooms on various topics, engage in discussions, and collaborate with other learners.

## Screenshots

<table width="100%"> 
<tr>
<td width="50%">      
&nbsp; 
<br>
<p align="center">
  Feed Home
</p>
<img src="https://user-images.githubusercontent.com/72341453/134747262-0a92233d-8010-40f8-84c5-8d94895aac44.PNG">
</td> 
<td width="50%">
<br>
<p align="center">
  Room Conversation Preview
</p>
<img src="https://user-images.githubusercontent.com/72341453/134747155-3ca5b55f-b064-4741-aeae-abe90bddf41e.PNG">  
</td>
</table>

## Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/IndrajeetBohra/StudyBud.git
cd StudyBud
```

### 2. Create and activate a virtual environment

```bash
# Should probably remove the env folder from this repo
rm -rf env

# Install virtualenv if you haven't already
pip install virtualenv

# Create a virtual environment
virtualenv venv

# Activate the virtual environment
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the development server

```bash
python manage.py runserver
```

The application will be available at http://127.0.0.1:8000/

### 5. Error

If you get error like

```bash
ModuleNotFoundError: No module named 'distutils'
```

install below command and try running the server again

```bash
pip install setuptools
```
