# docker example

## to build n image
docker build -t 'bocacode':1.0 .

## to create a container
docker run --rm -d -p 8000:8000/tcp bocacode:1.0