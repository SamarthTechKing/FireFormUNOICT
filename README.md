# 🔥 FireForm UNOICT — Report Once, File Everywhere

## 📌 Overview

FireForm is an open-source, technology-agnostic system designed to reduce administrative overhead for first responders. It enables emergency response agencies to eliminate redundant paperwork by allowing incidents to be reported once and automatically generating all required agency-specific reports.

This project implements a prototype interface for the FireForm system, demonstrating a complete workflow from incident input to multi-agency report generation.

---

## 🚨 Problem Statement

First responders are required to document a single incident across multiple agencies such as:

- Fire Departments
- Law Enforcement
- Emergency Medical Services
- State & Local Authorities

Each agency uses different formats and forms, forcing responders to repeatedly enter the same data. This results in:

- Significant time loss
- Increased fatigue
- Higher chances of reporting errors
- Reduced operational readiness

---

## 💡 Solution — FireForm

FireForm introduces a **“Report Once, File Everywhere”** workflow:

- A responder provides a **single incident description** (via text or voice)
- The system processes this input using **locally deployed AI models**
- Extracts structured data into a standardized format (JSON)
- Automatically maps and fills multiple agency-specific report templates

All processing is designed to run **locally**, ensuring **data privacy and security**.

---

## 🚀 Key Features

### 📝 Unified Incident Input

- Natural language input (text + voice)
- Simple, user-friendly interface for rapid reporting

### 🤖 AI-Based Data Extraction (Simulated UI)

- Converts unstructured descriptions into structured fields:
  - Date & Time
  - Location
  - Incident Type
  - Reporting Person
  - Units Involved

### 🔍 Review & Validation Layer

- Allows users to verify and correct extracted data
- Highlights missing or uncertain fields

### 📤 Multi-Agency Report Generation

- Automatically prepares reports for multiple agencies
- Supports different formats and requirements
- Download-ready outputs (PDF simulation)

### 🗂️ Template Management System

- Upload and manage agency-specific templates
- Map fields between structured data and form inputs
- Enable/disable templates dynamically

### 🕓 Incident History Tracking

- Maintains logs of previously filed reports
- Provides quick access to past incidents

### 🔐 Privacy-Focused Design

- Designed for **local deployment**
- Ensures no sensitive incident data leaves the system

---

## 🧠 System Workflow

1. **Input** → User describes incident (text/voice)
2. **Processing** → AI extracts structured data
3. **Review** → User validates and edits fields
4. **Mapping** → Data mapped to agency templates
5. **Output** → Auto-filled reports generated

---

## 🛠️ Tech Stack

- HTML5
- CSS3 (Custom UI system)
- JavaScript (Vanilla JS)
- Web Speech API (voice input simulation)

---

## 🌍 Impact

FireForm significantly reduces administrative burden by:

- Saving hours of repetitive documentation work
- Improving reporting accuracy and consistency
- Allowing responders to focus on emergency response
- Enhancing overall operational efficiency and safety

---

## 🎯 Expected Future Enhancements

- Integration with real LLMs (e.g., Mistral via Ollama)
- Automated PDF form filling
- Backend integration for persistent storage
- Schema validation and error handling
- Multi-user and role-based access system

---

## 👨‍💻 Author

Samarth Sharma

---

## 📄 References

Project concept inspired by FireForm Digital Public Good initiative
