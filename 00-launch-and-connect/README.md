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

`Step 2:` Open Puttygen to generate the Private Key file as shown in image:

<img src="https://github.com/i-adarsh/aws/blob/main/00-launch-and-connect/key-1.png?raw=true" alt="image" style="width:60%;height:auto;">
<img src="https://github.com/i-adarsh/aws/blob/main/00-launch-and-connect/key-2.png?raw=true" alt="image" style="width:60%;height:auto;">
<img src="https://github.com/i-adarsh/aws/blob/main/00-launch-and-connect/key-3.png?raw=true" alt="image" style="width:60%;height:auto;">
<img src="https://github.com/i-adarsh/aws/blob/main/00-launch-and-connect/key-4.png?raw=true" alt="image" style="width:60%;height:auto;">
<img src="https://github.com/i-adarsh/aws/blob/main/00-launch-and-connect/key-5.png?raw=true" alt="image" style="width:60%;height:auto;">

`Step 3:` Enter username and IP of your VM instance:

<img src="https://github.com/i-adarsh/aws/blob/main/00-launch-and-connect/con-1.png?raw=true" alt="image" style="width:60%;height:auto;">
<img src="https://github.com/i-adarsh/aws/blob/main/00-launch-and-connect/con-2.png?raw=true" alt="image" style="width:60%;height:auto;">

`Step 4:` Enter the Private Key file path:

<img src="https://github.com/i-adarsh/aws/blob/main/00-launch-and-connect/con-3.png?raw=true" alt="image" style="width:60%;height:auto;">
<img src="https://github.com/i-adarsh/aws/blob/main/00-launch-and-connect/con-4.png?raw=true" alt="image" style="width:60%;height:auto;">
<img src="https://github.com/i-adarsh/aws/blob/main/00-launch-and-connect/con-5.png?raw=true" alt="image" style="width:60%;height:auto;">
