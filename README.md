# 🛡️ Huawei USG6000 Firewall Zone Segmentation Lab

## 📌 Overview
<img width="1224" height="1285" alt="USG6000 " src="https://github.com/user-attachments/assets/ba526c86-db18-4a31-bd60-922b06b053fc" />

This lab demonstrates how to configure security zones and firewall policies on a Huawei USG6000 firewall using Huawei eNSP.

The network is divided into three security zones: **Trust, DMZ, and Untrust**. Firewall policies are used to control communication between these zones and allow or block traffic according to the configured rules.

## 🎯 Lab Objectives

- ⚙️ Configure Huawei USG6000 firewall interfaces.
- 🧩 Create and assign security zones.
- 🔐 Configure inter-zone security policies.
- 🚦 Control traffic between different network segments.
- 🧪 Verify connectivity using Ping tests.

## 🌐 Network Zones

| Zone | Description |
|---|---|
| 🟦 **Trust** | Represents the internal network. |
| 🟩 **DMZ** | Contains servers or services that require controlled access. |
| 🟥 **Untrust** | Represents the external or untrusted network. |

## 🛠️ Lab Configuration

### 1️⃣ Interface Configuration

Configure the firewall interfaces with the appropriate IP addresses and assign them to the correct security zones.

### 2️⃣ Security Policies

Create security policies to control traffic between the Trust, DMZ, and Untrust zones.

- ✅ Permit authorized traffic.
- 🚫 Block traffic that is not allowed by the configured policies.
- 🔒 Apply access control between network segments.

### 3️⃣ Connectivity Testing

Use Ping from the connected PCs to verify network connectivity and check whether the firewall policies behave as expected.

## 🔍 Verification

The lab screenshots demonstrate:

- 🖥️ Firewall interface configuration.
- 🔐 Security policy configuration.
- ✅ Successful Ping tests for permitted traffic.
- ❌ Failed Ping tests for blocked traffic.

## 💻 Technologies Used

- Huawei USG6000 Firewall
- Huawei eNSP
- Firewall Security Zones
- Inter-Zone Security Policies
- ICMP / Ping Testing

## 🏁 Conclusion

This lab demonstrates how a Huawei USG6000 firewall separates network zones and controls communication through security policies. Connectivity tests help verify that permitted traffic can pass while restricted traffic is blocked.

---

👨‍💻 **Author:** Abdalla Mohamed Nieam
