# 🍴 AI-Powered Restaurant Assistant & Order Automation

[![Tools](https://img.shields.io/badge/Tools-Botpress%20%7C%20Make%20%7C%20Google%20Sheets-blue)](#)
[![Status](https://img.shields.io/badge/Status-90%25%20Complete-green)](#)

A comprehensive AI automation solution designed for the food and beverage industry. This project streamlines 24/7 customer service, real-time digital ordering, and delivery logistics by integrating conversational AI with automated data pipelines.

---

## 📽️ System Demonstrations
Below are two high-speed demos showcasing the platform's core functionalities:

1. **User Interface & NLP:** A look at how the AI handles menu inquiries, identifies customer intent, and processes orders through natural conversation.
  <img width="506" height="962" alt="PantallazoBotpress" src="https://github.com/user-attachments/assets/2e998016-cab8-4b6f-a6b2-2f0216d23e15" />

2. **Backend & Data Pipeline:** A technical demonstration of the real-time synchronization between the Chatbot, Webhooks (Make.com), and the delivery database (Google Sheets).
 <img width="482" height="908" alt="image" src="https://github.com/user-attachments/assets/ad4f3c2c-3cc0-4ae9-b88e-99dc7e363374" />

---

## 🛠️ Technical Architecture
* **Conversational Engine:** [Botpress](https://botpress.com/) (NLP & Workflow Management).
* **Automation Orchestrator:** [Make.com](https://www.make.com/) for API and data flow handling.
* **Database:** Google Sheets API for order logging and logistics tracking.
* **Logic:** Custom JavaScript snippets for dynamic price calculation and data validation.

---

## 🚀 Key Features
* **24/7 Automated Support:** Instant response to FAQs, location details, and business hours.
* **End-to-End Ordering:** Seamless transition from greeting to checkout without human intervention.
* **Delivery Logistics Integration:** Automatic data push to delivery teams, reducing manual entry errors.
* **Scalable Knowledge Base:** Easy-to-update menu and business rules.

---

## 📁 Repository Contents
> [!IMPORTANT]  
> **Language Note:** While the documentation is in English, the **exported bot files, Make scenarios, and the Knowledge Base are in Spanish**, as the implementation was developed for the Latin American market.

* **`restaurant-bot-template.bpz`**: The full chatbot export file for Botpress Cloud.
* **`01-Order-Entry-Webhook.blueprint.json`**: Make.com scenario for incoming order reception.
* **`02-Payment-Validation-Service.blueprint.json`**: Make.com scenario for payment verification logic.
* **`03-Delivery-Dispatch-Logic.blueprint.json`**: Make.com scenario for delivery team notification.
* **`Restaurant_Operations_Sheet.xlsx`**: Excel template for order management and logistics.
* **`knowledge-base-sanitized.docx`**: The structured data used by the AI to learn about the menu and business rules.

---

## 🔧 Setup Instructions
1. Import the **`restaurant-bot-template.bpz`** file into your **Botpress Cloud** Studio.
2. Import the three **`.blueprint.json`** files into your **Make.com** account to replicate the automation logic.
3. Use **`Restaurant_Operations_Sheet.xlsx`** as your database in Google Sheets.
4. Review the **`knowledge-base-sanitized.docx`** file to customize your restaurant's specific menu and policies.
5. Update the Webhook URLs in Botpress to match your new Make.com endpoints.

---

## 👤 Professional Background
I am a **Maintenance Engineer** currently specializing in **Data Science and AI Engineering**. This project serves as a showcase of my ability to design and implement automated systems that optimize operational efficiency through data-driven technology.
---

## ⚖️ License
This project is for portfolio and demonstration purposes. All business logic and sanitization have been applied to protect privacy.
