# WINspect

>     WINspect is part of a larger project for auditing different areas of Windows environments.           #
   It focuses on enumerating different parts of a Windows machine aiming to identify security weaknesses       #
   and point to components that need further hardening. The main targets for the script are domain-joined      #
   windows machines. Howerver, some of the functions can also be invoked for standalone workstations.
## Features

This current version of the script supports the following features :

- Checking installed security products .
- Enumerating World Exposed local filesystem shares.
- Enumerating domain users and groups with local group membership.
- Enumerating registry autoruns.
- Enumerating local services that are configurable by Authenticated Users group members.
- Enumerating local services for which corresponding binary is writable by Authenticated Users group members.
- Enumerating non-system32 Windows Hosted Services and their associated DLLs.
- Enumerating local services with unquoted path vulnerability.
- Enumerating non-system scheduled tasks.
- Checking for DLL hijackability.
- Checking for User Account Contol settings.
- Checking for unattended installs leftovers.

## Supported Powershell Version

   This version was tested in a powershell v2.0 environment.
   
```
curl https://raw.githubusercontent.com/ascott1/readme-template/master/README-template.md > README.md
```

## Getting Help

If you have questions or need further guidance on using this template, please [file an issue](https://github.com/ascott1/readme-template/issues). I will do my best to respond to all issues in a timely manner.

## Contributions

You are welcome to contribute and suggeste any improvements.
If you want to point to an issue, Please [file an issue](https://github.com/ascott1/readme-template/issues).

## Direct contributions
For direct contributions: 
  0.Fork the repository. 
  1.File a pull request.
  2... You are good to go ;)
  
## Lisence
This project is licensed under The GPL terms .