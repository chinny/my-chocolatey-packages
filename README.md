# my-chocolatey-packages

## Requirements

* Chocolatey
Install via elevated PS:

```
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
```

## Usage

* Install my favorite applications through the Chocolatey package manager.

## Changelog

* 2021-04-19: 
  * Init commit 
  * Created xml config files (based on chinny/my-winget-packages)
