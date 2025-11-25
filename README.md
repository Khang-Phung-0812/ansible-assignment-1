# Assignment 1 – Configure Hostnames and Interface Descriptions
**Student:** Tran Minh Khang Phung  
**Course:** CNIT381 – Network Automation

## 📘 Description
This playbook configures hostnames and interface descriptions on two routers in a CML topology.  
Each router receives a unique hostname and a custom description on interface Ethernet0/0.  
After configuration, the playbook verifies the changes using IOS show commands.

## ▶️ How to Run
```bash
ansible-playbook -i inventory.ini assignment1.yaml
