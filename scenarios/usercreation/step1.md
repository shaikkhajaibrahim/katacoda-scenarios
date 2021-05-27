User Creation
-------------

* For creating the Linux user, we need to specify
  * username
  * home directory of the user

* Lets create a user 'ironman'
`sudo useradd -d /home/ironman ironman`{{execute}}

* Now lets examine if the user got created or not. The User information in Linux machines is stored in the file ```/etc/passwd```

`sudo cat /etc/passwd`{{execute}}
    