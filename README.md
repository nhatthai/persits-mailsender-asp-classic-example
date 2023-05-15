# Persits Mail Sender ASP Classic Example
+ Send email in ASP Classic

### Requisite
+ Install [Persits.MailSender](https://www.aspemail.com/download.html) in your server
    ![Install Persits Mail Sender](./images/Installed-Persits.MailSender.png)
+ Create an application in IIS
+ Create SMTP

### Issues
+ Server object error 'ASP 0177 : 800401f3'. Server.CreateObject Failed
    ```
    Fixed: Enable 32 Bit Applications = false in the Application pool in IIS
    ```
    It depends on your server which is using 64BIT/32BIT

    ![application-pool-iis](./images/application-pool-iis.png)
