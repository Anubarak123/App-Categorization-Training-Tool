# CS633 A1 - Interactive Text Classification System
 https://github.com/Anubarak123/Quick-Quiz-Drag-and-Drop-Software-Categorization#cs633-a1---interactive-text-classification-system
🚀 Architecture & Infrastructure (Module 1 Baseline Verified)
 https://github.com/Anubarak123/Quick-Quiz-Drag-and-Drop-Software-Categorization#-architecture--infrastructure-module-1-baseline-verified
Senior Developer / System Architect: Jiankai (Anubarak123)
Core Technology Stack: Python 3.10 (Flask Framework) + MongoDB Atlas (Cloud Persistent Instance)
Production Deployment: Render Web Services (Environment Variable Injection)
Note: Google Colab is only used for batch data import to MongoDB, and is NOT the online web service backend.
> M1-09: Establish responsive text classification web UI template (M1 Base Prototype), contains 2 frontend pages (student quiz page + instructor edit management page).

📁 Engineering Audit Trails & Traceability
 https://github.com/Anubarak123/Quick-Quiz-Drag-and-Drop-Software-Categorization#-engineering-audit-trails--traceability
M1-08: Initialize secure GitHub infrastructure (Owner: Anubarak123 - Zero Hardcoded Credentials)
M1-09: Establish responsive text classification web UI template (M1 Base Prototype), contains 2 frontend pages (student quiz page + instructor edit management page).
M1-10: Connect and white-list remote MongoDB Atlas cloud integration (Dynamic configuration verified)
M1-11: Containerize and replicate architecture deployment mapping in Google Colab (for data import purpose only)

💡 User Stories (Aligned Custom Text & Label Schema)
 https://github.com/Anubarak123/Quick-Quiz-Drag-and-Drop-Software-Categorization#-user-stories-aligned-custom-text--label-schema
User Story 1 (Instructor Domain): As an instructor, I want to store custom text elements (e.g., "Steam", "Zoom") and their correct functional target categories (e.g., "Game", "Communication") into MongoDB so that sorting templates load dynamically. The instructor can add, delete and modify texts and categories directly on the webpage without manually operating Mongo.
User Story 2 (Student Domain): As a student, I want an interactive Drag-and-Drop web interface to sort application terms into matching functional zones so that my score is instantly calculated, validated, and persisted safely in the cloud.

Security Notice: All sensitive production credentials and cluster addresses are completely externalized from the source code via os.environ mapping to enforce zero credential leakage.
