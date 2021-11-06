# Windows 10 Home edition && Docker

- You want to enable the windows feature "Windows Hypervisor"?
- You only have a installation of windows 10 home?

## Steps to make HyperV feature available:
- create new file on desktop "hv.bat" (*doesnt need to be desktop*)
- copy code from "hv.bat" in this repository
- open hv.bat in edit mode
- paste code from repo in there and save
- execute "hv.bat" with administrator rights
now you have HyperV available!

## **Bonus** aktivate HyperV:
- open cmd with administrator right
- type "bcdedit /set hypervisorlaunchtype auto" and execute
- close cmd
- open windows features, check the option Windows HyperVisorPlattform
- restart maschine
