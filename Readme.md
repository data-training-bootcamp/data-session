Instructions are specific to Mac, but most instructions are similar.  Google is your best friend.
**Environment Setup**


Download and install Python, select 3.12 version.  Higher is fine too, but lets stick to this version.
  https://www.python.org/downloads/

  Start a Terminal:
     > python version     #to ensure you have python installed.

**Setup Virtual Environment**:
  > pip install virtualenv

**Create Virtual Environment**
  > mkdir session1
  > cd session1 
  > python -m venv env

  Active Virtual Environment
  > source env/bin/activate

  For Windows, try the following:
    env/Scripts/activate.bat //In CMD
    env/Scripts/Activate.ps1 //In Powershel

**Install requirements**
Create a requirements.txt and add required libraries that you would like to install
> pip install -r requirements.txt
