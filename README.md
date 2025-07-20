# Secure Email Server Deployment

This project involves designing and deploying a secure email server using an Ubuntu-based virtual machine and open-source tools. The setup ensures authenticated email delivery, malware protection, system monitoring, and a webmail interface — all configured in a secure and scalable environment.

## Tools & Technologies Used

- Ubuntu 22.04 LTS (on VM or cloud)
- Postfix (SMTP server)
- Dovecot (IMAP/POP3)
- Roundcube (Webmail interface)
- MariaDB (Mail user storage)
- NGINX (Web server)
- Fail2Ban (Intrusion prevention)
- ClamAV (Malware scanning)
- Netdata (System monitoring)
- DNS records (SPF, DKIM, DMARC)
- iRedMail (Mail server setup automation)

## Features

- Secure email sending & receiving with virus and spam filtering
- Web-based email access via Roundcube
- SSL certificate integration using Certbot
- Mailbox management using MariaDB
- IP ban automation for suspicious login attempts
- Real-time performance monitoring with Netdata

## Security Highlights

- Authentication: SPF, DKIM, DMARC records
- Malware scanning with ClamAV
- Fail2Ban to block brute-force login attempts
- SSL encryption for secure access

