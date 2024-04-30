# Steps to run the bot:
## 1. Install python and pip
## 2. Install poetry : "pip isntall poetry"
## 3. Install dependencies using 'poetry install' command
## 4. Creat the bot:
### 4.1. In Telegram find: "botfather"
### 4.2. Click "Start" (or send '/start')
### 4.3. Select "newbot" (or send '/newbot')
### 4.4. Choose a name for your bot 
### 4.5. Copy the given TOKEN from botfather
### 4.6. Go to '.env' and paste the TOKEN there in 'TOKEN' parameter
## 5. [OPTIONAL] Go to '.env' and edit your DB configuration. Without it some features may be locked or fail
## 6. Run the main.py




# How to create virtualenv?
## 1. Try "poetry install" command
## 2. if .venv folder is not created the try:
### a. delete "poetry.lock" file
### b. run "poetry config virtualenvs.path D:\\git\\AppsProject\\OpenU-Project-BackEnd" (Change the path according to your folder) 
### c. run "poetry install"
## 2. More helpful commands:
### a. "poetry config virtualenvs.path"
### b. "poetry config --list"


# How to add more libraries? "poetry add [name]"

# How to progress version? "poetry version [patch, minor, major, prepatch, preminor, premajor, prerelease]"

# for more poetry info: https://python-poetry.org/docs/cli/



# IMPOTANT:
## need to add "/" commands
## Do it via BotFather