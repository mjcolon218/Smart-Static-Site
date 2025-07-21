# 🌐 Smart Static Site

A globally distributed, cost-effective, and secure static website hosted on AWS using **Amazon S3**, **CloudFront**, and **Route 53**.

---

## 📌 Project Overview

This project demonstrates how to host a static website with global reach, high availability, and HTTPS support using core AWS services. Ideal for personal portfolios, marketing pages, or lightweight web apps.

---

## 🧠 Key AWS Concepts Covered

- ✅ S3 Static Website Hosting
- ✅ CloudFront Content Delivery Network
- ✅ Route 53 DNS Management
- ✅ IAM & Bucket Policies
- ✅ SSL/TLS via AWS Certificate Manager (ACM)
- ✅ (Optional) CloudFront Access Logs + Athena

---

## 🧰 Architecture Diagram

```plaintext
 User (Browser)
      |
      v
+-------------+
|  Route 53   |  <-- Domain Routing (yourdomain.com)
+-------------+
      |
      v
+-------------+
| CloudFront  |  <-- Global CDN + HTTPS
+-------------+
      |
      v
+-------------+
|    S3       |  <-- Static Website Hosting (HTML/CSS/JS)
+-------------+
