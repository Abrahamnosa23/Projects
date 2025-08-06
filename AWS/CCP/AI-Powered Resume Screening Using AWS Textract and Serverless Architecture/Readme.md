
# Resume Screener Project

**AI-Powered Resume Screening Using AWS Textract and Serverless Architecture**

---

## Project Overview

This project is a fully serverless resume screening tool built with AWS services. It automatically extracts text from resumes, checks for key job-related skills, scores them, stores results in a database, and notifies the recruiter—without any manual intervention.

It is designed especially for **Startups, SMEs, NGOs**, or any organization that cannot afford expensive **ATS** platforms.

---

## Key Features

- Text extraction using **Amazon Textract**
- Serverless processing with **AWS Lambda**
- Resume storage in **Amazon S3**
- Keyword-based scoring logic (e.g., "AWS", "Python", "Certified")
- Data storage in **Amazon DynamoDB**
- Notifications via **Amazon SNS**
- Structured resume metadata output (JSON)

---

## Why This Project?

Recruiters spend hours manually scanning resumes. Existing ATS systems are expensive and often inaccessible to smaller companies.

This project provides:
- A low-cost, scalable solution
- A fair and standardized way to screen resumes
- Easy integration with existing hiring processes

---

## Tech Stack

| Service        | Purpose                             |
|----------------|-------------------------------------|
| AWS S3         | Resume upload and storage           |
| AWS Textract   | Resume text extraction              |
| AWS Lambda     | Orchestrate the workflow            |
| AWS DynamoDB   | Store scores and metadata           |
| AWS SNS        | Send real-time alerts               |
| Python + Boto3 | Backend logic & AWS SDK             |

---

## System Architecture

![Architecture Diagram](https://github.com/Abrahamnosa23/Projects/blob/main/AWS/CCP/AI-Powered%20Resume%20Screening%20Using%20AWS%20Textract%20and%20Serverless%20Architecture/Uploads/Architecture%20Diagram/AI-Powered%20Resume%20Screener%20Using%20AWS%20Textract.png)

---

## 📝 Sample Output

```json
{
  "processed_file": "uploads/resume.pdf",
  "score": 6,
  "keywords_found": ["AWS", "Python", "Cloud", "Certified", "Architecture", "Security"]
}
```
---

## Opportunities for Improvement

- Use NLP for semantic keyword matching
- Add support for multiple job roles and custom keyword lists
- Build a web interface to view scores and filter resumes
- Integrate with email or frontend resume upload form

---

## Impact

This tool enables fairer and faster hiring, especially in regions and companies where:

- ATS platforms are unaffordable
- HR teams are overwhelmed
- Automation can create real time and cost savings

---
## Documentation
[Download full project documentation (PDF)](https://github.com/Abrahamnosa23/Projects/blob/main/AWS/CCP/AI-Powered%20Resume%20Screening%20Using%20AWS%20Textract%20and%20Serverless%20Architecture/Uploads/Project%20Documentation/AI-Powered%20Resume%20Screener%20Project%20Documentation.docx)

---

## Author
Developed by Abraham Aigbokhan, Cloud and DevOps Engineer passionate about using technology to solve real-world problems.

[Let’s connect on LinkedIn](https://www.linkedin.com/in/abraham-aigbokhan-3abb28214)

