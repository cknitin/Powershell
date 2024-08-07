# To check poweshell version

```
$PSVersionTable 
```

# To check execution policy

```
Get-ExecutionPolicy
```

- Restricted — No PowerShell scripts may be run. This is the default setting.
- AllSigned — You can run PowerShell scripts signed by a trusted developer.
- RemoteSigned — You can run your own scripts or scripts signed by a trusted developer.
- Unrestricted — You can run any script you want.

# To change the execution policy setting

```
Set-ExecutionPolicy RemoteSigned
```
