---
title: "Setup EventBridge"
weight: 3
chapter: false
pre: "<b>3.3 </b>"
---

## Setting up EventBridge to receive AWS Config events

EventBridge allows you to create automated event flows when configuration changes or compliance violations occur.

1. In AWS Management Console, go to **Amazon EventBridge**.
2. Select **Rules** → **Create rule**.
3. Enter a name (e.g., `config-rule-violation`).
4. In **Event source**, choose:
   - **AWS services** → **AWS Config**.
5. In **Event pattern**, select:
   - Event type: **Config Rules Compliance Change** or **Configuration Item Change**.
6. In **Target**, choose:
   - An SNS Topic, Lambda function, or Step Functions workflow to handle the event.
7. Click **Create**.

![Setup EventBridge](/images/3.3/030.png?featherlight=false&width=90pc)

![Setup EventBridge](/images/3.3/031.png?featherlight=false&width=90pc)

![Setup EventBridge](/images/3.3/032.png?featherlight=false&width=90pc)

![Setup EventBridge](/images/3.3/033.png?featherlight=false&width=90pc)

![Setup EventBridge](/images/3.3/034.png?featherlight=false&width=90pc)


