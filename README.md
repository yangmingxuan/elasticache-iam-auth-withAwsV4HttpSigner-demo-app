# AWS ElastiCache IAM Authentication Examples

This repository provides sample code demonstrating how to connect to **Amazon ElastiCache for Redis** and **Amazon ElastiCache for Valkey** clusters using **IAM Authentication**.

## Overview

Amazon ElastiCache supports IAM authentication, providing enhanced security by eliminating the need to store Redis/Valkey passwords. This repository contains production-ready examples in multiple programming languages to help you quickly integrate IAM authentication into your applications.

### ElastiCache Engines
- **Amazon ElastiCache for Redis** (version 7.0+)
- **Amazon ElastiCache for Valkey** (version 7.2+)

### Programming Languages
- **Java 8** - See [java8/README.md](java8/README.md)
- **Python 3.10+** - See [python/README.md](python/README.md)

### Prerequisites
According to documentation [Authenticating with IAM for Elasticache](https://docs.aws.amazon.com/AmazonElastiCache/latest/dg/auth-iam.html) or [Authenticating with IAM for MemoryDB](https://docs.aws.amazon.com/memorydb/latest/devguide/auth-iam.html) , set up IAM user/role permission policies, create Elasticache/MemoryDB users(type=iam) for Redis/Valkey clusters, generate access strings, and complete other required steps.

## Getting the Code
Choose the sample code in your preferred language.

### Java sample code Only
```
git clone --filter=blob:none --sparse https://github.com/aws-samples/sample-Elasticache-iam-authentication-python-demo-application.git elasticache-iam-auth-demo-app
cd elasticache-iam-auth-demo-app/
git sparse-checkout set java8
cd java8
```
### Python sample code Only
```
git clone --filter=blob:none --sparse https://github.com/aws-samples/sample-Elasticache-iam-authentication-python-demo-application.git elasticache-iam-auth-demo-app
cd elasticache-iam-auth-demo-app/
git sparse-checkout set python
cd python
```

### Both sample codes
```
git clone --filter=blob:none --sparse https://github.com/aws-samples/sample-Elasticache-iam-authentication-python-demo-application.git elasticache-iam-auth-demo-app
cd elasticache-iam-auth-demo-app/
git sparse-checkout set java8 python
```


