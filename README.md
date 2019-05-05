First run powershell as **Administrator** and paste and run this: <code>Set-ExecutionPolicy Unrestricted -Force</code> 
This allows scripts to be run as they are blocked by default.
Now download **all** the files and run the ps1 file as administrator, and follow the steps. 

In the prompt with: <code>Would you like to remove everything that was preinstalled on your Windows Machine? Select Yes to remove everything, or select No to remove apps via a blacklist.</code>
It doesn't matter what you choose as it will always use the blacklist. This isn't finished yet, I just copied this from another repo and started editting this. The person who created this hasn't done a good job, so I'm fixing things.

I rewrote some code as it wasn't correct. Original code: https://github.com/Sycnex/Windows10Debloater/
