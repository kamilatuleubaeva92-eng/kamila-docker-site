# kamila-docker-site

docker build -t kamila-docker-site .
docker run -d --name kamila-site-container -p 8080:80 kamila-docker-site
