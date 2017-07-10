---
layout: post
title: Các lệnh cơ bản khi làm việc với Docker
---

1. Tại và run một container
```
docker run --privileged --name laravel -p 8080:80 -p 8000:8000 -v D:/docker/laravel:/home/bkand1909 -it ubuntu /bin/bash
```

2. Exec một container đang chạy
```
docker exec -it laravel /bin/bash
```
