# Wallarm Solutions Engineer Technical Evaluation

## 📌 Overview

Welcome to the **Wallarm Solutions Engineer Technical Evaluation**. This exercise is designed to assess your ability to deploy and configure Wallarm's filtering nodes using a deployment method of your choice, troubleshoot any issues encountered, and document your process effectively. Additionally, we will evaluate your ability to leverage our official documentation to complete the task.

---

## 🎯 Objectives

By the end of this evaluation, you should be able to:

✅ Deploy a Wallarm filtering node using a supported method of your choice.  
✅ Configure a backend origin to receive test traffic. (httpbin.org is also acceptable)  
✅ Use the **GoTestWAF** attack simulation tool to generate traffic.  
✅ Document the deployment and troubleshooting process.  
✅ Demonstrate proficiency in using **Wallarm's official documentation**.  

---

## 📂 Prerequisites

Before you begin, ensure you have access to:

- A **cloud or desktop environment** that supports one of Wallarm’s [deployment methods](https://docs.wallarm.com/installation/supported-deployment-options/) (**Kubernetes, Docker, VM, etc.**).
- A **backend application** or API endpoint to receive test traffic.
- **GoTestWAF**: [GitHub Repository](https://github.com/wallarm/gotestwaf)
- **Wallarm official documentation**: [Documentation Portal](https://docs.wallarm.com/)

---

## 🚀 Task Breakdown

### 1️⃣ Deploy a Wallarm Filtering Node

🔹 Choose a [deployment method](https://docs.wallarm.com/installation/supported-deployment-options/) (**e.g., Docker, Kubernetes, AWS, etc.**).  
🔹 Follow the [**official Wallarm documentation**](https://docs.wallarm.com/) to install and configure the filtering node.  
🔹 Verify that the filtering node is properly deployed and running.  

### 2️⃣ Set Up a Backend Origin

🔹 Configure a simple **backend API or web application** to receive traffic.  
🔹 Ensure the backend is **reachable from the filtering node**.  

### 3️⃣ Generate Traffic Using GoTestWAF

🔹 Install and configure **GoTestWAF**.  
🔹 Send attack simulation traffic through the **Wallarm filtering node**.  
🔹 Analyze the results and confirm that attacks are being detected.  

### 4️⃣ Document Your Process

📝 Provide an **overview summary** of your deployment and why you chose it.  
🛠️ Document any **issues encountered and how you resolved them**.  
📸 Include **relevant logs, screenshots, or outputs** where applicable.  

---

## ✅ Evaluation Criteria

Your submission will be evaluated based on:

📌 **Completeness**: Were all required tasks completed?  
📌 **Clarity**: Is the documentation clear and well-structured?  
📌 **Troubleshooting**: How well did you document and resolve any issues?  
📌 **Understanding of the Product**: Did you correctly set up and use the Wallarm filtering node?  
📌 **Use of Official Documentation**: Did you successfully leverage Wallarm's official resources?  

---

## 📬 Submission

Once you have completed the evaluation, submit the following:

📂 Fork this **GitHub repo** and use it as the repository for your documentation, configuration files, and any relevant logs or screenshots.  
📜 A **README file** summarizing your process and key findings.  
📜 A **HIGH Level Diargram** that illustrates what you built and how traffic is flowing.  

---

## ℹ️ Additional Notes

💡 You are encouraged to **ask questions and leverage Wallarm's documentation**.  
📖 The ability to **document your troubleshooting steps** is just as important as the final deployment.  

🚀 **Good luck, and we look forward to your submission!** 🎉
