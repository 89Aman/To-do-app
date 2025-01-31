# To-do-app

## Project Description
This is a simple To-Do application built using Flask. The application allows users to add, delete, and mark tasks as completed. The user interface is built using HTML and Tailwind CSS.

## Installation
1. Clone the repository:
   ```
   git clone https://github.com/89Aman/To-do-app.git
   ```
2. Navigate to the project directory:
   ```
   cd To-do-app
   ```
3. Install the dependencies using `requirements.txt`:
   ```
   pip install -r requirements.txt
   ```
   The project requires `flask` as a dependency.

## Usage
1. Run the application:
   ```
   python app.py
   ```
2. Open your web browser and go to `http://127.0.0.1:5000/` to access the To-Do app.

## Deployment
To deploy the application, you can use a platform like Heroku or any other cloud service provider. Here are the general steps to deploy on Heroku:
1. Create a `Procfile` in the project directory with the following content:
   ```
   web: python app.py
   ```
2. Install the Heroku CLI and log in to your Heroku account:
   ```
   heroku login
   ```
3. Create a new Heroku app:
   ```
   heroku create
   ```
4. Push the code to Heroku:
   ```
   git push heroku master
   ```
5. Open the deployed app in your web browser:
   ```
   heroku open
   ```

The application is now deployed and can be accessed via the Heroku URL provided.
