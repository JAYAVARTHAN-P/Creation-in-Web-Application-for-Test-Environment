 # CREATION IN WEB APPLICATION FOR TEST ENVIRONMENT
## AIM
To Creation in Web Application for Test Environment.
## PROBLEM STATEMENT
Setting up test environments for web applications is time-consuming and complex. Developers need an efficient way to replicate real-world conditions while ensuring security and consistency. A simplified solution can streamline the process and improve testing outcomes.
## ALGORITHM
 ### Steps 1:
 Launch an EC2 instance in AWS using an Amazon Linux 2 AMI with a Security Group allowing HTTP and SSH traffic.
 ### Steps 2:
 Connect to the instance using SSH and install a web server like Apache.
 ### Steps 3:
 Create a simple HTML file in the server's default directory.
 ### Steps 4:
 Enter the content you want to be displayed in the website.
 ### Steps 5:
 Access the instance's public IP in a browser to verify the HTML page is displayed.
## COMMANDS
### To install httpd:
```
yum install httpd -y
```
### To enable and start httpd :
```
systemctl enable httpd
systemctl start httpd
```
### HTML code :
```html
<!DOCTYPE html>
<html>
<body>
<h1>My First PHP page</h1>
<?php
echo "Hello World";
?>
</body>
</html>
```
## OUTPUT
### REG NUMBER:212222100015
### NAME: Jayavarthan P
### Terminal:
![386834017-fc9d9baf-9d2d-4470-833a-e6bce67247b7](https://github.com/user-attachments/assets/95fe2d35-f377-4797-b6a8-3f811508e8e9)

### Website:
![386834037-f63dc64f-c2ea-4aa8-9d6c-02b56b96adc1](https://github.com/user-attachments/assets/dea0906c-8689-4de4-8761-91fb68eab536)


## RESULT
 Thus the web application for test environment has successfully been created and executed.

  


