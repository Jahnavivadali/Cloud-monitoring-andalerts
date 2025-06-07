# Cloud-monitoring-andalerts
COMPANY   : CODTECH IT SOLUTIONS

NAME      : VADALI JAHNAVI

INTERN ID :CT04DL1041

DOMAIN    :CLOUD COMPUTING

DURATION  :4 WEEKS

MENTOR    :NEELA SANTHOSH

DESCRIPTION:

In this task, I implemented a **cloud monitoring solution** using **Amazon CloudWatch**, the native monitoring service provided by AWS. The objective was to set up monitoring and alerting for a cloud-based application to ensure real-time visibility, operational efficiency, and proactive alerting on resource usage and performance metrics.

I began by launching an **EC2 instance** running a web server (Apache) using Amazon Linux 2. Then, I installed and configured the **CloudWatch Agent** on the EC2 instance to collect custom metrics such as memory and disk usage, in addition to default metrics like CPU utilization.

Once data was being sent to CloudWatch, I created a **custom dashboard** to visualize the system’s health. The dashboard included multiple widgets displaying key metrics like CPU utilization, disk space, and network activity, offering a real-time snapshot of the instance's performance.

To ensure timely notifications, I set up **CloudWatch Alarms**. These alarms were configured to monitor specific thresholds — for example, when CPU usage exceeds 60%. Notifications were sent using **Amazon SNS (Simple Notification Service)**, which triggered email alerts to notify me of any abnormal behavior.

This monitoring setup helps in identifying performance bottlenecks, reducing downtime, and maintaining system reliability. The task not only enhanced my understanding of AWS monitoring services but also demonstrated how cloud observability tools can be integrated into production environments to ensure operational excellence.

