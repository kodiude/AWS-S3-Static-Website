 # 🌐 AWS S3 Static Portfolio Website  

**Author:** Kodi Ude  
**Live Demo:** [https://kodi-portfolio-site.s3-website-us-west-1.amazonaws.com](https://kodi-portfolio-site.s3-website-us-west-1.amazonaws.com)  

---

## 📖 Overview  
This project demonstrates how to host a **static website on AWS** using **Amazon S3** and **CloudFront**.  
The site serves as my personal portfolio — showcasing my background, skills, and AWS cloud projects.  

This project is part of my hands-on AWS learning journey, focused on building free-tier, portfolio-ready cloud solutions.

---

## 🧰 AWS Services Used  
- **Amazon S3** – static website hosting  
- **AWS IAM** – access control and permissions  
- **AWS CloudFront** *(optional)* – global content delivery network  
- **AWS Route 53** *(optional)* – custom domain setup  

---

## 🧱 Architecture  

```text
Browser → AWS CloudFront (optional) → Amazon S3 → Website Files (HTML, CSS, JS)


