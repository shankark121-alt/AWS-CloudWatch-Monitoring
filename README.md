# **INTRODUCTION TO AMAZON CLOUDWATCH**

Amazon CloudWatch is a monitoring and observability service provided by Amazon Web Services (AWS). It helps users monitor AWS resources, applications, 

system performance, and operational activities.CloudWatch collects and monitors metrics, logs, and events. It allows administrators to create dashboards 
and alarms to identify performance issues and receive notifications when specified conditions occur.

# **MAIN FEATURES:**

Monitoring AWS resources.

Collecting metrics and logs.

Creating monitoring dashboards.

Configuring alarms.

Sending notifications through Amazon SNS.

Monitoring EC2 instance performance.

# **AWS CloudWatch Practical – Step-by-Step Execution**

# 1. Login to AWS Management Console**

Open your web browser.

Visit AWS Management Console.

Enter your AWS account credentials.

After login, the AWS Console Home page will appear.

Search for CloudWatch in the AWS search bar.

<img width="748" height="393" alt="image" src="https://github.com/user-attachments/assets/4883ca79-3ed4-4d79-ac16-84bb51aabe1e" />

# **2. Open Amazon CloudWatch**

Search for CloudWatch in the AWS search bar.

Click on CloudWatch.

The CloudWatch Overview page will open.

Check the left-side navigation panel.

Explore the available sections, such as:
- Application Signals
- Infrastructure Monitoring
- Metrics
- Logs
- Network Monitoring

<img width="838" height="415" alt="image" src="https://github.com/user-attachments/assets/5cbd6867-c7df-4df8-852e-27278ea9bc73" />

# **3. Open CloudWatch Metrics**

In the left navigation panel, expand Metrics.

Click All Metrics.

The Metrics page will open.

Select the Browse tab.

Explore the available metric namespaces.

Select the AWS service whose metrics you want to monitor.

<img width="811" height="392" alt="image" src="https://github.com/user-attachments/assets/6215d5aa-dd8b-4b39-b972-c0217fc96742" />

# **4. Create a CloudWatch Alarm**

# Step 1: Open Create Alarm

1. Navigate to CloudWatch.
2. Click Alarms in the left navigation panel.
3. Click the Create alarm button.

<img width="1988" height="1117" alt="image" src="https://github.com/user-attachments/assets/088c714a-256e-4326-ae66-b9b9a3eebf22" />

# Step 2: Specify Metric and Conditions

1. Select the metric data source.
2. Choose Metrics.
3. Select the metric type.
4. Choose the AWS/EC2 namespace.
5. Select the required EC2 metric.
6. Choose the metric named:

InstanceEBSIOPSExceededCheck
8. Select the required EC2 instance metric.
   














