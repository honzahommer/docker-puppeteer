# Docker Puppeteer 

## How to use this image

#### Dockerfile

```
FROM honzahommer/puppeteer
...
```

#### Docker run

```
docker run --rm honzahommer/puppeteer
```

#### Clone repository and build custom image

```
git clone https://github.com/honzahommer/docker-puppeteer.git
cd docker-puppeteer
...
docker build --tag puppeteer .
docker run --rm puppeteer
```
