---
title: "Setting up AWS Config"
weight: 1
chapter: false
pre: "<b>3.1 </b>"
---

## Enable and Configure AWS Config

AWS Config allows you to **evaluate, audit, and monitor** the configurations of your AWS resources. It also stores configuration history for compliance and auditing purposes.

### Steps to Configure

1. **Open** the AWS Management Console and navigate to **AWS Config**.
2. If this is your first time setting it up, click **Get started**.
3. In the **Settings** section:
   - **Resource types**: Select **All resources** (monitor all resources) or specify only the resource types you want to track.
   - **Delivery method**:
     - **S3 bucket**: Select the bucket created earlier to store configuration files.
     - **SNS Topic**: Select the SNS Topic created in step 2.4 to receive change notifications.
4. In the **AWS Config role** section:
   - Select **Create AWS Config service-linked role** if you don’t already have one.
5. Click **Next** → Review your settings.
6. Click **Confirm** to enable AWS Config.

### Verifying AWS Config

- Once enabled, AWS Config will begin recording the current configuration state of resources and track any changes.
- To test:
  1. Modify a resource that AWS Config is tracking (e.g., change an S3 bucket policy).
  2. Go back to **AWS Config** → **Resources** → locate that resource.
  3. Check the **Configuration timeline** to see the recorded changes.

⚠ **Note:** Some minor changes (such as non-critical metadata updates) may not be recorded immediately. Synchronization can take a few minutes depending on the service.

---

![AWS Config Setup](/images/3.1/024.png?featherlight=false&width=90pc)

![AWS Config Setup](/images/3.1/025.png?featherlight=false&width=90pc)

![AWS Config Change Detection](/images/3.1/035.png?featherlight=false&width=90pc)

![AWS Config Timeline](/images/3.1/036.png?featherlight=false&width=90pc)
