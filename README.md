
# EliteTech Internship - Cloud Computing Task 1

## ✅ Task: Cloud Storage Setup on AWS S3

This repository contains files and setup details for Task 1 of the EliteTech Cloud Computing Internship.

---

### 🪣 Bucket Details:
- **Bucket Name:** internship-project-krish
- **Region:** EU (Stockholm) - `eu-north-1`

---

### 📁 Uploaded Files:
- `readme.txt`
- `sample-image.jpg`
- `cloud-storage-demo.pdf`

---

### 🔗 Public Access File:
[Click here to view the public image file](https://internship-project-krish.s3.eu-north-1.amazonaws.com/sample-image.jpg)

---

### 📸 Screenshots:
> *(Optional)* You can upload and embed screenshots like this:





---

## ✅ Task 2: Cloud Monitoring and Alerts (AWS CloudWatch)

### 🎯 Objective:
Monitor an EC2 instance using AWS CloudWatch, set up an alert, and visualize metrics in a custom dashboard.

---

### 🧰 Tools Used:
- **Platform:** AWS
- **Services:** EC2, CloudWatch
- **Region:** eu-north-1 (Stockholm)

---

### 🛠️ Monitoring Setup:
- EC2 instance: `CloudMonitorDemo` (t3.micro)
- Metrics Tracked:
  - CPUUtilization
  - NetworkIn
  - DiskReadBytes

---

### 🔔 Alarm Configuration:
- **Alarm Name:** HighCPUAlert
- **Condition:** CPUUtilization > 50% for 5 minutes
- **State:** OK (monitoring active)
- **Notification:** Optional (no SNS used)

---

### 📊 Dashboard:
- **Name:** CloudMonitorDashboard
- **Widgets Added:**
  - CPUUtilization (Line)
  - NetworkIn
  - DiskReadBytes (optional)

---

### 📸 Screenshots:
- ![Alarm View](./screenshots/Screenshot%202025-06-27%20122021.png)
- ![Dashboard Created](./screenshots/Screenshot%202025-06-27%20122209.png)

---

### ✅ Summary:
This task demonstrates how to effectively monitor a cloud server (EC2) using AWS CloudWatch with custom alarms and dashboards.

---

