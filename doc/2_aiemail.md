# n8n Workflow – Gemini AI Chat + Email Trigger

This document describes an n8n workflow that integrates **Google Gemini Chat Model**, an **AI Agent**, and two separate triggers:

1. **Manual Execution Trigger → Send Email**
2. **Chat Message Trigger → AI Chat Response**

---

## 📌 Workflow Overview

The workflow is divided into two functional sections.

---

## 1. Manual Trigger → Send Email

This portion runs when the user manually clicks **“Execute workflow”** inside n8n.

### **Nodes**
- **When clicking 'Execute workflow'**  
  Manual test trigger.
- **Send a message (Gmail)**  
  Sends an email using the configured Gmail account.

### **Flow Structure**
