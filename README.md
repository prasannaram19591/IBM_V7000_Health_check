# IBM_V7000_Health_check

Hello Storage Admins,

How many times we had been told to automate daily health checks of the storae infra that we manage by many people. In a work area with more than 50 storage devices, it will become a tedious task to login to each storage device and perform the same commands and verifying the output. More than the wastage of time it involes manual erros as well. I have got you covered for all your day to day health checks for storage devices that you manage.

Pre-requisites:
1.  SSH connectivity to the storage box to run remote commands.
2.  A Linux VM with storage network connectivity.
3.  Python 2.7 and above installed on the vm.
4.  Python Paramiko and MIME modules installed for SSH and mailing capabilities.
5.  The VM should be able to send mails through SMTP.
6.  Optionally Jenkins to schedule.
