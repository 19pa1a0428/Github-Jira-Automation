# 🚀 GitHub & Jira Automation using Flask  

Welcome to my **GitHub & Jira Automation** project! 🎉 This project automates the process of creating Jira tickets whenever a specific comment is made on a GitHub issue. The integration is powered by **Flask**, **GitHub Webhooks**, and **Jira API**, and it's deployed on an **AWS EC2 instance**.  

## 🔥 How It Works?  

1. A **Flask application** is created to handle incoming requests.  
2. A **GitHub Webhook** is configured to listen for comments on issues in a repository.  
3. Whenever someone comments `"/jira"` on a **GitHub issue**, GitHub sends the issue details in **JSON format** to the Flask API.  
4. The Flask application extracts the relevant data from the JSON payload.  
5. The Flask app then makes a **POST request** to the **Jira API** to create a new Jira ticket with the extracted details.  
6. The newly created Jira ticket gets added to the specified **Jira backlog** or project.  

### 📝 Example Scenario:  

1️⃣ A user goes to a **GitHub issue** and adds a comment:  

/jira This is a bug that needs to be fixed ASAP!

2️⃣ GitHub Webhook triggers and sends issue details to the Flask app running on **AWS EC2**.  
3️⃣ Flask processes the data and calls the **Jira API** to create a new Jira ticket.  
4️⃣ The issue gets added to the Jira project, allowing the team to track and manage it efficiently!  

---

## 🛠 Technologies Used  

- **Python** 🐍  
- **Flask** 🌐  
- **GitHub Webhooks** 🔗  
- **Jira API** 📝  
- **AWS EC2** ☁️  

## 🚀 Deployment  

1. **Host the Flask app** on an **AWS EC2** instance.  
2. **Set up GitHub Webhooks** to send data to the Flask API.  
3. Ensure the server is running and accessible over the internet.  
4. Test by commenting `"/jira"` on any GitHub issue!  

## 🙏 Special Thanks  

A huge **THANK YOU** ❤️ to **Abhishek Veeramalla** for his **amazing** YouTube playlist on **"Python for DevOps"**. His tutorials helped me build this project! 🎯  

📌 *Check out his playlist here:* [Python for DevOps - Abhishek Veeramalla](https://youtu.be/YVjXwyJlHgg?si=LZ1YmxXMXh4xdMxo)  

---

Hope you find this useful! Feel free to ⭐ **Star** this repo and contribute! 🚀✨  
