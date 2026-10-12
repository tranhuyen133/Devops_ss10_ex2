# Session 10 - Ex2: Backend Single-stage Dockerfile

Web API đơn giản (Node.js + Express) đóng gói bằng Dockerfile single-stage.

## Cách chạy
docker build -t hw-backend:v1 .
docker run -d --name app-single-stage -p 8080:3000 hw-backend:v1
curl -i http://localhost:8080/

## Kết quả
Container Up, curl trả về HTTP 200 kèm JSON.