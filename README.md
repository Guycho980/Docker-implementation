# Docker-implementation

git add -A ; git commit -m 'updated project' ; git push

docker build -t IMAGE_NAME:IMAGE_TAG .

docker build -t apache-web:V1 .

docker run --name apache-webserver -p 80:80 -d apache-web:V2

