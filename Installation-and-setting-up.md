## Installation

To install **Apache2** on our **Ubuntu** machine, input the following commands on the terminal:

```
apt install apache2 -y
```

To verify that the service is running, we can type the command:

```
systemctl status apache2
```

You should be a able to get similar output:

```
● apache2.service - The Apache HTTP Server
     Loaded: loaded (/lib/systemd/system/apache2.service; enabled; vendor preset: enabled)
     Active: active (running) since Wed 2025-01-29 11:30:12 UTC; 7min ago
       Docs: https://httpd.apache.org/docs/2.4/
    Process: 3786 ExecStart=/usr/sbin/apachectl start (code=exited, status=0/SUCCESS)
   Main PID: 3805 (apache2)
      Tasks: 55 (limit: 2338)
     Memory: 5.2M
     CGroup: /system.slice/apache2.service
             ├─3805 /usr/sbin/apache2 -k start
             ├─3806 /usr/sbin/apache2 -k start
             └─3807 /usr/sbin/apache2 -k sta
```

You can also access it on your browser using the by typing ```http://<IP ADDRESS OF THE DEVICE>``` You should be able to have a similar output:

![image](https://github.com/user-attachments/assets/8645d4b7-13a2-4ba4-b214-079816ca51de)





