# DevOps Workshop

Welcome to the **DevOps Workshop**, a comprehensive training program designed to enhance your understanding of distributed systems, scalability, and infrastructure automation using modern tools like Prometheus, Terraform, and Jenkins.

---

## Table of Contents

1. [Buổi 1: Infrastructure as Code (IaC)](#buổi-1-infrastructure-as-code-iac)
   - [Tổng Quan về Infrastructure as Code (IaC)](#tổng-quan-về-infrastructure-as-code-iac)
   - [Tìm Hiểu Terraform](#tìm-hiểu-terraform)
   - [Tìm Hiểu Ansible](#tìm-hiểu-ansible)
   - [Kết Hợp Terraform và Ansible](#kết-hợp-terraform-và-ansible)
   - [CI/CD Pipeline với Jenkins](#cicd-pipeline-với-jenkins)
2. [Buổi 2: Distributed Systems & Scalability](#buổi-2-distributed-systems--scalability)
   - [Giới thiệu Kiến trúc Distributed Systems](#giới-thiệu-kiến-trúc-distributed-systems)
   - [Service Discovery](#service-discovery)
   - [Load Balancing](#load-balancing)
   - [Circuit Breaker Pattern](#circuit-breaker-pattern)
   - [Giám sát và Logging với Prometheus & Grafana](#giám-sát-và-logging-với-prometheus--grafana)
   - [Deployment & Scalability](#deployment--scalability)

---

## 🛠️ Buổi 1: Infrastructure as Code (IaC)

### 🎯 Mục tiêu Buổi Học:
- Hiểu khái niệm **Infrastructure as Code (IaC)** và tầm quan trọng của nó trong DevOps.
- Làm quen với các công cụ phổ biến: **Terraform**, **Ansible**.
- Tự động hóa việc triển khai hạ tầng.
- Tạo pipeline CI/CD với **Jenkins**.

---

### Tổng Quan về Infrastructure as Code (IaC)

#### 🎯 Mục tiêu:
- Hiểu khái niệm và lợi ích của IaC.

#### 📋 Nội dung:
- **IaC là gì?**
- Mutable Infrastructure vs Immutable Infrastructure.
- Lợi ích: Reproducibility, Consistency, Scalability.
- Công cụ phổ biến: Terraform, Ansible, AWS CloudFormation.

#### 🛠️ Thực hành:
- So sánh các công cụ IaC trong các tình huống thực tế.

---

### Tìm Hiểu Terraform

#### 🎯 Mục tiêu:
- Triển khai hạ tầng với **Terraform**.

#### 📋 Nội dung:
- **Giới thiệu Terraform:** HashiCorp Configuration Language (HCL).
- **Khái niệm cơ bản:** Providers, Resources, Variables, Outputs.
- **State Management:** Terraform State.
- **Modules:** Tái sử dụng cấu hình.

#### 🛠️ Thực hành:
- Triển khai một server cơ bản trên AWS/GCP/Azure.
- Sử dụng module để quản lý nhiều dịch vụ.

---

### Tìm Hiểu Ansible

#### 🎯 Mục tiêu:
- Tự động hóa cấu hình server với **Ansible**.

#### 📋 Nội dung:
- **Ansible là gì?**
- So sánh với Puppet, Chef.
- **Playbook và Inventory:** Viết playbook và cấu hình inventory.
- **Idempotency:** Đảm bảo tác vụ luôn cho kết quả như nhau.

#### 🛠️ Thực hành:
- Cấu hình Nginx và Docker bằng Ansible.
- Tạo Playbook triển khai nhiều node backend.

---

### Kết Hợp Terraform và Ansible

#### 🎯 Mục tiêu:
- Hiểu cách kết hợp Terraform và Ansible trong một quy trình IaC hoàn chỉnh.

#### 📋 Nội dung:
- Terraform: Infrastructure Provisioning.
- Ansible: Configuration Management.

#### 🛠️ Thực hành:
- Tạo server trên AWS/GCP bằng Terraform.
- Cấu hình Nginx và Docker bằng Ansible.

---

### CI/CD Pipeline với Jenkins

#### 🎯 Mục tiêu:
- Tạo pipeline CI/CD để tự động hóa việc triển khai hạ tầng.

#### 📋 Nội dung:
- **Jenkins:** Tích hợp với Terraform và Ansible.
- **Pipeline as Code:** Jenkinsfile.

#### 🛠️ Thực hành:
- Viết pipeline Jenkins để triển khai hạ tầng với Terraform.
- Cấu hình server với Ansible qua pipeline.

---

## ☁️ Buổi 2: Distributed Systems & Scalability

### 🎯 Mục tiêu Buổi Học:
- Hiểu kiến trúc **Microservices** và cách xây dựng hệ thống phân tán.
- Làm quen với các khái niệm quan trọng: **Service Discovery**, **Load Balancing**, và **Circuit Breaker**.
- Giám sát và logging hệ thống với **Prometheus**, **Grafana**, và **ELK Stack**.
- Triển khai và mở rộng dịch vụ với chiến lược **Scalability**.

---

### Giới thiệu Kiến trúc Distributed Systems

#### 🎯 Mục tiêu:
- Hiểu nguyên tắc cơ bản và lợi ích của hệ thống phân tán.

#### 📋 Nội dung:
- **Distributed Systems là gì?**
- Monolith vs Microservices Architecture.
- Lợi ích và thách thức:
  - High Availability
  - Scalability
  - Fault Tolerance

---

### Service Discovery

#### 🎯 Mục tiêu:
- Hiểu và triển khai Service Discovery để quản lý giao tiếp giữa các dịch vụ.

#### 📋 Nội dung:
- **Service Discovery là gì?**
- Static vs Dynamic Discovery.
- Công cụ: **Consul**, **Eureka**.
- **Thực hành:** Tạo Service Discovery với **Consul** trong hệ thống NestJS.

---

### Load Balancing

#### 🎯 Mục tiêu:
- Cân bằng tải giữa các dịch vụ backend để đảm bảo hiệu suất và độ tin cậy cao.

#### 📋 Nội dung:
- **Load Balancer là gì?**
- Layer 4 vs Layer 7 Load Balancing.
- Công cụ: **Nginx**, **HAProxy**.
- **Thực hành:** Triển khai Load Balancer với **Nginx**.

---

### Circuit Breaker Pattern

#### 🎯 Mục tiêu:
- Ngăn chặn sự cố lan rộng trong hệ thống phân tán.

#### 📋 Nội dung:
- **Circuit Breaker là gì?**
- Các trạng thái: Closed, Open, Half-Open.
- **NestJS Circuit Breaker Module.**
- **Thực hành:** Triển khai Circuit Breaker trong một dịch vụ NestJS.

---

### Giám sát và Logging với Prometheus & Grafana

#### 🎯 Mục tiêu:
- Theo dõi và giám sát hiệu suất hệ thống.

#### 📋 Nội dung:
- **Prometheus:** Thu thập metrics hệ thống và ứng dụng.
- **Grafana:** Tạo Dashboard từ Prometheus.
- **ELK Stack:** Phân tích logs.

#### 🛠️ Thực hành:
- Tích hợp Prometheus vào hệ thống NestJS.
- Tạo Dashboard API trên Grafana.
- Phân tích logs bằng ELK Stack.

---

### Deployment & Scalability

#### 🎯 Mục tiêu:
- Hiểu cách triển khai và mở rộng hệ thống backend.

#### 📋 Nội dung:
- **Scaling Strategies:** Horizontal Scaling vs Vertical Scaling.
- **Containerization với Docker:** Đóng gói ứng dụng.

---

🎉 **Hẹn gặp tại workshop!**