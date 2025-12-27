# 📦 AWS S3 Lifecycle Rule Project

This project demonstrates how to configure **Amazon S3 Lifecycle Rules** to automate storage management.  
Lifecycle rules help move objects to cheaper storage classes and delete them automatically after a defined time — saving cost and improving efficiency.

---

## 📌 Project Overview

In this project, you will see:

✔ Creation of an S3 bucket  
✔ Uploading an object  
✔ Setting up a lifecycle rule to:
- Transition objects to **Standard Infrequent Access (IA)** after **30 days**
- Expire (delete) objects after **365 days**
- Cleanup incomplete uploads

This is a real hands-on demonstration using the AWS Console.

---

## 📸 Screenshots

### 1. Bucket Created
Shows the S3 bucket we created for this project.


---

### 2. File Uploaded
Uploaded a sample file to the bucket.


---

### 3. Lifecycle Rule Scope
Defining the rule scope and name.


---

### 4. Lifecycle Actions Selected
Transition and expiration actions are selected here.


---

### 5. Rule Created and Active
The final lifecycle rule is created and enabled.


---

## 🧠 What You Learned

By completing this project:

- You learned how to create an S3 bucket in AWS
- You understand how to upload objects
- You applied lifecycle configuration to automate data transitions
- You improved your cloud cost optimization skills

This project is great for building real-world AWS experience!

---

## 📦 Repository Structure

aws-s3-lifecycle-rule/
├── screenshots/
│ ├── bucket-created.png
│ ├── file-upload.png
│ ├── lifecycle-scope.png
│ ├── lifecycle-actions.png
│ ├── rule-created.png
├── README.md


---

## 🚀 Next Steps

If you want to extend this project, you could:

✔ Add versioning lifecycle rules  
✔ Implement lifecycle using AWS CLI / Terraform  
✔ Connect this bucket to CloudFront for static hosting

---

## 📝 Notes

This demo is safe and inexpensive — S3 storage costs are minimal and no compute instances were used.

---

⭐ *Feel free to use this in your LinkedIn portfolio or resume!*
