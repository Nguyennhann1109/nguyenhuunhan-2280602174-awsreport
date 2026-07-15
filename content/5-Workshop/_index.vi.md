---
title : "Workshop"
date :  "`r Sys.Date()`" 
weight : 5 
chapter : false
pre : " <b> 5. </b> "
---

# Hướng dẫn Triển khai hệ thống AntiCollab lên AWS Management Console

#### Tổng quan

Trong phần này, chúng ta sẽ thực hiện triển khai thủ công toàn bộ hạ tầng và các dịch vụ của nền tảng **AntiCollab - Real-time Streaming Collaboration Platform** thông qua AWS Management Console. 

Mục tiêu của bài lab là giúp hiểu rõ cách cấu hình từng thành phần hạ tầng tương đương với mã nguồn Terraform của dự án, thiết lập kết nối mạng, cài đặt bảo mật và quản lý luồng dữ liệu một cách an toàn.

#### Thứ tự thực hiện (Bắt buộc)

Việc triển khai cần tuân thủ nghiêm ngặt theo trình tự dưới đây để đảm bảo các tài nguyên phụ thuộc được tạo đúng thứ tự:

1. [Giới thiệu](5.1-overview/)
2. [Mạng & Bảo mật](5.2-network-security/)
   - [AWS Cognito User Pool](5.2-network-security/5.2.1-cognito-auth/)
   - [Secrets Manager](5.2-network-security/5.2.2-secrets-manager/)
   - [VPC và Mạng](5.2-network-security/5.2.3-vpc-network/)
   - [Security Groups](5.2-network-security/5.2.4-security-groups/)
3. [Dữ liệu & Lưu trữ](5.3-data-storage/)
   - [S3 Buckets & IAM Roles](5.3-data-storage/5.3.1-s3-buckets-iam/)
   - [RDS PostgreSQL](5.3-data-storage/5.3.2-rds-database/)
   - [ElastiCache Redis](5.3-data-storage/5.3.3-elasticache-redis/)
4. [Triển khai & Phân phối](5.4-deployment-delivery/)
   - [ECR & Push Images](5.4-deployment-delivery/5.4.1-ecr-push/)
   - [ALB & Target Groups](5.4-deployment-delivery/5.4.2-load-balancer/)
   - [CloudFront Distribution](5.4-deployment-delivery/5.4.3-cloudfront/)
   - [ECS Cluster & Services](5.4-deployment-delivery/5.4.4-ecs-fargate/)
5. [Dọn dẹp tài nguyên](5.5-cleanup/)

