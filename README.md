# Salesforce Workflow Automation Project

## 📌 Overview

This project demonstrates a Salesforce automation solution to monitor high-value sales under an Opportunity and automatically notify users when business conditions are met.

---

## 🎯 Problem Statement

The business needs a system to:

* Track total sales under an Opportunity
* Identify high-value sales (≥ 100,000)
* Automatically notify when multiple high-value sales exist
* Reduce manual monitoring and improve response time

---

## 💡 Solution Implemented

* Created a custom object **Sales**
* Established a **Master-Detail Relationship** with Opportunity
* Implemented **Roll-Up Summary Fields** to calculate:

  * Total Sales Amount
  * Count of High-Value Sales
* Built a **Workflow Rule** to trigger automation
* Configured **Email Alerts** and **Task Creation**

---

## ⚙️ Key Features

* Automated tracking of sales data
* Real-time email notifications
* Task creation for follow-up
* No manual intervention required
* Scalable and efficient design

---

## 🔁 Working Logic

1. User creates an Opportunity
2. User adds Sales records under the Opportunity
3. System checks:

   * If Sales Amount ≥ 100,000
4. System counts high-value sales
5. If count ≥ 2:

   * Email alert is triggered
   * Task is created for Opportunity Owner

---

## 🧪 Testing Performed

* Created a sample Opportunity
* Added two Sales records with amount ≥ 100,000
* Verified:

  * High Value Sales Count updated correctly
  * Email notification received
  * Task created successfully

---

## 📊 Result

The system successfully:

* Identifies multiple high-value sales
* Sends automated email alerts
* Creates tasks for timely action

---

## 🚀 Conclusion

This project demonstrates how Salesforce automation can streamline business processes, reduce manual effort, and ensure timely decision-making through real-time alerts.

---

## 🛠️ Tools & Technologies

* Salesforce Classic
* Workflow Rules
* Email Templates
* Roll-Up Summary Fields
