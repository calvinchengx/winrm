# Python client access to WinRM service

Usage:

```bash
python testwinrm.py -U <url> -u <username> -p <password> <cmd> [cmd_args]
```

* url is typically of the form `htpp://fqdn:port`.
* username is your windows machine user (typically in the Administrator group).
* password is the password of your windows machine user
* cmd is typically a powershell command, followed by relevant arguments

