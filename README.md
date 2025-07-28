# Automated Optical Character Recognition for Stroke Data

##### This project was completed during my internship at The Florey Institute - Australian Stroke Organization
## Project Overview

This project focuses on automating the manual process of handling stroke patient data for the **Australian Stroke Organization**.

The organization receives stroke patient follow-up data from various hospitals across Australia. After a patient is discharged, a follow-up form is sent—mostly via **postal mail**—which patients fill out by hand and return. Some patients also return the filled forms via email after completing them online. As a result, the organization receives a combination of **handwritten and digitally filled forms**.

Previously, staff members manually read each form and entered the data into an AWS database. This process was **time-consuming, repetitive**, and **prone to human error**.

To address these challenges, this project aimed to build an **automated pipeline** using AWS services to extract data from these forms through **Optical Character Recognition (OCR)**. Since the majority of the forms were handwritten, the project had to overcome several challenges related to extraction accuracy.

We explored and compared two OCR-based approaches using:
- **AWS Textract** – effective for printed and scanned text
- **AWS Bedrock** – used for handwritten form extraction via foundation models

Both methods offered different strengths and weaknesses depending on form quality and handwriting clarity.

> **Note:** The data used in this project includes real patient information and is therefore **not publicly available**. For the same reason, the full source code is also not included in this repository. This repo focuses on explaining the architecture, decision-making process, and workflow used to carry out the automation.

---

## Tools & Technologies Used
- Python
- AWS Textract
- AWS Bedrock
- Amazon S3
- AWS Lambda
- AWS IAM
- CloudWatch (for monitoring and logging)

---

## Acknowledgement

This project was completed as part of an internship, in collaboration with the **Australian Stroke Organization**.
