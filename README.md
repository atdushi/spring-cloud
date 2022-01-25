- Eureka http://localhost:8761/
- Client http://localhost:9872/greeting
- Feign http://localhost:8190/get-greeting
- Zuul http://localhost:5555/cloud/gclient/greeting

docker-compose up --build -d

docker-compose down

