# Help Desk SAG

This repository contains the custom osTicket setup and configuration for SAG.

## Features
- Pre-configured ticket templates.
- Custom SLA policies and workflows.
- Database backup included.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/FreddyMH07/Help-Desk-SAG.git
2. Upload files to your server:
   scp -r Help-Desk-SAG/ root@server_ip:/var/www/html/Help-Desk/
3. Restore the database:
   mysql -u [username] -p [database_name] < Helpdesk_backup.sql
4. Edit include/ost-config.php with your database credentials.
5. Restart web server:
   systemctl restart apache2
