---
title: "Create S3 Bucket"
weight: 3
chapter: false
pre: "<b>2.3 </b>"
---

## Creating an Amazon S3 Bucket for AWS Config Logs

**Note:** Before proceeding, ensure you have the necessary IAM permissions to create S3 buckets.

AWS Config requires an S3 bucket to store configuration snapshots and compliance history. Follow these steps to create it:

1. **Sign in** to the AWS Management Console.
2. Navigate to the **S3** service.
3. Click **Create bucket**.
4. Enter a unique **Bucket name** (e.g., `config-log-bucket-23`).
5. Choose the **AWS Region** where you want the bucket created.
6. For **Block Public Access settings**, ensure **Block all public access** is **enabled**.
7. Leave other settings as default and click **Create bucket**.

![Create S3 Bucket](/images/2.3/006.png?featherlight=false&width=90pc)

![Create S3 Bucket](/images/2.3/007.png?featherlight=false&width=90pc)

![Create S3 Bucket](/images/2.3/008.png?featherlight=false&width=90pc)


