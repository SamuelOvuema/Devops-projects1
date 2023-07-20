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

sudo yum -y install wget httpd php php-mysqlnd php-fpm php-json

Start Apache
```bash
sudo systemctl enable httpd
sudo systemctl start httpd
```
