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

# Install modules and packages

## The most commonly used modules include:

  - Active Directory
  - Microsoft Exchange Server
  - Azure Active Directory
  - Office 365 (M365)
  - SQL Server
  - SharePoint Server
  - Internet Information Services

## To get list of installed moudle

```
Get-Module -ListAvailable
```

# To get process

```
Get-Process
```

# To get services

```
Get-Service
```

# Retrieves a list of files and folders in a directory.

```
Get-ChildItem
```

# Cmdlet alias

```
Start-Process notepad

start notepad
```

```
Stop-Process -Name notepad

spps -Name notepad
```

# To see all aliases

```
Get-Alias
```

# Cmdlet parameters and arguments

```
Get-Process

[-Name <String[]>]
[-ComputerName <String[]>]
[-FileVersionInfo]
[-Module]
[-InputObject <Process[]>]
[-IncludeUserName] [-ExcludeUserName]
[-Credential <PSCredential>]
[-Id <Int32[]>]
[-IncludeTotalProcessorTime]
[-WhatIf]
[-Confirm]

```

