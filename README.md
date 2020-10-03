# docker-compose_flask-restful_nginx_deployment_example

cd to flask > docker build -t flask_restful:test .

cd to nginx > docker build -t nginx_for_restful:test .

cd to / docker-compose up or docker-compose up -d


/nginx 'default.conf' add 'protocol=http'

/docker-compose.yml 80:80 to 81:81 for avoid port overlap 'docker-compose_flask_nginx_deployment_example'

ref to https://basketdeveloper.tistory.com/66
