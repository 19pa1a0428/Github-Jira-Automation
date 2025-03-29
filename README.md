# 🚀 GitHub & Jira Automation using Flask  

Welcome to my **GitHub & Jira Automation** project! 🎉 This project automates the process of creating Jira tickets whenever a specific comment is made on a GitHub issue. The integration is powered by **Flask**, **GitHub Webhooks**, and **Jira API**, and it's deployed on an **AWS EC2 instance**.  

## 🔥 How It Works?  

1. A Flask application is hosted on **AWS EC2**.  
2. A GitHub webhook is set up to listen for issue comments.  
3. When a user comments `"/jira"` on a GitHub issue, GitHub sends a **JSON payload** to the Flask app.  
4. The Flask app processes this payload and creates a **Jira ticket** using the **Jira API**.  

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
