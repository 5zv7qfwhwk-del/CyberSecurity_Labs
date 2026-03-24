# 🌐 Network Foundations & Data Flow

## 🎯 Focus

Understanding how data travels across a network and why networking is
critical to cybersecurity.

-   Data flow: **Device → Router → Internet → Server**
-   Identifying where vulnerabilities may exist in the communication
    path

------------------------------------------------------------------------

## 📘 Study

### Network Components

-   Studied **Professor Messer Network+ -- Section 3**
    -   Network devices
    -   Physical vs logical topology
    -   Took concise bullet-point notes

------------------------------------------------------------------------

## 🧠 Concept Check

### What happens when I type a website into a browser?

When a URL is entered:

1.  The browser queries **DNS** to resolve the domain name into an IP
    address\
2.  A **TCP connection** is established with the destination server\
3.  The browser sends an **HTTP/HTTPS request**\
4.  The server responds with data (HTML, CSS, JS)\
5.  The browser renders the webpage

------------------------------------------------------------------------

### Where does DNS fit?

DNS (Domain Name System) acts as the **translator of the internet**:

-   Converts domain names → IP addresses\
-   Required before any communication with a server begins\
-   Critical to web browsing, email, and most internet services

------------------------------------------------------------------------

### Where can an attacker intercept traffic?

Potential interception points include:

-   Unsecured public Wi-Fi networks\
-   Compromised routers or switches\
-   Malicious or monitored ISP routes\
-   Man-in-the-Middle (MITM) attacks\
-   Unencrypted HTTP traffic

------------------------------------------------------------------------

## 🧪 Lab: Network Path Analysis

### Commands Used

``` bash
ping google.com
traceroute google.com
```

------------------------------------------------------------------------

### Key Observations

-   **Traceroute** reveals the path packets take across networks\
-   Each "hop" represents a network device (typically a router)

#### Results:

-   Total hops: **17**
-   Notable latency spike:
    -   Hop 14 increased from **\~12ms → \~34ms**

------------------------------------------------------------------------

## 🔍 Analysis

Traceroute helps:

-   Visualize how traffic flows across the internet\
-   Identify latency bottlenecks\
-   Detect abnormal routing behavior\
-   Understand the attack surface between source and destination

------------------------------------------------------------------------

## 🧠 Key Takeaways

-   Networking is foundational to cybersecurity\
-   Every hop introduces potential risk or delay\
-   DNS is a critical (and often targeted) component\
-   Visibility into traffic flow is essential for threat detection
