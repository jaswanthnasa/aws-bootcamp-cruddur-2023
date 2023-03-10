# Week 0 — Billing and Architecture

#### 1)AWSCLI installation 

![aws-installted](https://user-images.githubusercontent.com/92042814/219269406-ea5b1673-1378-4186-8085-27f93b3a3dfd.JPG)


### 2)sts caller identity check from cloud shell
![sts-caller-identity](https://user-images.githubusercontent.com/92042814/219874091-3d8459a0-0518-49b1-b3c2-80e53b45f677.JPG)



### 3)Architecture Diagram using Lucid

Worked on arcjitecture diagram using lucid charts.
![arch-diagram](https://user-images.githubusercontent.com/92042814/219745512-19e2bb2f-3775-484b-a80b-622b166481e3.JPG)


[AWS archtecture diagram lucid reference link](https://lucid.app/lucidchart/3b9e1231-da56-4993-be42-bbf7aa719985/edit?viewport_loc=-1005%2C182%2C2220%2C1038%2C0_0&invitationId=inv_9e1d9c5b-f372-42bd-bf22-f372544d0098)

### 4)Created Cloduwatch alarm to notify the expendicture of cloud services via SNS topic

![BillingAralm](https://user-images.githubusercontent.com/92042814/219873261-c838a389-5d36-4552-805d-f0a739af00fe.JPG)

```
referred below AWS documentaion to set up billing alarm in cloud wathch to estimate usage
One finding is billing alarm can be created only in US-EAST-1 (N. Virginia) region as in AWS billing metric data is **only** stored in N.Virginia region .
```
[Create Billing alarm](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/monitor_estimated_charges_with_cloudwatch.html#creating_billing_alarm_with_wizard)



















