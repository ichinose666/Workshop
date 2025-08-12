---
title: "Create EC2 Instance"
weight: 2
chapter: false
pre: "<b>2.2 </b>"
---

## Launching an EC2 Instance for Testing

We will create a small EC2 instance to generate configuration changes that AWS Config can track.

1. **Go to** the **EC2** service in AWS Management Console.
2. Click **Launch instance**.
3. Enter a name (e.g., `AWS-CONFIG`).
4. Choose an Amazon Machine Image (AMI), such as **Amazon Linux 2**.
5. Select a small instance type (e.g., `t2.micro`).
6. Under **Key pair**, create or select an existing key pair.
7. In **Network settings**, allow only necessary inbound rules (e.g., SSH from your IP).
8. Click **Launch instance**.

![Create EC2](/images/2.2/004.png?featherlight=false&width=90pc)

![Create EC2](/images/2.2/005.png?featherlight=false&width=90pc)


