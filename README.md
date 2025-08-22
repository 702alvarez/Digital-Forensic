# Forensic Investigation (Autopsy Case Study)

---

## 📌 Project Overview
This project demonstrates a hands-on forensic investigation using **Autopsy** to analyze disk images, recover deleted data, and identify Acceptable Use Policy (AUP) and Non-Disclosure Agreement (NDA) violations.  

---

## 🎯 Objectives
1. Create a forensic case in Autopsy.  
2. Examine evidence from carved/unallocated data and deleted files.  
3. Extract, preserve, and report relevant evidence.  
4. Identify policy violations and present findings.  

---

## 🛠️ Tools Used
- **Autopsy** – case creation, evidence ingest, and artifact analysis  
- **FTK Imager** – imaging and preservation (supporting tool)  
- **Belkasoft RAM Capture** – volatile data capture (supporting tool)  
- **Paraben E3:UNIVERSAL** – additional analysis capability  

---

## 🔍 Investigation Process

### **Objective 1 – Case Setup**
- Opened **Autopsy** and created a new case (`J.Smith`).  
- Set base directory: `C:\Users\Labusers\Desktop\EvidanceFiles\`.  
- Entered **Case Number:** `290885652`, **Examiner:** Anthony Alvarez.  
- Added evidence source: disk image (`Jsmith_Q1.001`).  
- Used default ingest configuration to initialize case.  

---

### **Objective 2 – Evidence Examination**
- Selected **data source**: `Jsmith_Q1.001_1 Host`.  
- Analyzed **carved/unallocated data**.  
- Reviewed **deleted files** under File Views.  
- Examined **metadata artifacts** for evidence context.  
- Extracted key evidence to a secure directory for reporting.  

---

### **Objective 3 – Findings**
- **Policy Violations Identified**:  
  - Multiple confidential PDFs marked *“Do Not Disclose”*.  
  - Evidence of proprietary drilling information found in deleted images.  
- **Suspicious Behavior**:  
  - Files related to concealing activity and anonymous bitcoin payments.  
- **Conclusion**:  
  John Smith violated both **AUP** and **NDA** by accessing and attempting to conceal proprietary data.  

---

## 📂 Screenshots (Demonstration)
## Step 1 – Case Setup
Created a new case in Autopsy, assigned examiner details, and loaded the disk image.
<img width="588" height="303" alt="image" src="https://github.com/user-attachments/assets/39a05b06-aef6-4657-a7c9-202babe8187e" />
## Step 2 – Evidence Ingestion
Ingested the image with default modules to process deleted files, carved data, and artifacts.
<img width="591" height="550" alt="image" src="https://github.com/user-attachments/assets/7094e065-d6fa-4c41-8a07-62d456f8e8bd" />
## Step 3 – Analyzing Deleted & Carved Data
Reviewed deleted files and examined unallocated space to uncover hidden remnants.
<img width="594" height="520" alt="image" src="https://github.com/user-attachments/assets/bb9d805d-ab4d-44ff-ad92-f9b1a3f2b68b" />
## Step 4 – Metadata & Artifacts
Inspected metadata and activity logs to build a timeline of the user’s actions.
<img width="594" height="564" alt="image" src="https://github.com/user-attachments/assets/18eb8fa5-8b5f-4821-b089-335dd49a3f20" />
## Step 5 – Findings
- Recovered confidential PDFs marked “Do Not Disclose.”
- Found deleted drilling images containing proprietary data.
- Detected user research into Bitcoin and file hiding.
Conclusion: The investigation confirmed AUP and NDA violations by the user, demonstrating insider
threat detection through digital forensics
<img width="594" height="444" alt="image" src="https://github.com/user-attachments/assets/343d018e-cf26-43df-b0cd-776c8902027e" />














---

## 📌 Skills Demonstrated
- Case creation and evidence ingestion in Autopsy  
- File carving and recovery of deleted artifacts  
- Metadata and artifact analysis  
- Evidence extraction and chain of custody preservation  
- Reporting and presentation of policy violations  

---

## ✅ Conclusion
This investigation highlights real-world application of forensic methodologies using Autopsy, showing my ability to detect, extract, and report on digital evidence tied to insider threats and policy violations.  
