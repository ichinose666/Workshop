---
title: "Cleanup Resources"
weight: 4
chapter: false
pre: "<b>4 </b>"
---

## Cleanup Resources

Follow these steps to remove all AWS resources created during the workshop. **Be careful** – this will permanently delete data and configurations.

### 4.1 Delete AWS Config Recorder & Delivery Channel
1. Go to **AWS Config** → **Settings**.
2. Stop the **Configuration Recorder**.
3. Delete the **Delivery Channel**.
4. Confirm deletion.

![Clean](/images/4/037.png?featherlight=false&width=90pc)

![Clean](/images/4/038.png?featherlight=false&width=90pc)

### 4.2 Delete Config Rules
1. In **AWS Config**, go to **Rules**.
2. Select each rule you created.
3. Choose **Delete** → Confirm.

![Clean](/images/4/039.png?featherlight=false&width=90pc)

### 4.3 Delete S3 Buckets
1. Go to **Amazon S3**.
2. Empty the bucket used for AWS Config logs.
3. Select the bucket → **Delete** → Type the bucket name to confirm.

![Clean](/images/4/040.png?featherlight=false&width=90pc)

### 4.4 Delete SNS Topics and Subscriptions
1. Go to **Amazon SNS**.
2. Open the **Topics** list and delete the topic.
3. Go to **Subscriptions** and delete all related subscriptions.

![Clean](/images/4/041.png?featherlight=false&width=90pc)

### 4.5 Delete IAM User
1. Go to **IAM** → **Users**.
2. Select the user you created for this workshop.
3. Remove any access keys or attached policies.
4. Delete the user.

![Clean](/images/4/042.png?featherlight=false&width=90pc)
