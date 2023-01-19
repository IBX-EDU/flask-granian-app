## ibx-flask-granian-app

Flask + Granian application for the Fly.io cloud deployment

# Components
- [Flask](https://github.com/pallets/flask): The Python micro framework for building web applications.
- [Granian](https://github.com/emmett-framework/granian): A Rust HTTP server for Python applications
- [Fly.io](https://fly.io): Fly is a platform for running full stack apps and databases.

# Deployment
0. [Fly.io](https://fly.io) - create account
1. mkdir ibx-flask-granian-app
2. cd ibx-flask-granian-app
3. python -m venv venv
4. .\venv\scripts\activate
5. pip install flask, granian
6. pip freeze > requirement.txt
7. create app.py and templates
8. some code
9. configure Procfile
10. flyctl auth login
11. flyctl launch
12. flyctl deploy
13. browse https://ibx-flask-granian-app.fly.dev/