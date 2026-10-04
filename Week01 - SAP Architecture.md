Day 1 - SAP Architecture Fundamentals
--------------------------------------
 
What is SAP Architecture?
 
SAP follows a 3-tier architecture consisting of:
1. Presentation Layer
2. Application Layer
3. Database Layer

 
Presentation Layer:
-------------------
 
The Presentation Layer allows users to interact with SAP.
 
Examples:
 
- SAP GUI
- SAP Business Client
- SAP Fiori Launchpad
 
Responsibilities:
 
- User interaction
- Sending requests
- Displaying results
 
---
 
Application Layer:
------------------
 
The Application Layer is the heart of SAP.
 
Major Components:
 
- Dispatcher
- Work Processes
- Message Server
- Gateway
 
Responsibilities:
 
- Process business logic
- Handle user requests
- Communicate with database
 
---
 
Database Layer:
---------------
 
The Database Layer stores all SAP data.
 
Examples:
 
- Customer Data
- Vendor Data
- Purchase Orders
- Configuration Data
 
Databases:
 
- SAP HANA
- Oracle
- SQL Server
 
---
 
Message Server:
----------------
Purpose:
 
- Load balancing
- Communication between application servers

 
Example:

User A → App Server 1

User B → App Server 2

User C → App Server 3

 
Dispatcher:
------------
Purpose:
 
The Dispatcher receives user requests and assigns them to available work processes.

 
Flow:

 
User Request

↓

Dispatcher

↓

Work Process

↓

Database

---
Key Transactions

 
SM51 - Used to view application servers.

 
SM50 - Used to monitor work processes of the current instance.

 
SM66 - Used to monitor work processes across all instances.

 
---
 
Day 1 Troubleshooting Scenario:
-------------------------------

Problem:
Users can log in but transactions are very slow.

 
Checks: 
1. SM50
2. SM66
3. SM37
4. SM21
5. ST06
6. ST03N
7. DBACOCKPIT
 

 
Key Learnings:
--------------
 
- SAP uses a 3-tier architecture.
- Message Server performs load balancing.
- Dispatcher assigns requests to work processes.
- Application Layer is the heart of SAP.

