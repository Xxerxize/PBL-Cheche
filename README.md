# PROJECT 1
## **STEP 1 — INSTALLING APACHE AND UPDATING THE FIREWALL**

> Install **Apache** using Ubuntu’s package manager ‘apt’
 
 You need to check if app already exists, so you run a check on the machine.

 #update a list of packages in package manager 

 Run the command
```r
  $ sudo apt update
```
![Image](https://github.com/chechechek88/PBL-Cheche/blob/main/Images%20screenshot/screenshot.png)
---
![install apache2](https://github.com/chechechek88/PBL-Cheche/blob/main/Images%20screenshot/downloaded%20apache2.png)

> verify that apache2 is running as a Service in your OS, use:
```r
  $ sudo systemctl status apache2
```
![apache verified, working](https://github.com/chechechek88/PBL-Cheche/blob/main/Images%20screenshot/apache%20verified%20working.png)

###### **_Green color shows it is working properly_**
Once the server is running, run the code to check if it is accessible.

```r
  curl http://localhost:80
```
![Server running locally](https://github.com/chechechek88/PBL-Cheche/blob/main/curl%20http%20.png)





