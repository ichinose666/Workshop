---
title: "Setup SNS Topic"
weight: 4
chapter: false
pre: "<b>2.4 </b>"
---

## Setting up Amazon SNS Topic for AWS Config Notifications

AWS Config can send change notifications and compliance updates via Amazon SNS. Let’s create a new topic and subscription.

1. **Go to** the **SNS** service in AWS Management Console.
2. Click **Create topic**.
3. Choose **Standard** type and name your topic (e.g., `config-alerts-23`).
4. Click **Create topic**.
5. Inside the topic page, click **Create subscription**.
6. Set **Protocol** to `Email` and enter your email address.
7. Click **Create subscription**.
8. Check your email and confirm the subscription by clicking the confirmation link.

![Setup SNS Topic](/images/2.4/009.png?featherlight=false&width=90pc)

![Setup SNS Topic](/images/2.4/010.png?featherlight=false&width=90pc)

![Setup SNS Topic](/images/2.4/011.png?featherlight=false&width=90pc)

![Setup SNS Topic](/images/2.4/012.png?featherlight=false&width=90pc)

![Setup SNS Topic](/images/2.4/013.png?featherlight=false&width=90pc)



