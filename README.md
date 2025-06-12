# NetPractice: Networking And System Administration

## Summary
Net_Practice is a system administration and networking exercise designed to help understand and configure small-scale networks providing hands-on experience with TCP/IP addressing principles and network troubleshooting through a browser-based training interface ensuring proper network connectivity. It's a practical exercise designed to introduce to networking concepts through a series of challenges where users will learn how to configure and troubleshoot networks in a simulated environment gaining valuable insights into **networking fundamentals, TCP/IP addressing, and system administration techniques**, helping build a strong foundation for real-world network management.

---

## General Guidelines
- The project consists of **10 levels**, each containing a unique networking problem that must be resolved.
- Users must configure networks by understanding and applying **TCP/IP addressing** principles.
- The networks in this project are **simulated**, accessible via a **web-based training interface**.
- Logs are available at the bottom of the interface to help debug incorrect configurations.

---

## Subnetting Table
Common subnetting details:

| CIDR Notation | Subnet Mask         | Network Splits | Total Hosts | Valid Hosts |
|---------------|---------------------|----------------|-------------|-------------|
| /30           | 255.255.255.252     | 64             | 4           | 2           |
| /29           | 255.255.255.248     | 32             | 8           | 6           |
| /28           | 255.255.255.240     | 16             | 16          | 14          |
| /27           | 255.255.255.224     | 8              | 32          | 30          |
| /26           | 255.255.255.192     | 4              | 64          | 62          |
| /25           | 255.255.255.128     | 2              | 128         | 126         |
| /24           | 255.255.255.0       | 1              | 256         | 254         |


---

## Networking Concepts
### What is TCP/IP?
TCP/IP (Transmission Control Protocol/Internet Protocol) is a suite of communication protocols used for networking. It includes:
- **IP (Internet Protocol):** Handles addressing and routing of data packets.
- **TCP (Transmission Control Protocol):** Ensures reliable data transmission between devices.

TCP/IP operates on a layered model:
- **Application Layer:** Manages applications (e.g., HTTP, FTP).
- **Transport Layer:** Ensures data delivery (e.g., TCP, UDP).
- **Internet Layer:** Handles addressing and routing (e.g., IP).
- **Network Access Layer:** Manages physical transmission (e.g., Ethernet).

# Net_Practice focuses on fundamental networking principles, including:

### 1. **TCP/IP Addressing**
   - Each device in a network needs a unique IP address.
   - IPv4 uses a **32-bit address** divided into four octets (e.g., `192.168.1.1`).
   - Networks are categorized into **classes (A, B, C, D, E)** based on their size.
   - **Subnet masks** determine the division between the network and host portions of an address.

### 2. **Subnetting**
   - Subnetting allows a large network to be divided into smaller networks.
   - This improves **efficiency, security, and organization** of IP addresses.
   - The subnet mask (e.g., `255.255.255.0`) defines the number of available hosts in a subnet.
   - ### Subnet Masks and CIDR
      - **Subnet Mask:** A 32-bit number dividing an IP address into network and host portions.
      - **CIDR (Classless Inter-Domain Routing):** Defines IP ranges using notation like `192.168.1.0/24`, where `/24` specifies the fixed bits of the subnet mask.

### 3. **Switches**
   - **Switches:** Connect multiple devices within the same network and forward data based on MAC addresses.

### 4. **Routing Basics**
   - **Routers:** Direct network traffic between different networks.
   - **Routing Tables:** Store reachable networks and interfaces.
   - **Default Gateway:** The router address packets use when no specific route is available.

### 5. **Common Network Issues**
   - **IP address conflicts** occur when two devices share the same address.
   - **Incorrect subnet masks** can prevent communication between devices.
   - **Routing misconfigurations** lead to unreachable networks.
