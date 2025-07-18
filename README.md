🌐 Highly Available Medical Website using Azure VM Scale Sets 🚑

A robust and responsive medical website deployed on Microsoft Azure, designed to maintain high availability and handle fluctuating traffic loads with Virtual Machine Scale Sets (VMSS) and Azure Load Balancer. This project demonstrates how cloud infrastructure can be leveraged to ensure uninterrupted access to critical healthcare information and services.

🚀 Project Overview
This project showcases a cloud-native web application that adapts to user demand in real-time. We built a responsive medical platform hosted on virtual machines (VMs) using Azure VM Scale Sets. By integrating Azure Load Balancer, the website smartly distributes traffic to maintain performance—even during high demand.

Key Objective:

To control and manage heavy web traffic using cloud scalability, ensuring uninterrupted delivery of healthcare services online.

🧠 Key Features
📱 Responsive Medical Website
Built with HTML, CSS, and JavaScript – accessible and optimized for all screen sizes.

📈 VM Scale Sets (VMSS)
Automatically scales VMs up or down based on user traffic, ensuring zero downtime.

⚖️ Azure Load Balancer
Evenly distributes incoming traffic across virtual machines, improving performance and fault tolerance.

💡 High Availability & Auto Recovery
The website stays online even during VM failures or high peak usage.

💰 Cost-Efficient Scalability
Dynamically scales resources as per demand – pay only for what you use.

☁️ Cloud Architecture
text
Copy
Edit
User Request
     │
     ▼
[Azure Load Balancer]
     │
     ▼
[Virtual Machine Scale Set]
     ├─ VM 1 (Web App)
     ├─ VM 2 (Web App)
     └─ VM N (Web App)
🧰 Tech Stack
Layer	Technologies
Frontend	HTML, CSS, JavaScript
Cloud Provider	Microsoft Azure
Infrastructure	Azure VM Scale Sets, Load Balancer

🎯 Outcomes
✅ Seamless and reliable access to healthcare information.

🚀 Improved website uptime, speed, and resilience.

🔄 Autoscaling infrastructure based on live traffic patterns.

🧘‍♀️ Stress-free traffic handling with intelligent load balancing.

📍 Why This Project?
In the healthcare domain, uptime and accessibility are mission-critical. Our goal was to design an infrastructure that automatically scales and balances traffic to ensure constant access to medical information—no matter the traffic volume.

“We don’t just host a website—we ensure it's always available when needed the most.”

🛠️ Future Improvements
Integrate Azure App Gateway for SSL termination.

Add CI/CD pipeline with GitHub Actions or Azure DevOps.

Connect to a backend database for storing medical records securely.
