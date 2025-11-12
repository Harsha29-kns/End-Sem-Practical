#  Using Autopsy to Create a Case and Import Digital Evidence

---

## **Aim**
To use **Autopsy**, a digital forensic analysis tool, to create a new forensic case, import digital evidence, examine artifacts, and generate a detailed forensic investigation report.

---

## **Procedure**

### **1. Installation**
1. Download the latest version of **Autopsy** from the official website.  
2. Install the application following the setup instructions for your operating system (Windows, Linux, or macOS).  
3. Launch Autopsy to verify successful installation.

---

### **2. Creating a New Case**
1. Open **Autopsy**.  
2. Click on **Create New Case**.  
3. Provide the following details:
   - **Case Name**
   - **Case Number**
   - **Examiner’s Name**
   - **Base Directory** (location to store case data)
4. Click **Next** to proceed to the data source configuration page.

---

### **3. Adding a Data Source**
1. Select the evidence type:
   - Disk Image / VM File (e.g., `.E01`, `.dd`)
   - Local Disk
   - Logical Files
2. Browse and select the acquired **evidence file**.  
3. Configure **Ingest Modules** such as:
   - File Type Identification  
   - Hash Lookup  
   - Keyword Search  
   - Web Artifacts  
4. Click **Next** to begin ingestion and analysis.
<img width="1716" height="903" alt="Screenshot 2025-11-12 160707" src="https://github.com/user-attachments/assets/2b77be72-8a65-41ac-b878-4c5199a2cd61" />

---

### **4. Monitoring Ingest and Overview**
1. The progress bar at the bottom shows ingestion progress.  
2. After processing completes, Autopsy lists categorized results in:
   - **File Views**
   - **Data Artifacts** (Web History, Cookies, Recent Documents, etc.)
   - **Analysis Results**
3. Navigate through these views to explore extracted artifacts.
<img width="1702" height="916" alt="Screenshot 2025-11-12 161459" src="https://github.com/user-attachments/assets/303f4517-ed07-42d4-bdb0-af2154caa047" />
<img width="1913" height="1031" alt="Screenshot 2025-11-12 163237" src="https://github.com/user-attachments/assets/ef5bcc81-7379-4459-b507-f6c4ac089353" />

---

### **5. Performing Detailed Analysis**
1. **Keyword Search:**  
   - Run custom or predefined keyword lists to identify relevant evidence.
2. **File Analysis:**  
   - Browse files under File System or File Types; preview or export files as needed.  
3. **Timeline Analysis:**  
   - Visualize system and user activities chronologically using timestamps.  
4. **Hash Analysis:**  
   - Compare file hashes with known databases (e.g., NSRL) to detect suspicious or trusted files.  
5. **Artifact Correlation:**  
   - Cross-reference artifacts (browser history, cookies, deleted files) for deeper insights.

---

### **6. Generating Reports**
1. Navigate to **Case → Generate Report**.  
2. Choose desired report format:
   - HTML
   - PDF
   - Excel
   - CSV  
3. Select report contents such as:
   - File Listings  
   - Keyword Hits  
   - Hash Set Matches  
   - Tagged Evidence  
4. Save the generated report in the case folder for documentation and submission.
   <img width="1907" height="904" alt="image" src="https://github.com/user-attachments/assets/8979d4ac-4667-4fe5-b886-05a888792aed" />


---

### **7. Closing and Archiving the Case**
1. Once the analysis is complete:
   - Save all results and reports.  
   - Click **Close Case** from the Autopsy toolbar.  
2. Backup and archive the entire case directory securely following forensic **chain-of-custody** standards.  
3. Store generated reports, evidence hashes, and extracted artifacts for future verification.

---

## **Result**
Successfully created a forensic case using **Autopsy**, imported and analyzed digital evidence, performed file system, keyword, timeline, and hash analysis, and generated a comprehensive forensic report.  


---
