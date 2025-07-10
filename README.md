# Foundational-Cyber-Elements

---

## My Holistic Take on Cybersecurity

I built a solid, holistic understanding of security, as my mentor suggested. I've been working on it, and here's my high-level overview so far:

In cybersecurity, it makes most sense to start by grasping the **environment and the network**. I think of it as the **perimeter**; everything else lives within it. Since it's the very first point of contact, securing this level is fundamental. At this stage, I'd be looking at things like **firewalls, proxies, Intrusion Detection/Prevention Systems (IDP/IPS), and potentially VPNs**. Once that perimeter's covered, we move inward to what's inside it, which I break down into three main areas: **Endpoints, Users, and Data**.

These three are all part of the network, but they each need their own specific security controls and policies.

---

### Protecting Endpoints

After network controls, the next big focus is **Endpoint Security**. These are often the first things attackers try to get to.

**For endpoint protection, you'd typically implement:**

* **Antivirus (AV) and Endpoint Protection Platforms (EPP)** as your baseline defense.
* **Endpoint Detection and Response (EDR)** goes beyond that, catching malicious events that AV might miss and preventing incidents based on the detection rules you've set up. EDRs also go deeper with hunting, detecting and isolating capabilities.
* **Patch Management** is critical. This is where all your vulnerability management programs fit in, making sure you fix known weaknesses in software, firmware operating systems and applications on those endpoints.
* **Application Whitelisting/Blacklisting** is another strong control. It lets you decide exactly what applications are allowed or blocked from running or being downloaded onto endpoints, offering robust protection against unauthorized code.

---

### Securing Users

Moving on from endpoints, we shift our attention to **Users**. Users are known to often be the weakest link, so securing them is paramount.

**Three foundational controls in this area, in my opinion, are:**

* **Multi-Factor Authentication (MFA):** This hardens access points by requiring at least two ways to verify someone's identity.
* **Least Privilege:** This policy ensures users only get the bare minimum access they need for their job—it's all about authorization.
* **Role-Based Access Control (RBAC):** This drives the least privilege concept by creating specific roles with defined authorization levels, and then assigning users to those roles.
* **Security Awareness Training** is equally, if not more, foundational. Users are often the weakest link, and no amount of technical control can fully mitigate risks if users are susceptible to phishing, social engineering, or poor security hygiene. This is a behavioral control that complements the technical onesSalam
I checked seekers guidance regarding what to do if I accidentally washed my hands with scented soap. It said if it’s lees than a limb (which I think it is for washing only hands) than I only give charity 
I’m not sure how much I need to give 
Can you ask sh faraz listed.



---

### Safeguarding Data

Finally, we get to **Data Security**. This is the information that lives on those endpoints and that users in the organization interact with and have access to.

**The two fundamental security controls for data are DLP and Encryption:**

* **Encryption** uses an algorithm and a key to scramble plain text into an unreadable format. Without that key, the data's locked down. This applies to **data in transit** ( SFTP transfers, secure browser requests with HTTPS, or encrypted emails) and also to **data at rest** (like files stored on a drive).
* **Data Loss Prevention (DLP) software** is key because you can't protect what you don't know is sensitive. DLP learns what your organization's sensitive data is, then tracks it. If it detects suspicious patterns—like data being copied, moved, or exfiltrated by unauthorized individuals—it blocks those actions and triggers alerts.

---

### Bringing It All Together: The Fundamental Pillars

So, fundamentally, these four elements—**Network, Endpoints, Users, and Data**—make up an organization's security posture. It all starts by securing the **network perimeter**, and then moves inward to protect the endpoints, users, and the data that reside within it. Each of these layers has its own specific ways to apply security. That's my high-level overview.

---
