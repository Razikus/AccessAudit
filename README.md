[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fmoshix%2FAccessAudit&count_bg=%2379C83D&title_bg=%23555555&icon=microsoftsqlserver.svg&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)

What is AccessAudit?
====================

AccessAudit is an extension to Linux instances to log all logins securely and tamperproof in an immutable database for audit and forensic purposes. All logins are logged with rich metadata  (IP, time, user, time etc.). A query tool is provided to query and serach the audit log in the database and export it. 

AccessAudit allows server administrator, auditors etc. to provide a cryptographically strong, and tamperproof tally all accesses to their Linux instances. 


How does AccessAudit Work?
==========================


AccessAudit is a script that will do the following for your local and remote Linux machines:

1. Obtain the auditable and immutable database immudb in a container
2. Craete an 'audit' database in it
3. Modify your rsyslog.conf so that all logins to your Linux instance will *also* be logged in the database
4. Give you a tool to query and search the audit database for logins and related info 

Features
========

| Feature                            | Supported          |
| --------------------------         | ------------------ |
| Debian/Ubuntu/Mint/Arch            | :white_check_mark: |  
| Red Hat/AlmaLinux/Rocky            | :white_check_mark: |  
| Obtains latest immudb              | :white_check_mark: |  
| Enables auto-start of db at boot   | :white_check_mark: |  
| Query tool with search for db      | :white_check_mark: |  
| SSL support                        | :white_check_mark: |  
| Windows                            | :x:                |  
| Solve world hunger                 | :x:                |

  



Moshix  
December 16, 2022  
