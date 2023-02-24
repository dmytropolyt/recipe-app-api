# recipe-app-api
Recipe API project made by django-rest-framework using test-driven-development

This api provides things like create recipes with ingredients, tags and images. It visualisated
by Swagger UI using drf-spectacular package for automated documentation.

Usage
--
It is custom user model that provides registration with email instead of username.
It uses tokenAuth(Token-based authentication with required prefix "Token").
After registration user can obtain token and use api.

User can create recipes with multiple ingredients, tags and with one image.
User can get a list of recipes, ingredients and tags.
He can change them, retrieve by id and delete.
Get recipes with filter ingredients and tags and more.

Deployment
--
App deployed on aws EC2. Link: http://ec2-18-193-157-71.eu-central-1.compute.amazonaws.com/api/docs/

Stack
--
+ Backend: Python(Django, django-rest-framework)
+ Database: PostgreSQL
+ Virtualization: Docker, docker-compose
+ CI/CD: GitHub Actions
+ Proxy: nginx
+ Server: Amazon EC2


