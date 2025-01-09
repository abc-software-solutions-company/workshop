# Backend Workshop

Welcome to the **Backend Workshop**, an in-depth training program focused on modern backend development techniques, including Redis, Kafka, database optimization, API security, and automation.

---

## Table of Contents

1. [Buổi 1: API Documentation & Automation](#buổi-1-api-documentation--automation)
2. [Buổi 2: API Security & Advanced Patterns](#buổi-2-api-security--advanced-patterns)
3. [Buổi 3: Database Optimization](#buổi-3-database-optimization)
4. [Buổi 4: Redis & Kafka](#buổi-4-redis--kafka)

---

## 📚 Buổi 1: API Documentation & Automation

### 🎯 Mục tiêu:
- Tạo tài liệu API chi tiết với **Swagger**.
- Kiểm thử API tự động với **Postman**.
- Giám sát hiệu suất API với **Postman Monitor**.

### 📋 Nội dung Chi Tiết:

1. **API Documentation với Swagger**
   - **Swagger và OpenAPI Specification:** Tổng quan về Swagger.
   - **Cấu hình Swagger trong NestJS:** Tạo tài liệu API.
   - **Xác thực JWT trong Swagger:** Tài liệu hóa bảo mật API.

2. **API Testing với Postman**
   - **Kiểm thử API:** GET, POST, PUT, DELETE.
   - **Environment & Variables:** Quản lý biến môi trường.
   - **Automation Test Scripts:** Tạo Test Suite cho API.

3. **Mock Server với Postman**
   - **Tạo Mock API:** Phát triển song song Frontend và Backend.
   - **Environment Switching:** Chuyển đổi môi trường dễ dàng.

4. **API Monitoring & Debugging**
   - **Giám sát API:** Sử dụng Postman Monitor.
   - **Phân tích lỗi API:** Timeout, lỗi xác thực.

### 🛠️ Thực hành:
- Tạo tài liệu API đầy đủ với Swagger.
- Kiểm thử API JWT Authentication trên Postman.
- Tạo Mock API và Postman Monitor để giám sát API.

---

## 🛡️ Buổi 2: API Security & Advanced Patterns

### 🎯 Mục tiêu:
- Bảo mật API theo chuẩn **OWASP API Security Top 10**.
- Xác thực và ủy quyền API với **JWT (JSON Web Token)**.
- Triển khai **Rate Limiting** và **Throttling** để bảo vệ API.
- Áp dụng các mẫu thiết kế nâng cao cho API.

### 📋 Nội dung Chi Tiết:

1. **OWASP API Security Top 10**
   - Phân tích các lỗ hổng bảo mật phổ biến.
   - Phòng chống lỗi phổ biến: SQL Injection, Authentication Bypass, Data Exposure.

2. **Xác thực và Ủy quyền với JWT**
   - **JWT (JSON Web Token):** Cách JWT hoạt động.
   - **Xác thực API với JWT:** Middleware và Guards trong NestJS.
   - **Refresh Token:** Tái tạo token an toàn.

3. **API Rate Limiting & Throttling**
   - **Giới thiệu Rate Limiting & Throttling:** Bảo vệ API khỏi DDoS.
   - **Cấu hình Rate Limiting:** Trên NestJS với `nestjs/throttler`.

4. **Advanced API Patterns**
   - **Service Layer Pattern:** Tách biệt logic nghiệp vụ khỏi Controller.
   - **Repository Pattern:** Tối ưu kết nối với database.
   - **CQRS Pattern:** Phân tách Command và Query để tăng hiệu suất API.

### 🛠️ Thực hành:
- Tạo API bảo mật với JWT Authentication và Refresh Token.
- Áp dụng Rate Limiting cho các endpoints quan trọng.
- Sử dụng Service Layer và Repository Pattern trong NestJS.

---

## 🟡 Buổi 3: Database Optimization

### 🎯 Mục tiêu:
- Tối ưu hóa cơ sở dữ liệu cho ứng dụng backend.
- Giảm thiểu các vấn đề phổ biến như **N+1 Problems**, đảm bảo **ACID**, và mở rộng hệ thống qua **Sharding** và **Replication**.

### 📋 Nội dung Chi Tiết:

1. **ACID – Đảm bảo Tính Toàn Vẹn Dữ Liệu (1 tiếng)**
   - **ACID Properties:** Atomicity, Consistency, Isolation, Durability.
   - **Transactions:** Cách đảm bảo giao dịch an toàn.

2. **N+1 Problems – Phân tích và Giải quyết (1 tiếng)**
   - **N+1 Query Problem:** Vấn đề và nguyên nhân.
   - **Cách phát hiện N+1 Query:** Sử dụng Query Log.
   - **Giải pháp:** Lazy Loading vs Eager Loading.

3. **Sharding & Replication – Mở Rộng và Sao Lưu Dữ Liệu (1 tiếng)**
   - **Sharding:** Phân chia cơ sở dữ liệu theo chiến lược Horizontal Scaling.
   - **Replication:** Sao lưu dữ liệu để tăng khả năng chịu lỗi.
   - **High Availability:** Cấu hình Primary-Replica Setup.

### 🛠️ Thực hành:
- Xây dựng giao dịch ACID trong PostgreSQL.
- Sửa lỗi N+1 Query trong ORM (MikroORM hoặc TypeORM).
- Cấu hình Sharding và Replication trong PostgreSQL.

---

## 🟢 Buổi 4: Redis & Kafka

### 🎯 Mục tiêu:
- Làm chủ Redis và Kafka trong việc quản lý dữ liệu tạm thời và truyền tải dữ liệu thời gian thực.
- Tích hợp Redis và Kafka vào ứng dụng NestJS.

### 📋 Nội dung Chi Tiết:

1. **Redis – Quản lý Dữ liệu Tạm thời (1.5 tiếng)**
   - **Giới thiệu Redis:** In-memory database, use-cases phổ biến (caching, Pub/Sub, Session Store).
   - **Caching với Redis:**
     - Key-Value Store.
     - Expiration Policy (TTL).
   - **Pub/Sub với Redis:** Cách hoạt động Pub/Sub trong Redis.

2. **Kafka – Xử lý Luồng Dữ liệu Thời gian Thực (1.5 tiếng)**
   - **Giới thiệu Kafka:** Cách hoạt động của Event Streaming.
   - **Producer & Consumer:** Tạo Producer và Consumer Kafka.
   - **Message Broker:** Quản lý luồng dữ liệu với Kafka Topics.

### 🛠️ Thực hành:
- Tích hợp Redis Cache vào ứng dụng NestJS.
- Xây dựng kênh Pub/Sub với Redis.
- Xử lý luồng dữ liệu thời gian thực bằng Kafka.

---

## 📌 Chuẩn bị trước buổi học:
- Cài đặt môi trường phát triển:
  - Node.js
  - NestJS
- Tải xuống các công cụ cần thiết:
  - Redis
  - Kafka
  - PostgreSQL
  - Swagger
  - Postman
  - ELK Stack

---

🎉 **Hẹn gặp tại workshop!**