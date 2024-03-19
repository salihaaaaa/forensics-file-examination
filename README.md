# Computer Forensic Lab: File Examination

This repository contains documentation for a computer forensics lab exercise focused on examining files using various forensic processes.

## Introduction 
In this lab, investigator examines three different files to gather evidence relevant to the investigation. The processes used involve file recovery, text extraction, and file type manipulation to extract meaningful information from the files.

### Investigator's Processes

#### JimmyJungle.doc
- **Description:** The suspect deleted the file, but it was recovered using FTK Forensic.
- **Process:** The investigator successfully recovered the "JimmyJungle.doc" file, which the suspect had deleted. The recovery process involved using FTK Forensic.
- **Findings:** Upon examining the contents of the file, the investigator found information such as "Joe Jacobs Supplier" and an address.

- ![Screenshot of Step 1](https://github.com/salihaaaaa/forensics-file-examination/blob/main/jimmyjungle.PNG)

#### Coverpage.jpgc
- **Description:** Suspect change the filetype into jpgc, making the computer unable to read the file. The investigator accessed the file and extracted information.
- **Process:** To examine the "Coverpage.jpgc" file, the investigator opened the file and viewed it in filtered text format.
- **Findings:** This revealed a piece of information: `password=goodtimes`.

- ![Screenshot of Step 1](https://github.com/salihaaaaa/forensics-file-examination/blob/main/coverpage.PNG)
- ![Screenshot of Step 1](https://github.com/salihaaaaa/forensics-file-examination/blob/main/coverpagejpg.PNG)

#### SCHEDU~1.EXE
- **Description:** Suspect change the filetype into SCHEDU~1.EXE. The original filetype is zip. And suspect also add password for file encryption. The investigator manipulated the file and extracted relevant data.
- **Process:** The "SCHEDU~1.EXE" file was exported, and its file type was changed to zip. After changing the file type, the investigator extracted its contents using password obtain from the "Coverpage.jpg" file (**goodtimes**).
- **Findings:** The extracted file, "Scheduled visit.xls", contains information about Joe Jacob's visit to school.

- ![Screenshot of Step 1](https://github.com/salihaaaaa/forensics-file-examination/blob/main/schedu~1-zip.PNG)
- ![Screenshot of Step 1](https://github.com/salihaaaaa/forensics-file-examination/blob/main/schedulevisit.PNG)

## Conclusion
Through a combination of file recovery, examination, and extraction techniques, valuable information was retrieved from the suspect's files.

