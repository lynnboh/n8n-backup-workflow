# n8n-backup-workflow
This is to backup the N8N workflows and credentials

## 📜 Overview  
This repository contains an n8n workflow designed to automate the backup of your n8n workflows and data. It can help you regularly export and store workflows, ensuring you always have a backup version in case of accidental loss or changes.

---

## 🚀 Features  
- Automatically exports all n8n workflows at scheduled intervals  
- Saves backups locally or to cloud storage (depending on configuration)  
- Supports timestamped filenames for easy version tracking  
- Easy to customize for different backup destinations  

---

## 📂 Files included  
| File                | Description                                      |
|---------------------|--------------------------------------------------|
| `n8n-backup.json`  | The main workflow file for importing into n8n    |
| `example.env`      | (Optional) Example environment variable settings |
| `README.md`        | This file                                        |

---

## 📥 How to use  
1. Download the `n8n-backup.json` file.  
2. Open your n8n instance.  
3. Go to **Workflows > Import from file**.  
4. Select the `n8n-backup.json` file.  
5. Set up any required credentials (e.g., cloud storage, database, webhook).  
6. Adjust scheduling if needed.  
7. Test and activate!  

---

## 🛠 Setup Tips  
- Make sure to have the correct credentials (e.g., Google Drive, S3, or FTP) set up in n8n.  
- You can customize where backups are stored in the workflow settings.  
- Recommended: Schedule the workflow to run daily or weekly
