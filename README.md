# 🚗 WhatsNext Vision Motors – Salesforce CRM Project

WhatsNext Vision Motors is a pioneering force in the automotive sector, committed to revolutionizing the mobility experience through cutting-edge technology and customer-first solutions. This Salesforce CRM project is designed to streamline customer interactions, optimize vehicle order workflows, and automate dealership operations—ultimately delivering a smarter, faster, and more reliable vehicle ordering experience.

# 📌 Project Overview

The core objective of this Salesforce implementation is to enhance the customer ordering process and improve operational efficiency through intelligent automation and centralized data management. Key features include:

🔍 Auto-suggestion of nearest dealers based on customer address

🚫 Prevention of out-of-stock vehicle orders

✅ Real-time order status updates based on stock availability

🔁 Scheduled batch processing to monitor inventory and update order statuses

📧 Automated notifications for test drives and stock updates

This project leverages the power of Salesforce CRM to align with WhatsNext Vision Motors’ vision of transforming the automotive buying journey while empowering employees with a modern and efficient backend system.

# ⚙️ Create Custom Object

1: Creating Vehicle Custom Object

To manage vehicle-related data efficiently, we begin by creating a custom object called Vehicle in Salesforce.
<img width="940" height="481" alt="image" src="https://github.com/user-attachments/assets/ab58c273-be6c-4982-bec9-c14a09c530e8" />


Vehicle Object
<img width="939" height="377" alt="image" src="https://github.com/user-attachments/assets/f30a3093-6b6f-44d6-938c-30caceaca629" />


2: Create Vehicle Dealer Custom Object

To store and manage dealership information effectively, we create a custom object named Vehicle Dealer.
<img width="940" height="499" alt="image" src="https://github.com/user-attachments/assets/5af521a2-ca75-48b5-add2-1eb8bf92b731" />

3:⚙️Create Other Custom Object

<img width="940" height="355" alt="image" src="https://github.com/user-attachments/assets/cc6aca83-3fd6-4461-a4fa-52d708392f28" />

4: Custom Tabs for all Custom Objects

<img width="939" height="394" alt="image" src="https://github.com/user-attachments/assets/c60efa5e-fea9-4c8d-b454-6b84beaaa3b3" />

# Creating the Lightning App

<img width="938" height="434" alt="image" src="https://github.com/user-attachments/assets/043a7668-d795-40e0-970b-b62695674329" />

1:Adding items needed 

<img width="939" height="386" alt="image" src="https://github.com/user-attachments/assets/a7779abc-afb6-4e5c-b96e-1f2857cab01b" />

2:Adding user profile

<img width="939" height="388" alt="image" src="https://github.com/user-attachments/assets/d42c9667-ec13-4f39-9068-cde739235463" />

3:WhatNext Vision App look

<img width="941" height="441" alt="image" src="https://github.com/user-attachments/assets/ed225fcd-c5cb-4406-97f4-4ac69df374c4" />


# Fields & Relationships along with Key Fields for Each Object

A: Vehicle
<img width="939" height="427" alt="image" src="https://github.com/user-attachments/assets/6012996e-d359-4bf2-b925-29e5227614cb" />


B:Vehicle_ Dealer
<img width="941" height="416" alt="image" src="https://github.com/user-attachments/assets/c2e90721-bb9b-491c-a564-26162c2da516" />


C:Vehicle_Customer
<img width="938" height="436" alt="image" src="https://github.com/user-attachments/assets/a85c9fe3-8ed5-4e25-8f07-1bb39ed96243" />


D:Vehicle_Order
<img width="939" height="361" alt="image" src="https://github.com/user-attachments/assets/ee8c7ac2-f5cf-4261-af02-1c24a64ff145" />


E:Vehicle_Test_Drive
<img width="939" height="384" alt="image" src="https://github.com/user-attachments/assets/23feb2d2-db14-4d7f-a18a-6c5c659f1bb2" />


F:Vehicle_Service_Request
<img width="939" height="411" alt="image" src="https://github.com/user-attachments/assets/df14380d-84b0-42a0-8e8d-5ffcc07d5043" />

# Flow Creation and activation

<img width="939" height="411" alt="image" src="https://github.com/user-attachments/assets/1dff25c1-5ab0-4ef3-912d-20a665f5ecfd" />

Record-Trigger Flow Creation

<img width="939" height="391" alt="image" src="https://github.com/user-attachments/assets/78d8c88b-24d6-49d3-9698-808b5efff709" />


# Flow testing:

Successfully created vehicle test drive

<img width="939" height="392" alt="image" src="https://github.com/user-attachments/assets/2d04fa12-14e5-4dd9-a674-8b7e60fbe9d4" />

Received email for test drive remainder

<img width="941" height="403" alt="image" src="https://github.com/user-attachments/assets/7aab2510-2370-4f12-8a6b-7c50dd31092f" />


