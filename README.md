docker build . -f ./Dockerfile --tag=my_django_project

docker run -p 80:8000 my_django_project