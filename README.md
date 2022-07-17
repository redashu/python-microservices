# python-microservices

## when compose is having backend and db 
### create something in backend container using compose 

```
(env) fire@node155:~/microservices/tutorial$ docker-compose exec backend bash 
root@656a6cd7df56:/app# ls
Dockerfile  db.sqlite3  docker-compose.yaml  env  manage.py  requirements.txt  tutorial
root@656a6cd7df56:/app# python manage.py  startapp products
root@656a6cd7df56:/app# 

```

