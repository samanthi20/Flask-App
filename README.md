How the Flask App Works

Flask Setup

Flask is a lightweight Python web framework used to build web applications.

We create an app instance which acts as the main application.

Routes

Routes are URLs that the user can visit.

Example: / (home page), /about (about page).

Each route is linked to a function that returns a response (like text or HTML).

Request & Response

When a user visits the route (like http://localhost:5000/), Flask processes the request.

The function for that route runs and returns a response (like "Hello, Flask App is running on Azure!").

Local Development

Running app.run(debug=True) starts a development server on your local machine (usually at http://127.0.0.1:5000).

Deployment

When deployed to Azure App Service, you push the code to GitHub.

Azure fetches the code, installs dependencies (from requirements.txt), and runs the app.

Then, the app is accessible on your Azure web URL.
