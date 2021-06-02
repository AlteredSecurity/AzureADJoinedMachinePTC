# AzureADJoinedMachinePTC

A tool to execute Pass-The-Certificate attack for lateral movement between Azure AD joined machines.

## Requirements

* Python 2.7
* PythonForWindows
* Impacket
* Smbprotocol

## Usage

```
Main.py [-h] --usercert USERCERT --certpass CERTPASS --remoteip REMOTEIP --command COMMAND
```

## Example

```
Main.py --usercert "AzureAD.pfx" --certpass AzureAD --remoteip 192.168.1.2 --command "whoami"
```



*Part of the Kerberos functionality and SMB warrper for PSEXEC taken from Impacket


## Credit

This project is forked from [AzureADJoinedMachinePTC](https://github.com/morRubin/AzureADJoinedMachinePTC) project. 
The original author of the project is [Mor Rubin](https://twitter.com/rubin_mor).
