User Creation
-------------

* For creating the Linux user, we need to specify
  * username
  * home directory of the user

* First lets find out what is the user which we are logged in as `whomai`{{execute}}
  
* Explore the ```/etc/passwd``` file the first entry in this file will be root user
`head -n 5 /etc/passwd`{{execute}}


* Lets create a user 'ironman'
`useradd -d /home/ironman ironman`{{execute}}

* Now lets examine if the user got created or not. The User information in Linux machines is stored in the file ```/etc/passwd```

`cat /etc/passwd`{{execute}}

* For the specific line with the ironman information `tail -n 1 /etc/passwd`
* Compare the content with the following pattern
```
username:x:UID:GID:User Home Directory: User Bash Type
x represents the encrypted password
```
* The user information can be changed by username `chfn ironman`{{execute}}

* Change the password of the ironman by executing `passwd ironman`{{execute}} 

* To check the password expiry and account information `chage -l ironman`{{execute}}

    