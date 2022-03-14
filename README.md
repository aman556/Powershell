# Powershell
Power-shell commands

# How to print output on powershell
To print the output on powershell we use `Write-Host` command.

```
Write-Host
     [[-Object] <Object>]
     [-NoNewline]
     [-Separator <Object>]
     [-ForegroundColor <ConsoleColor>]
     [-BackgroundColor <ConsoleColor>]
     [<CommonParameters>]
 ```
 
 Now we will explore each flag one by one.
 
 ```
 Write-Host "My first output"
 ```
 
 ## -NoNewline
 NoNewline flag help in omitting the new line and continue writing in the same line.
 
```
Write-Host "Now we will use -NoNewline flag." -NoNewline
Write-Host "Notice no new line created the same line continues."
```
