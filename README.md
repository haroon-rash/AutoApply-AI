# AutoApply AI 🚀

AI-powered job outreach automation platform built using **Java 17, Spring Boot 3, PostgreSQL, and AI APIs**.

AutoApply AI automates job application outreach by identifying HR contacts using AI-powered search and sending targeted email campaigns. It reduces manual effort while improving outreach accuracy.

---

## Overview

AutoApply AI is a production-grade backend platform that streamlines job application workflows.  

**Key objectives:**
- Automate HR contact discovery using AI (Google Gemini & DeepSeek).  
- Manage large-scale email campaigns with personalized messages and attachments.  
- Secure backend using Spring Security + JWT.  
- Scalable architecture with Docker containerization.  

---

## Features

- AI-powered HR contact discovery and extraction  
- Automated job application email campaigns  
- Resume & document parsing (PDF, DOCX, Excel)  
- Campaign tracking and logging  
- Secure authentication & role-based access control  
- Containerized deployment for consistent environments  

---

## System Architecture

![System Architecture](images/architecture.png)

**Architecture Flow:**  

`User → Frontend Dashboard → Spring Boot Backend → AI Search (Gemini / DeepSeek) → PostgreSQL → Email Service`

---

## Screenshots

### Dashboard
![Dashboard](images/dashboard.png)

### HR Contact Discovery
![AI Search](images/ai-search.png)

### Email Campaign Management
![Campaign Management](images/campaign.png)

---

## Tech Stack

**Backend:** Java 17, Spring Boot 3, Spring Security, Spring Data JPA  
**AI Integration:** Google Gemini API, DeepSeek AI  
**Database:** PostgreSQL  
**Tools & Utilities:** Docker, Maven, JWT, Apache POI, PDFBox  
**Frontend:** Vanilla JavaScript, HTML5, CSS3  

---

## Installation

1. Clone the repository:  
```bash
git clone https://github.com/haroon-rash/autoapply-ai.git
