## ☁️ **What is Cloud Computing?**

Cloud computing is the **on-demand delivery** of IT resources—like servers, storage, databases, networking, software, and analytics—via the **internet 🌐**, without direct management by the user.
It enables organizations to access resources from a **Cloud Service Provider (CSP)**, typically **on a pay-as-you-go model 💳**, reducing the need for huge hardware investments.

🧵 *"Cloud is a network of remote servers that store data, run applications, and power services—eliminating the need for managing physical infrastructure."*

---

## 🔄 **Cloud Computing vs. Monolithic Servers**

| Feature          | 🧱 Monolithic Server                     | ☁️ Cloud Computing                |
| ---------------- | ---------------------------------------- | --------------------------------- |
| **Architecture** | All app components in a single system 🔒 | Distributed, scalable systems 🌍  |
| **Scalability**  | Manual upgrades 🔧                       | Auto-scaling ⚙️                   |
| **Cost**         | Capital Expenditure (CapEx) 💸           | Operational Expenditure (OpEx) 💳 |
| **Maintenance**  | Managed by user 🧑‍🔧                    | Managed by CSP 🛠️                |
| **Flexibility**  | Low, hard to reconfigure 🚫              | High, on-demand provisioning ✅    |

---

## 🖐️ **Five Characteristics of Cloud Computing**

1. ⚡ **On-Demand Self-Service**: Instant access to computing resources without human interaction.
2. 🌐 **Broad Network Access**: Accessible from phones, laptops, tablets using the internet.
3. 🧠 **Resource Pooling**: Multi-tenant model with dynamic resource allocation.
4. 📈 **Rapid Elasticity**: Instantly scale resources up or down—appears infinite!
5. 📊 **Measured Service**: Pay only for what you use, with precise monitoring.

---

## 🎯 **Benefits of Cloud Computing**

✅ Increased speed and agility (resources in minutes)
✅ No more capacity guessing 🎯
✅ Focus on **innovation 💡** not infrastructure 🖥️
✅ Expand globally in minutes 🌍

---

## 💰 **Trading CapEx for OpEx**

Cloud transforms large, upfront **CapEx** investments into flexible, scalable **OpEx** models.

**Advantages:**

* 💵 **Cost Efficiency**: Avoid huge investments
* 🚀 **Agility**: Scale with market demand
* 🔧 **Less Maintenance**: CSP handles updates & security
* 🧪 **Experimentation**: Try new tools without risk
* 🌎 **Global Scalability**: Deploy services near users for low latency

---

## 🧩 **Types of Cloud Computing Services**

1. 🏗️ **Infrastructure as a Service (IaaS)**

   * Provides: Virtual Machines, Storage, Networking
   * Example: AWS EC2, S3
   * You manage OS, data, and apps.

2. 🛠️ **Platform as a Service (PaaS)**

   * Provides: App development platforms
   * Example: Google App Engine, AWS Elastic Beanstalk
   * You manage code; CSP manages the rest.

3. 💻 **Software as a Service (SaaS)**

   * Provides: Fully functional applications
   * Example: Gmail, Salesforce, Slack
   * You use the app; everything else is handled.

---

## 🏗️ **Cloud Deployment Models**

1. ☁️ **Public Cloud**

   * Provided by AWS, Azure, GCP
   * Shared infrastructure, cost-effective
2. 🏠 **Private Cloud**

   * Dedicated to one organization
   * More secure, customizable
3. 🔁 **Hybrid Cloud**

   * Combines public + private
   * Flexibility + control
4. 🌐 **Multi-Cloud**

   * Uses multiple cloud vendors
   * Avoids lock-in, boosts redundancy

---

## 🌎 **AWS Global Infrastructure**

Designed for **high availability**, **low latency**, and **scalability**.

### 📍 AWS Regions & AZs

* **Region**: Geographic area with multiple data centers
* **AZ (Availability Zone)**: One or more isolated data centers
* 🔁 **AZs are interconnected** for fast replication and fault tolerance

---

## 🧭 **AWS Edge Components**

* 🏙️ **Local Zones**: Place compute/storage closer to metro areas for low latency (e.g., gaming)
* 📡 **Wavelength**: Embedded in 5G networks for **ultra-low latency apps** (e.g., IoT, autonomous cars)
* 🏢 **Outposts**: AWS services in on-prem data centers for hybrid needs
* 🌐 **Points of Presence (PoPs)**: Edge locations for caching, CDN, and low latency

---

## 🔐 **AWS Shared Responsibility Model**

| Responsibility | AWS (🔒 Security **of** the cloud)  | Customer (🔐 Security **in** the cloud) |
| -------------- | ----------------------------------- | --------------------------------------- |
| Infrastructure | ✅ AWS manages physical data centers | ❌ Not your responsibility               |
| Data Security  | ❌ Your responsibility               | ✅ Manage access, encryption, firewalls  |
| Patching       | AWS patches hardware                | You patch OS & applications             |

🛡️ **Shared Controls**: Both AWS and customer collaborate (e.g., patch mgmt., config settings)

