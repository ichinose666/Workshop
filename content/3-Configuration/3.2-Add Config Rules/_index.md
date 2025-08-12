---
title: "Add Config Rules"
weight: 2
chapter: false
pre: "<b>3.2 </b>"
---

## Adding Config Rules to monitor compliance

Config Rules let you define compliance standards and check whether AWS resources meet them.

1. In AWS Management Console, go to **AWS Config** → **Rules** → **Add rule**.
2. Choose either **AWS Managed Rules** (pre-built) or **Custom Rule** (your own Lambda).
3. Example: Search for and select **required-tags** to enforce tagging.
4. Configure the rule parameters (if applicable).
5. Choose **Trigger**:
   - **Configuration changes** (trigger on changes).
   - **Periodic** (run on a schedule).
6. Click **Next** and then **Add rule**.

![Add Config Rule](/images/3.2/026.png?featherlight=false&width=90pc)

![Add Config Rule](/images/3.2/027.png?featherlight=false&width=90pc)

![Add Config Rule](/images/3.2/028.png?featherlight=false&width=90pc)

![Add Config Rule](/images/3.2/029.png?featherlight=false&width=90pc)


