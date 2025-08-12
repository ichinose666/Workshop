---
title: "Create IAM User"
weight: 1
chapter: false
pre: "<b>2.1 </b>"
---

## Create IAM User for AWS Config

AWS Config requires an IAM User with sufficient permissions to configure and manage AWS resources.

1. **Open** the **IAM** service in the AWS Management Console.
2. Go to **Users** → **Add users**.
3. Enter a username (e.g., `UserADMIN`).
4. In **AWS access type**, choose:
   - **Access key - Programmatic access** if using CLI/SDK.
   - **Password - AWS Management Console access** if Console login is needed.
5. Click **Next** to set permissions:
   - Choose **Attach existing policies directly**.
   - Attach **AdministratorAccess** (or minimum required permissions like `AWSConfigUserAccess`).
6. Click **Next**, skip tags if not needed.
7. Select **Create user**.
8. Save the **Access key** and **Secret access key** (if created for programmatic access).

![Create IAM User](/images/2.1/001.png?featherlight=false&width=90pc)

![Create IAM User](/images/2.1/002.png?featherlight=false&width=90pc)

![Create IAM User](/images/2.1/003.png?featherlight=false&width=90pc)


