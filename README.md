# Crater Detection System - Quick Start
### This guide contains all the commands needed to run the Martian & Lunar Crater Detection project.

## Setup Commands
### Clone the repository
git clone https://github.com/Omkar3344/Crater_Detection_System.git
cd Martian_Lunar_Crater_Detection

### Create and activate virtual environment
## Windows
### Create virtual environment
python -m venv venv

### Activate virtual environment
venv\Scripts\activate

## macOS/Linux
### Create virtual environment
python3 -m venv venv

### Activate virtual environment
source venv/bin/activate

## Run the application
### Navigate to the API directory
cd object_detection_api

## Install required packages
pip install -r requirements.txt

### Load the models
python main.py