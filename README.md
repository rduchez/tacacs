# tacacs
This repo is for tacacs+ config files that will work with F5 BIG-IQ (tac_plus.conf)

In order to use this, you can:

Install Ubuntu on a server/vm - giyf

Install tacacs+ on the linux box: 
```sudo apt-get install tacacs+```
Edit configuration file:
```sudo vi /etc/tacacs+/tac_plus.conf```

Make sure to edit the config file as needed to reflect your environment and requirements. 

The BIG-IQ tacacs+ server configuration (System-User Management-Auth Providers) should look something like: 
<img width="1398" alt="Screen Shot 2019-04-08 at 6 11 36 PM" src="https://user-images.githubusercontent.com/12305166/55766509-d1b57580-5a29-11e9-98a6-fb430d219b6c.png">


The User Group assignment (System-User Management-User Groups) should look something like:
<img width="1398" alt="Screen Shot 2019-04-08 at 6 00 20 PM" src="https://user-images.githubusercontent.com/12305166/55766187-51dadb80-5a28-11e9-817f-c3f9584b202e.png">
