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

7. Select the required EC2 instance metric.

# Step 3: Configure Metric Details

<img width="945" height="553" alt="image" src="https://github.com/user-attachments/assets/7a2fead7-15de-42ce-9b21-78f8f2838f57" />

| Parameter       | Value                        |
| --------------- | ---------------------------- |
| Namespace       | AWS/EC2                      |
| Metric Name     | InstanceEBSIOPSExceededCheck |
| Statistic       | Average                      |
| Period          | 5 minutes                    |
| Threshold Type  | Static                       |
| Condition       | Greater                      |
| Threshold Value | 1                            |

8. Select Static as the threshold type.

9. Select Greater as the comparison condition.

10. Enter 1 as the threshold value.

11. Review the metric graph.

12. Click Next to continue.

# **Configure Alarm Actions**

After configuring the metric, the Configure actions page will open.

Under Notification, click Add notification if you want to configure SNS notifications.

You can also configure Lambda, Auto Scaling, or EC2 actions if required.

In your screenshot, no notification or other action is configured.

Continue to the next step.

<img width="1001" height="728" alt="image" src="https://github.com/user-attachments/assets/9a05fa69-4a37-4530-a3db-43bba503a5d6" />

# **Add Alarm Details**

<img width="1252" height="717" alt="image" src="https://github.com/user-attachments/assets/bcb0ea7b-f940-49cc-9fdb-790c9e5d34ac" />

1. Enter the alarm name.
2. Use the following alarm name:
   
shankar-alarm

3. Add an optional description.
4. Add tags if required.
5. Review the alarm details.
6. Click Next.

# **Preview and Create Alarm**

The Preview and create page will appear.

Review the selected metric.

Verify the namespace.

Check the statistic and period.

Verify the threshold condition.

Check the alarm name.

Confirm that the configuration is correct.

Click Create alarm.

<img width="848" height="582" alt="image" src="https://github.com/user-attachments/assets/32c9c38c-9c8e-4ecf-bcca-b0a4997b1cd7" />

# **Verify Created Alarm**

After clicking Create alarm, return to the Alarms page.

Check the alarm list.

Find your alarm named shankar-alarm.

Verify that it appears in the list.

Click the alarm name to open its details.

<img width="800" height="454" alt="image" src="https://github.com/user-attachments/assets/498f0bb8-baa7-49d1-a6fa-020b72ed52e2" />

# **View Alarm Details and Monitoring Graph**

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/025f1c7e-c650-4fa5-8d31-216834899651" />

# **CONCLUSION**

Through this practical, I learned how to use Amazon CloudWatch to monitor AWS resources and manage EC2 instance performance. I gained hands-on experience navigating CloudWatch, 
exploring EC2 metrics, configuring alarm conditions, and creating a CloudWatch alarm named shankar-alarm. This practical helped me understand how CloudWatch identifies monitoring 
conditions and helps administrators detect potential performance issues. Overall, I gained practical knowledge of AWS monitoring, alarm configuration, and cloud infrastructure management.








   














