# Load Balancers : Traffic Cop

**What**: A device/service that sits in front of your servers.

**Why**: If one server gets 10,000 requests, it crashes. The NGINX Load Balancer or AWS ELB distributes that traffic across 5 or 10 servers so no single one is overwhelmed.

---
A load balancer is a networking device or software application that distributes and balances the incoming traffic among the servers to provide high availability, efficient utilization of servers, and high performance.

Load balancers are highly used in cloud computing domains, data centers, and large-scale web applications where traffic flow needs to be managed. 
The primary goal of using a load balancer is, not to overburden with huge incoming traffic which may lead to server crashes or high latency.

---
### Types of Load Balancers
- Based on Configurations
  - Software Load Balancer
  - Hardware Load Balancer
  - Virtual Load Balancer
- Based on Functions
  - L4 Load Balancer
  - L7 Load Balancer
  - Global Server Load Balancing

---
### Load balancing algorithms

1. Round Robin

2. Weighted Round Robin

3. Source IP Hash

4. Least Connection Method

5. Least Response Time Method
