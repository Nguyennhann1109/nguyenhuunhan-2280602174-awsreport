---
title : "Workshop"
date : "`r Sys.Date()`"
weight : 5
chapter : false
pre : " <b> 5. </b> "
---

# AntiGroup Infrastructure Manual Deployment Guide

#### Overview

In this workshop, you will manually deploy the entire infrastructure and services for **AntiGroup - Real-time Streaming Collaboration Platform** using the AWS Management Console.

The goal of this lab is to help you understand how to configure each infrastructure component corresponding to the project's Terraform source code, establish network connections, configure security, and manage data flows securely.

#### Order of Execution (Mandatory)

The deployment must strictly follow the sequence below to ensure dependent resources are created in the correct order:

1. [Overview](5.1-workshop-overview/)
2. [Secrets Manager](5.2-secrets-manager/)
3. [VPC & Networking](5.3-vpc-network/)
4. [Security Groups](5.4-security-groups/)
5. [S3 Buckets & IAM Roles](5.5-S3-buckets-iam/)
6. [RDS PostgreSQL](5.6-rds-database/)
7. [ElastiCache Redis](5.7-elasticache-redis/)
8. [ECR & Push Images](5.8-ecr-push/)
9. [ALB & Target Groups](5.9-load-balancer/)
10. [CloudFront Distribution](5.10-cloudfront/)
11. [ECS Cluster & Services](5.11-ecs-fargate/)
12. [Resource Cleanup](5.12-cleanup/)

