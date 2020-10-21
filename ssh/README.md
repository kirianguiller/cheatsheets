# SSH Connection


### Automatic connections

Enter this command for linking the ssh connection with the local public key 
```
ssh-copy-id -i ~/path/to/public/key <username>@<IP>
```

Here an example with my configuration (changed the IP for security)
```
ssh-copy-id -i ~/.ssh/id_rsa.pub webadmin@90.123.70.72
```

Here a link to a tutorial I followed that worked : https://www.ssh.com/ssh/copy-id