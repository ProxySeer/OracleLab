# Project Overview

**!!! The architecture below is set up on virtual servers and ready to run. !!!**  
All virtual machines have their own download links available in the `README.md` file within their respective folders, and all commands to be executed after starting the virtual machines are also included.

**Important note: This Oracle lab works in integration with the PostgreSQL lab. Please review the PostgreSQL lab first before this one.**

**Please read the `README.md` file in each folder after starting the virtual machines.**  

**The entire structure below is designed to be suitable for HA/DR solutions on virtual machines. While doing these installations, I used total of 5 virtual machines in this lab but A total of 21 virtual machines were used with Postgreslab. The setup includes the following technologies. All server installations were performed on RedHat and Ubuntu**

- Oracle Rac  
- Oracle Dataguard  
- PostgreSQL Database  
- Oracle Foreign Data Wrapper
- Oracle GoldenGate(Integrated Mode)
- ProxySeer(Captures all data and sends it to the ProxySeer server)
- FileBeat
- ElasticSearch
- Kibana

**The total size is around 500 GB. Each server has the same configuration, requiring a minimum of 20 GB RAM. 

This Hands-on lab will provide you with numerous opportunities for testing and learning. You can perform tasks such as Data Guard snapshot, switchover and filtering rows to update with GoldenGate.

## Project Architecture

![Project Architecture](https://github.com/ProxySeer/OracleLab/blob/main/Project-Architecture/Project-Architecture.gif)

## Starting Up the Servers

[![Watch the video](https://i.hizliresim.com/2o2po04.PNG)](https://www.youtube.com/watch?v=A_PDvBk6i7Y)

# Author

**Erol Çimen**

You can find me on [GitHub](https://github.com/ProxySeer/PostgresLab) and [LinkedIn](www.linkedin.com/in/erol-çimen-7b86552a0).
