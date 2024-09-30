build
```bash
docker build . -t ctnelson1997/cs571-f24-hw6-api
docker push ctnelson1997/cs571-f24-hw6-api
```

run
```bash
docker pull ctnelson1997/cs571-f24-hw6-api
docker run --name=cs571_f24_hw6_api -d --restart=always -p 48106:48106 -v /cs571/f24/hw6:/cs571 ctnelson1997/cs571-f24-hw6-api
```
