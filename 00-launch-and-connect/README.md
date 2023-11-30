## Connect through linux/mac:

`Step 1:` Change the file permission such that only owner has access to read and write:

```shell
chmod 400 codeops.pem
```

`Step 2:` Enter your username and IP address with PEM key file path

```shell
ssh -i "codeops.pem" ec2-user@124.15.184.36
```

## Connect through windows:

### Method 1:

Using Powershell

`Step 1:` Enter your username and IP address with PEM key file path in powershell

```shell
ssh -i "codeops.pem" ec2-user@124.15.184.36
```

### Method 2:

Using Putty

`Step 1:` Download and install putty according to your system architecture from the below link:

```sh
https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html
```

`Step 2:` Open Putty Keygen to generate the Private Key file as shown in image:

`Step 3:` Enter username and IP of your VM instance:

`Step 4:` Enter the Private Key file path:
