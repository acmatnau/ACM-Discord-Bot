# ACM Discord Bot
A discord bot developed in Python to help manage the ***ACM at NAU*** discord server. 

This project will allow the officers and current members to be able to contribute to an NAU ACM recognized open source repository.

---

## Setup

1. Fork and Clone this project through HTTPS or SSH:

```
# Using HTTPS
git clone https://github.com/{your-github-user}/ACM-Discord-Bot.git

# Using SSH
git clone git@github.com:{your-github-user}/ACM-Discord-Bot.git
```

2. Setup your workstation for local development by creating a virtual environment and installing project dependencies:

### For Windows:
```
# Make sure pip is installed
python -m pip --version

# Install virtualenv
python -m pip install --user virtualenv

# Create the virtual environment
python -m virtualenv env

# Activate the virtual environment
.\env\Scripts\activate

# Confirm you are in the virtual environment
where python

# Install project dependencies
pip install -r requirements.txt
```

### For macOS and Linux:
```
# Make sure pip is installed
pip --version

# Or
pip3 --version

# Install virtualenv
python3 -m pip install --user virtualenv

# Create the virtual environment
python3 -m virtualenv env

# Activate the virtual environment
source env/bin/activate

# Confirm you are in the virtual environment
which python

# Install project dependencies
pip install -r requirements.txt
```

**Whenever you are developing locally, ensure that your virtual environment is activated or you will not have the valid project dependencies!**

You can leave the virtual environment by running in your CLI:
```
deactivate
```