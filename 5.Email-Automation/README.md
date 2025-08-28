## EMAIL AUTOMATION SYSTEM (RULE-BASED FORWARDING)  

### 1. Abstract  
The Email Automation System is designed to filter and forward specific emails automatically based on subject keywords. Since students and professionals often receive a large number of emails daily, it becomes difficult to track important ones such as assignments, test notifications, or deadlines. This system solves that problem by detecting pre-defined keywords in email subjects and automatically forwarding such mails to another account as a reminder.  

---

### 2. Objectives  
- To automate the detection of important emails from a crowded inbox.  
- To forward filtered emails automatically to a designated account.  
- To reduce the chances of missing important academic or work-related updates.  
- To implement a simple, lightweight, and efficient email management solution.  

---

### 3. Methodology  
1. The system continuously monitors incoming emails.  
2. For each email received, the **subject line** is checked.  
3. If the subject contains specific keywords (e.g., *“test”*, *“assignment”*), the system marks it as important.  
4. The email is then **forwarded** to a pre-defined reminder email account.  
5. All other emails remain in the inbox without action.  

---

### 4. Tools & Technologies Used  
- **UiPath Studio / Automation Tool** – for building the workflow.  
- **Email Integration** – Gmail/Outlook for reading and forwarding emails.  
- **String Keyword Matching** – simple logic to detect important subjects.  

---

### 5. Sample Input and Output  

**Sample Input (Incoming Email):**  
- Subject: *Assignment Submission Reminder*  
- Body: "Please submit your assignment by 5 PM tomorrow."  

**System Action (Output):**  
- Forwards email to: *myreminderemail@example.com*  

**Forwarded Mail Subject:** *[Forwarded Reminder] Assignment Submission Reminder*  

---

### 6. Conclusion  
The Email Automation System provides a simple yet effective method for managing large volumes of emails. By filtering based on keywords and automatically forwarding critical messages, the system reduces manual effort and ensures that important updates are not missed.  
