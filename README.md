# Project Overview

**!!! The architecture below is set up on virtual servers and ready to run. !!!**  
All virtual machines have their own download links available in the `README.md` file within their respective folders

**Important note: This Oracle lab works in integration with the PostgreSQL lab. Please review the PostgreSQL lab first before this one.**

**All server installations were performed on RedHat and Ubuntu**

- Oracle Rac  
- Oracle Dataguard  
- PostgreSQL Database  
- Oracle Foreign Data Wrapper
- Oracle GoldenGate(Integrated Mode)
- ProxySeer(Captures all data and sends it to the ProxySeer server)
- FileBeat
- ElasticSearch
- Kibana

**The total size is around 500 GB. Each server has the same configuration, requiring a minimum of 20 GB RAM.**

**This Hands-on lab will provide you with numerous opportunities for testing and learning. You can perform tasks such as Data Guard snapshot, switchover and filtering rows to update with GoldenGate.**

**With ProxySeer, you can capture all queries and login information executed on all PostgreSQL and Oracle databases at the operating system level, and also integrate with Elasticsearch.**

## Project Architecture

![Project Architecture](https://github.com/ProxySeer/OracleLab/blob/main/Project-Architecture/Project-Architecture.gif)

## Audit (Captures all Queries and Login Informations) with ProxySeer (ElasticSearch FileBeat Kibana)

[![Watch the video](https://i.hizliresim.com/qsm3qw7.PNG)](https://www.youtube.com/watch?v=oH-vh9WcT7Q)

## Oracle Foreign Data Wrapper Oracle - PostgreSql 

[![Watch the video](https://i.hizliresim.com/qsm3qw7.PNG)](https://www.youtube.com/watch?v=A-lmiHTO54I)

## Oracle : Oracle Rac - Dataguard switchover

[![Watch the video](https://i.hizliresim.com/bfz55no.PNG)](https://www.youtube.com/watch?v=6s2PvWRNal0&t=1s)

## Oracle : GoldenGate Oracle - PostgreSql

[![Watch the video](https://i.hizliresim.com/t10havl.PNG)](https://www.youtube.com/watch?v=Du-xZea8vPc)

# Author

**Erol Çimen**

You can find me on [GitHub](https://github.com/ProxySeer/PostgresLab) and [LinkedIn](www.linkedin.com/in/erol-çimen-7b86552a0).
