# Comands

- mkdir sayhello
- cd sayhello
- vi index.html
- vi Dockerfile
- docker build -t sayhello .
- docker run --name nginx -p 8000:80 sayhello

### aws

- aws configure (access key + secret key)
- eb init (steps)
- eb create (steps) (check if region has a default vpc) (check differents services)
- eb list
- eb status
- eb open

### after changes

- eb deploy

### delete eb

- eb terminate (delete S3 permisions, then delete S3)
