# Automated Leave Request System

## 👤 Author

Sinenhlanhla Khumalo

---

## 📌 Project Overview

An automated system that allows users to submit leave requests, which are processed through an approval workflow and stored in SharePoint.

---

## 🛠️ Tools Used

* Microsoft Forms
* Power Automate
* SharePoint
* Outlook

## 🔗 Live Demo

👉 [Click here to submit a leave request](https://forms.office.com/r/3Lt8mWCH5u?origin=lprLink)



---

## ⚙️ System Workflow

### 🟦 Step 1: Leave Request Form

Users fill in their leave details such as name, email, leave type, dates, and reason.

<img width="1571" height="777" alt="INPUT INFO" src="https://github.com/user-attachments/assets/e08a1167-0635-4d5f-82be-132cc7a48db5" />
<img width="1586" height="775" alt="INPUT INFO2" src="https://github.com/user-attachments/assets/f8293510-0f1d-4e67-ac17-c485cedb5fe3" />





### 🟦 Step 2: Power Automate Flow

The flow is triggered when a form is submitted. It retrieves the response and prepares it for processing.

<img width="1561" height="762" alt="Power Automate Flow" src="https://github.com/user-attachments/assets/e891ca33-3112-48e7-a138-486893075bd5" />


---

### 🟦 Step 3: SharePoint List

All leave requests are stored in SharePoint with a default status of **Pending**.

<img width="1588" height="532" alt="SharePoint List (data proof)" src="https://github.com/user-attachments/assets/ead2b375-2185-4b7c-8a13-bc53fbb95e46" />


---

### 🟦 Step 4: Approval Email

An approval request is sent to the manager to approve or reject the leave.

<img width="1555" height="581" alt="Email (approval or result)" src="https://github.com/user-attachments/assets/10d230b7-9db8-42df-919c-ebb589d956f1" />


---

### 🟦 Step 5: Final Status Update

The system updates the request status to **Approved** or **Rejected** and sends a notification to the user.

<img width="1588" height="532" alt="SharePoint List (data proof)" src="https://github.com/user-attachments/assets/2c06c858-b2b7-4ae0-bd19-125ba5f1f423" />


---

## 💡 Features

* Automated workflow
* Approval system
* Email notifications
* Status tracking

---

## 🎯 Learning Outcomes

* Built automation using Power Automate
* Integrated multiple Microsoft tools
* Simulated a real business workflow

---

## 🚀 Conclusion

This project shows how automation can improve efficiency and reduce manual processes.

---

