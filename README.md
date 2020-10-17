# windows-debloat
```
 These are some powerful scripts/applications/utilities to debloat a new Windows installation.  
```  
## How To Run the Windows10Debloater.ps1 and the Windows10DebloaterGUI.ps1 files
```
There are different methods of running the PowerShell script. The methods are as follows:

First Method:

1) Download the .zip file on the main page of the github and extract the .zip file to your desired location
2) Once extracted, open PowerShell (or PowerShell ISE) as an Administrator
3) Enable PowerShell execution
<code>Set-ExecutionPolicy Unrestricted -Force</code>
4) On the prompt, change to the directory where you extracted the files:
  e.g. - cd c:\temp
5) Next, to run either script, enter in the following:
  e.g. - .\Windows10DebloaterGUI.ps1
  

Second Method:

1) Download the .zip file on the main page of the github and extract the .zip file to your desired location
2) Right click the PowerShell file that you'd like to run and click on "Run With PowerShell"
3) This will allow the script to run without having to do the above steps but Powershell will ask if you're sure you want to run this script.

Remember this script NEEDS to be run as admin in order to function properly.  
```  
# How To Run the Windows10SysPrepDebloater.ps1 file
```
For the WindowsSysPrepDebloater.ps1 file, there are a couple of parameters that you can run so that you can specify which functions are used. The parameters are:
-SysPrep, -Debloat. 

To run this with parameters, do the following:

1) Download the .zip file on the main page of the github and extract the .zip file to your desired location
2) Once extracted, open PowerShell (or PowerShell ISE) as an Administrator
3) On the prompt, change to the directory where you extracted the files:
  e.g. - cd c:\temp
4) Next, to run either script, enter in the following:
  e.g. - .\Windows10SysPrepDebloater.ps1 -Sysprep, -Debloat -Privacy
```
