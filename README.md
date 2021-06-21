# Exercise: Endpoints for Application Status
This exercise aims to extend a Python Flask web application with status and metrics endpoints.

Extend the Python Flask application with `/status` and `/metrics` endpoints, considering the following requirements:

* Both endpoints should return an HTTP 200 status code
* Both endpoints should return a JSON response e.g. `{"user": "admin"}`. (Note: the JSON response can be hardcoded at this stage)
* The `/status` endpoint should return a response similar to this example: `result: OK - healthy`
* The `/metrics` endpoint should return a response similar to this example: `data: {UserCount: 140, UserCountActive: 23}`
