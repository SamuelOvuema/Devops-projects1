# webstack
```bash
sudo apt update
```
**Step 3 — Install WordPress on your Web Server EC2**

Update the repository
```bash
sudo yum -y update
```
Install wget, Apache and it’s dependencies
![Snipaste pro5 mysql](https://github.com/SamuelOvuema/Devops-projects1/assets/132525203/6c4c1bbe-e15b-4134-9c19-25bf42182727)
sudo yum -y install wget httpd php php-mysqlnd php-fpm php-json

Start Apache
```bash
sudo systemctl enable httpd
sudo systemctl start httpd
```
