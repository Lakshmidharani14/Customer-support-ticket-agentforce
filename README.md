
# 🎯 Customer Support Ticket Priority Prediction and Automated Assignment System Using Agentforce

> An intelligent Salesforce-based customer support automation system that analyzes support tickets, predicts their priority, and automatically assigns appropriate support actions using Agentforce and Salesforce Flow.

---

## 📌 Project Overview

Customer support teams receive tickets with different levels of urgency. Manually identifying critical tickets can delay the support process.

Our project uses **Salesforce Agentforce** to analyze customer support tickets, determine their priority, and automate the required support actions.

The system classifies tickets into:

- 🔴 High Priority
- 🟡 Medium Priority
- 🟢 Low Priority

For high-priority tickets, the system automatically creates an urgent handling task and assigns the appropriate support level.

---

## 🎥 Demo Video

### Project Demonstration

▶️ **[Watch Project Demo](https://drive.google.com/file/d/1eqsU7dmbazjWP3n-p6nYsea4kUzr2UlK/view?usp=drivesdk)**

The demo demonstrates:

- Agentforce ticket analysis
- Priority prediction
- Automatic support assignment
- Urgent task creation
- Salesforce Flow automation

---

## ✨ Key Features

### 🤖 Agentforce Ticket Analysis

Agentforce retrieves the latest support ticket associated with the customer account and analyzes the issue description.

### 📊 Priority Prediction

The system determines ticket priority based on keywords in the issue description.

| Priority | Example Keywords |
|---|---|
| 🔴 High | urgent, not working, failure |
| 🟡 Medium | issue, slow, delay |
| 🟢 Low | Other / normal requests |

### ⚡ Automated Task Assignment

When a ticket is identified as High Priority, the system automatically creates an **Urgent Ticket Handling** task.

### 👨‍💼 Senior Support Assignment

High-priority tickets are assigned to a **Senior Support Agent** for immediate handling.

### 🔄 Salesforce Flow Automation

Salesforce Flow performs the backend processing, updates the ticket priority, creates the required task, and returns the result to Agentforce.

---

## 🛠️ Technology Stack

- ☁️ Salesforce
- 🤖 Agentforce
- 🔄 Salesforce Flow
- 🗃️ Salesforce Custom Objects
- ⚙️ Agent Actions
- 🔐 Salesforce Security & Permissions

---

## 🗂️ Salesforce Data Model

### Support Ticket Intelligence

**Custom Object:** `Support_Ticket_Intelligence__c`

Important fields include:

- Customer
- Contact
- Issue Type
- Description
- Priority Level
- Status
- Created Date
- Assigned To
- SLA Breach Risk
- Resolution Time

---

## 🔄 Workflow

The overall workflow includes:

1. User provides the Account Name
2. Agentforce retrieves the latest support ticket
3. Ticket description is analyzed
4. Priority is determined
5. High, Medium, or Low priority is identified
6. High-priority tickets trigger urgent handling
7. Senior Support Agent is assigned
8. Ticket priority is updated
9. Final result is returned through Agentforce

---

## 🤖 Agentforce Configuration

### Support Ticket Priority Analysis

The Agentforce subagent is responsible for:

- Retrieving the latest support ticket
- Reading the ticket description
- Determining ticket priority
- Triggering backend automation
- Assigning the appropriate support level
- Returning the result to the user

The **Support Ticket Intelligence** Flow is used as the backend Agent Action.

---

## 🧪 Demo Scenario

### Test Account

**Account:** Test Support Account

### Test Ticket

**Ticket:** TKT-0001

**Issue Type:** Technical

**Description:**  
Customer application is urgent and not working.

### Result

**Priority Level:** High

**Assigned To:** Senior Support Agent

**Task Created:** Urgent Ticket Handling

**Task Priority:** High

---

## 📈 Project Benefits

- ⚡ Faster identification of critical tickets
- 🤖 Reduced manual ticket prioritization
- 👨‍💼 Automated support assignment
- 🔄 Consistent ticket handling
- 📊 Improved support workflow
- 🚨 Faster response to urgent issues

---

## 👥 Team Members

### Team NM

**Team Leader**

👩‍💻 **Lakshmidharani.S**

**Team Members**

- 👩‍💻 Sushmitha H.A
- 👩‍💻 Sushmasri.R
- 👩‍💻 Srimanivoli.S

---

## 🎓 Academic Information

**Department:** Information Technology  
**Institution:** AVC College of Engineering, Mayiladuthurai

---

## 🚀 Future Enhancements

- AI-based sentiment analysis
- SLA breach prediction
- Automatic escalation for critical tickets
- Support agent performance analytics
- Multilingual ticket analysis
- AI-based resolution recommendations

---

## 📄 Project Documentation

The project documentation covers the Salesforce configuration, Agentforce setup, custom object, Flow automation, Agent Action, and ticket prioritization process.

---

## ⭐ Conclusion

The **Customer Support Ticket Priority Prediction and Automated Assignment System Using Agentforce** demonstrates how Salesforce Agentforce and Flow automation can be combined to intelligently prioritize customer support tickets and automate support actions.

The system helps reduce manual effort, improve response time, and ensure that critical customer issues receive immediate attention.

---

## 🙏 Thank You

**Team NM**  
**AVC College of Engineering, Mayiladuthurai**
