docker build -t 49sd-website .
docker run -p 8080:80 49sd-website
docker save 49sd-website | gzip > 49sd-website.tar.gz
