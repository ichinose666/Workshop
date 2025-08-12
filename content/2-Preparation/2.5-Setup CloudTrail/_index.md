---
title: "Setup AWS CloudTrail"
weight: 5
chapter: false
pre: "<b>2.5 </b>"
---

## Enabling CloudTrail for AWS Config

AWS Config relies on AWS CloudTrail to record API calls for resource changes. Let’s enable it.

1. **Go to** the **CloudTrail** service in AWS Management Console.
2. If no trail exists, click **Create trail**.
3. Enter a name (e.g., `config-trail`).
4. Choose **Create new S3 bucket** or select an existing one for log storage.
5. Enable **Log file validation** for integrity checking.
6. Click **Create trail**.

![Setup CloudTrail](/images/2.5/016.png?featherlight=false&width=90pc)

![Setup CloudTrail](/images/2.5/017.png?featherlight=false&width=90pc)

![Setup CloudTrail](/images/2.5/018.png?featherlight=false&width=90pc)

![Setup CloudTrail](/images/2.5/019.png?featherlight=false&width=90pc)

![Setup CloudTrail](/images/2.5/020.png?featherlight=false&width=90pc)

![Setup CloudTrail](/images/2.5/021.png?featherlight=false&width=90pc)

![Setup CloudTrail](/images/2.5/022.png?featherlight=false&width=90pc)

![Setup CloudTrail](/images/2.5/023.png?featherlight=false&width=90pc)


