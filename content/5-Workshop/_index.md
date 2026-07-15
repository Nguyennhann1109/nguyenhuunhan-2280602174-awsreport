---
title : "Workshop"
date : "`r Sys.Date()`"
weight : 5
chapter : false
pre : " <b> 5. </b> "
---

# AntiCollab Infrastructure Manual Deployment Guide

#### Overview

In this workshop, you will manually deploy the entire infrastructure and services for **AntiCollab - Real-time Streaming Collaboration Platform** using the AWS Management Console.

The goal of this lab is to help you understand how to configure each infrastructure component corresponding to the project's Terraform source code, establish network connections, configure security, and manage data flows securely.

#### Order of Execution (Mandatory)

The deployment must strictly follow the sequence below to ensure dependent resources are created in the correct order:

1. [Overview](5.1-overview/)
2. [Network & Security](5.2-network-security/)
   - [AWS Cognito User Pool](5.2-network-security/5.2.1-cognito-auth/)
   - [Secrets Manager](5.2-network-security/5.2.2-secrets-manager/)
   - [VPC & Networking](5.2-network-security/5.2.3-vpc-network/)
   - [Security Groups](5.2-network-security/5.2.4-security-groups/)
3. [Data & Storage](5.3-data-storage/)
   - [S3 Buckets & IAM Roles](5.3-data-storage/5.3.1-s3-buckets-iam/)
   - [RDS PostgreSQL](5.3-data-storage/5.3.2-rds-database/)
   - [ElastiCache Redis](5.3-data-storage/5.3.3-elasticache-redis/)
4. [App Deployment & Delivery](5.4-deployment-delivery/)
   - [ECR & Push Images](5.4-deployment-delivery/5.4.1-ecr-push/)
   - [ALB & Target Groups](5.4-deployment-delivery/5.4.2-load-balancer/)
   - [CloudFront Distribution](5.4-deployment-delivery/5.4.3-cloudfront/)
   - [ECS Cluster & Services](5.4-deployment-delivery/5.4.4-ecs-fargate/)
5. [Resource Cleanup](5.5-cleanup/)


