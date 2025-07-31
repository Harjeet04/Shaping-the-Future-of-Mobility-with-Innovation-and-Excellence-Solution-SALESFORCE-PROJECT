# 🚗 WhatsNext Vision Motors – Salesforce CRM Project

WhatsNext Vision Motors is a pioneering force in the automotive sector, committed to revolutionizing the mobility experience through cutting-edge technology and customer-first solutions. This Salesforce CRM project is designed to **streamline customer interactions, optimize vehicle order workflows, and automate dealership operations**—ultimately delivering a smarter, faster, and more reliable vehicle ordering experience.

---

## 📌 Project Overview

The core objective of this Salesforce implementation is to enhance the **customer ordering process** and improve **operational efficiency** through intelligent automation and centralized data management. Key features include:

* 🔍 Auto-suggestion of nearest dealers based on customer address
* 🚫 Prevention of out-of-stock vehicle orders
* ✅ Real-time order status updates based on stock availability
* 🔁 Scheduled batch processing to monitor inventory and update order statuses
* 📧 Automated notifications for test drives and stock updates

This project leverages the power of Salesforce CRM to align with WhatsNext Vision Motors’ vision of transforming the automotive buying journey while empowering employees with a modern and efficient backend system.

---

## ⚙️ Create Custom Objects

### 1️⃣ Creating Vehicle Custom Object

We begin by creating a custom object named **Vehicle** to manage vehicle-related information such as models, variants, and stock availability.

![Vehicle Object](https://github.com/user-attachments/assets/ab58c273-be6c-4982-bec9-c14a09c530e8)

**Vehicle Object View:**

![Vehicle Object Fields](https://github.com/user-attachments/assets/f30a3093-6b6f-44d6-938c-30caceaca629)

---

### 2️⃣ Create Vehicle Dealer Custom Object

The next step involves creating the **Vehicle Dealer** object, which allows us to store and manage dealership information such as name, location, and inventory support.

![Dealer Object](https://github.com/user-attachments/assets/5af521a2-ca75-48b5-add2-1eb8bf92b731)

---

### 3️⃣ Create Other Custom Objects

Additional objects such as **Vehicle Customer**, **Vehicle Order**, **Vehicle Test Drive**, and **Vehicle Service Request** are created to capture related operations and interactions.

![Other Objects](https://github.com/user-attachments/assets/cc6aca83-3fd6-4461-a4fa-52d708392f28)

---

### 4️⃣ Add Custom Tabs for All Objects

Once the objects are created, custom tabs are added for each object to ensure easy navigation and accessibility in the Salesforce app.

![Tabs](https://github.com/user-attachments/assets/c60efa5e-fea9-4c8d-b454-6b84beaaa3b3)

---

## ⚡ Creating the Lightning App

Next, we set up a Lightning App for "WhatsNext Vision Motors" to group related objects and features under one accessible app interface.

---

### 1️⃣ Adding Items to the App

Include all custom objects and relevant standard objects to the app.

![Add Items](https://github.com/user-attachments/assets/a7779abc-afb6-4e5c-b96e-1f2857cab01b)

---

### 2️⃣ Assigning User Profiles

Assign appropriate user profiles to ensure the app is accessible to the right team members.

![Add Profiles](https://github.com/user-attachments/assets/d42c9667-ec13-4f39-9068-cde739235463)

---

### 3️⃣ Final App View

The completed Lightning App interface:

![App View](https://github.com/user-attachments/assets/ed225fcd-c5cb-4406-97f4-4ac69df374c4)

---

## 🧩 Fields & Relationships (Key Fields for Each Object)

Below are the key fields created for each custom object to capture relevant data:

### A. Vehicle

![Vehicle Fields](https://github.com/user-attachments/assets/6012996e-d359-4bf2-b925-29e5227614cb)

---

### B. Vehicle Dealer

![Dealer Fields](https://github.com/user-attachments/assets/c2e90721-bb9b-491c-a564-26162c2da516)

---

### C. Vehicle Customer

![Customer Fields](https://github.com/user-attachments/assets/a85c9fe3-8ed5-4e25-8f07-1bb39ed96243)

---

### D. Vehicle Order

![Order Fields](https://github.com/user-attachments/assets/ee8c7ac2-f5cf-4261-af02-1c24a64ff145)

---

### E. Vehicle Test Drive

![Test Drive Fields](https://github.com/user-attachments/assets/23feb2d2-db14-4d7f-a18a-6c5c659f1bb2)

---

### F. Vehicle Service Request

![Service Fields](https://github.com/user-attachments/assets/df14380d-84b0-42a0-8e8d-5ffcc07d5043)

---

## 🔄 Flow Creation and Activation

Flows are used to automate the business processes such as assigning nearest dealers and sending reminders.

### Record-Triggered Flow Creation

![Flow Builder](https://github.com/user-attachments/assets/1dff25c1-5ab0-4ef3-912d-20a665f5ecfd)
![Flow Setup](https://github.com/user-attachments/assets/78d8c88b-24d6-49d3-9698-808b5efff709)

---

## ✅ Flow Testing

We test the record-triggered flow by creating a test drive request and observing the triggered email notification.

### Test Drive Record Created

![Test Drive Created](https://github.com/user-attachments/assets/2d04fa12-14e5-4dd9-a674-8b7e60fbe9d4)

### Email Reminder Received

![Email Received](https://github.com/user-attachments/assets/7aab2510-2370-4f12-8a6b-7c50dd31092f)

---

