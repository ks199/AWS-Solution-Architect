# 🌍 AWS Global Infrastructure & Core Services Notes

---

### ⚡ What is Latency?
Latency is the **time taken for data to travel from source to destination**.

📌 Example:
- User in India → Server in USA  
- More distance → Higher latency

---

## 🌎 AWS Regions

- A **Region** is a geographical area where AWS has data centers
- Example:
  - ap-south-1 (Mumbai)
  - us-east-1 (Virginia)

### 🧠 Key Point:
- Data does **NOT automatically move between regions**
- You must configure replication manually

---

## 🏢 Availability Zones (AZ)

- Each region has multiple **Availability Zones**
- Each AZ contains:
  - Data centers
  - Servers
  - Storage
  - Networking

### ✅ Benefits:
- Fault isolation
- High availability

📌 Example:
If one AZ fails → Others still work

---

## 📍 Data Localization
- Data stays within the selected region
- Important for compliance & security

---

### 🧱 What is AWS Outposts?

AWS Outposts is a **hardware rack installed in your data center**.

### 🔄 Use Case:
- Hybrid Cloud (On-prem + AWS)

### 📌 Features:
- Same AWS services on-prem
- Unified management via AWS Console

### 🧠 Architecture:
- Private Data Center <------> AWS Cloud
(Outposts) (Public)


---

## AWS Networking & CDN

### 🌐 What is CDN (Content Delivery Network)?

A CDN caches content closer to users to **reduce latency**.

---

## 🚀 AWS CloudFront

- AWS CDN service
- Delivers content globally with low latency

---

## 🌍 Edge Locations

- Located worldwide
- Cache static content (images, videos, etc.)

### 📊 Key Points:
- 350+ Edge Locations globally
- Closer to users → Faster delivery

---

## 🧠 Regional Edge Cache

- Larger cache than edge locations
- Stores frequently accessed content

📌 Only ~13 regional edge caches globally

---

## 🔄 CDN Flow
- User → Edge Location → Regional Cache → Origin Server


### 📌 Example:
- Static data stored in India (origin)
- User in USA accesses via nearest edge location

---

## 📅 Day 12 – AWS Compute Services

---

## 💻 Amazon EC2 (Elastic Compute Cloud)

### 📌 What is EC2?
- Virtual servers in the cloud
- Used to run applications

---

## 🏗️ Physical Infrastructure

- Tower Servers
- Rack Servers
- Blade Servers

---

## ⚙️ Virtualization Concept

### 🧠 Definition:
Virtualization allows running **multiple virtual machines (VMs)** on a single physical server.

---

## 🧱 Architecture
- Applications
Operating System (Linux/Windows)
Hypervisor (Virtualization Layer)

Physical Hardware (x86 Server)


---

## 🔧 Hypervisor

- Software that enables virtualization

### Types:
- Type 1 (Bare Metal)
- Type 2 (Hosted)

📌 Example:
- VMware
- Hyper-V (Microsoft)

---

## 🚀 Benefits of Virtualization

- Better resource utilization
- Cost efficiency
- Scalability
- Isolation between applications

---

## 🧠 Key Takeaways

- Regions → Geographical areas
- AZs → Fault isolation
- CDN → Low latency delivery
- EC2 → Compute service
- Virtualization → Core of cloud computing

---

## 📚 Author
**Sanu Gupta**  
Cloud & Network Engineer 🚀
