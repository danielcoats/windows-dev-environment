# Windows Development Environment

Automated development environment setup using Boxstarter. Based on [https://github.com/felixrieseberg/windows-development-environment](https://github.com/felixrieseberg/windows-development-environment).

## Prerequisites

Run the following commands with administrator privileges.

### Chocolatey

```powershell
Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
```

### Boxstarter

```powershell
cinst -y boxstarter
```

## Installation

```powershell
START http://boxstarter.org/package/nr/url?https://raw.githubusercontent.com/danielcoats/windows-dev-environment/master/boxstarter
```
