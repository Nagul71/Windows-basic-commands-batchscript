# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file
Save each script in a file with a .bat extension.
Ensure you have the necessary permissions to perform the operations.
Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.


## COMMAND

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.
```
mkdir %userprofile%\Desktop\MyLab
cd %userprofile%\Desktop\MyLab
type nul > MyFile.txt

```

## OUTPUT:

![image](https://github.com/Nagul71/Windows-basic-commands-batchscript/assets/118661118/022ab43b-9a59-45e2-9ec4-c70a3c7a6ae2)




## COMMAND

List the contents of the "MyLab" directory.
```
dir %userprofile%\Desktop\MyLab
```

## Output:

![image](https://github.com/Nagul71/Windows-basic-commands-batchscript/assets/118661118/bd2b0678-2876-437d-988a-cd4373545ea7)




## COMMAND

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.

Move the "MyLab" directory to the "Documents" folder.

```
mkdir %userprofile%\Desktop\Backup
copy MyFile.txt %userprofile%\Desktop\Backup

```


## OUTPUT
![image](https://github.com/Nagul71/Windows-basic-commands-batchscript/assets/118661118/98adf3d9-8753-4e5c-b913-d0f14e4c4432)




## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

```
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup

```
## OUTPUT:
![image](https://github.com/Nagul71/Windows-basic-commands-batchscript/assets/118661118/557b4214-b7c7-440f-91ca-8819a1febf90)



```
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
del %userprofile%\Documents\*.docx

```







## OUTPUT:
![image](https://github.com/Nagul71/Windows-basic-commands-batchscript/assets/118661118/4f37dd16-d8e6-449f-81d2-b5b3a2fb70fe)







# RESULT:
The commands/batch files are executed successfully.

