## Configure web server on AWS ec2-instance

`Step 1:` Launch an ec2-instance and SSH into it

```sh
ssh -i codeops.pem ec2-user@ip-addr
```

`Step 2:` Install httpd/apache2 and git

```sh
sudo apt update
sudo apt install -y apache2 git
```

`Step 3:` Clone web-server repository

```sh
git clone https://github.com/i-adarsh/aws.git
```

`Step 4:` Move the web-server files to the hosting directory

```sh
cd aws/02-configure-web-server/
sudo mv ./* /var/www/html/
```

`Step 5:` Start the web-server

```sh
sudo systemctl enable apache2 --now
```
