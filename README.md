# git-settings

## INSTALLING GIT 

1. install git
> https://git-scm.com/downloads

2. sign in git in cmd / terminal 
> git config --global user.name "your_username" 

> git config --global user.email "your_email_address@example.com"

note: for a simple config just use the same email with github

3. create ssh key in your pc/laptop

- Generate SSH
> $ ssh-keygen

note: for enter passphrase just empty it

4. See ssh
> $ cat ~/.ssh/id_rsa.pub or $ pbcopy < ~/.ssh/id_rsa.pub

5. Check ssh // tbh i forgot what is this command doing hehe
> $ dir .ssh

4. sign the ssh key from your device pc/laptop to git web service profile

![image](https://user-images.githubusercontent.com/90954993/209432173-0de76a7e-5f64-4ea2-b62e-11634704a08f.png)


5. when cloning if asked to enter password create token in git web profile

![image](https://user-images.githubusercontent.com/90954993/209432378-e1745cbe-d7ba-4a28-93b9-05a4497832a8.png)


## SYNCHING MS VISUAL STUDIO CODE CONFIG

1. install Settings Sync extension from author Shan Khan
2. press f1 and choose download settings to download stored settings
3. choose update/upload to upload new settings
