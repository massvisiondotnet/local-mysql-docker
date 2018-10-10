# Local MySQL Docker

## Setup Local Project

- start docker: __docker-compose up__
- stop docker: __docker-compose down__
- access db: __mysql -h127.0.0.1 -P3399 -uadmin -pdocker__
- burning docker images: <br>
      docker stop $(docker ps -a -q)  <br>
      docker rm $(docker ps -a -q) <br>
      docker rmi $(docker images -q) <br>
