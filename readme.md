# Ripple Frontend Interview

### Setup
- Clone repository
If you don't have pip: https://pip.pypa.io/en/stable/installing/
If you don't have virtualenv: ``` pip install virtualenv ```
- Install requirements
``` virtualenv venv ```
``` source venv/bin/activate ```
``` pip install -r requirements.txt ```
- Start Flask app
``` python app.py ```

### Building the frontend
- *Optional* If you need to install Javascript libraries/frameworks:
``` npm install <package name> ```
- Flask will render templates/index.html-- **This should be your starting point!**
- Index.html contains commented links for a few common CSS/Javascript libaries.  You may use these or add any others you deem useful.
- You may add additional html files to templates/ or additional Javascript/CSS files to templates/frontend
- You may use any online resource as reference.

### Expectations
The primary objective is to create an interface for viewing and submitting information to the provided API endpoints.  You have a considerable degree of freedom in designing how this interface should look and function, but at the very least, it should be able to communicate with all provided endpoints.
-  Dynamic rendering and Javascript-based API calls are preferred.
-  Utilizing one of the common CSS frameworks is preferred.
