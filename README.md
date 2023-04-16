# lighttp

Web directory to upload html file.
/var/www/localhost/htdocs/

build and run container with docker compose
"docker-compose up -d"

build a container
"docker pull adpatidar/lighthttpd:latest"
"docker run -d -t -p 8000:80 --name wellcome adpatidar/lighthttpd:latest"

container shell
"docker exec -it CONTAINERID/NAMES /bin/sh"
This repo has very lightweight httpd image approx 9.5MB, it is for testing purpose of html content.
