## This app claims following features:
- [X] LDAP integration
- [X] Multi-instance
- [X] Adeed php.log in the root folder for debugging PHP, with logrotate applied on it (can be accesssed by **admin->logs** and entering the **php.log**).
- [X] Fail2Ban
- [X] Option to choose between **Mysql** and **PostgreSQL** for the Osada

## Ldap Admin user rights, logs and failed database updates

- **For admin rights**: When installation is complete, you will need to visit your new hub's page and login with the **admin account username** which was entered at the time of installation process. You should then be able to create your first channel and have the **admin rights** for the hub.

- **For normal YunoHost users**: Normal LDAP users can login through LDAP authentication and create there channels.

- **Failing to get admin rights**: If the admin cannot access the admin settings at `https://osada.example.com/admin` then you have to **manually add 4096** to the **account_roles** under **accounts** for that user in the **database through phpMyAdmin**.

- **For logs**: Go to **admin->logs** and enter the file name **php.log**.

- **Failed Database after Upgrade:** Some times databse upgrade fails after version upgrade. You can go to hub eg. `https://osada.example.com/admin/dbsync/` and check the numbers of failled update. These updates will have to be ran manually by **phpMyAdmin**.
