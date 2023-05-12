# Recipe App API
The Recipe App API project using Django is a web application that provides users with the ability to search for and save their favorite recipes. The application uses the Django Rest Framework to provide a RESTful API that allows users to interact with the application's database of recipes.




## 🚀 Features
- User authentication and authorization using Django's Token based authentication system.
- CRUD (Create, Read, Update, Delete) functionality for recipes, allowing users to add, view, update, and delete recipes from the database.
- Search functionality that allows users to search for recipes by title or ingredient.
- Filtering functionality to improve the user experience.
- Unit tests to ensure the functionality of the application.



![All APIs EndPoints From My Project using Swagger](https://cdn.discordapp.com/attachments/694869240381046834/1106486789562191932/project_doc.jpg)




## 📖 Installation
Recipe App can be installed via Docker. To start, clone the repo to your local computer and change into the proper directory.

```
$ git clone https://github.com/ugauniyal/recipe-app-api.git
$ cd recipe-app-api
```




### Docker
```
$ docker-compose up -d --build
$ docker-compose exec web python manage.py migrate
$ docker-compose exec web python manage.py createsuperuser
# Load the site at http://127.0.0.1:8000
```