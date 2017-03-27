# Redirect http to https

A tiny nginx web server which redirects all traffic to https.

## Run Container
In order to run the container you need execute this simple command
```
docker run -d --name rewrite-https -p 80:80 erlend/redirect-https
```
