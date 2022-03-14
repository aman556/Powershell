# Powershell
Power-shell commands

# How to print output on powershell
## Write-Host
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
 
 ### -NoNewline
 NoNewline flag help in omitting the new line and continue writing in the same line.
 
```
Write-Host "Now we will use -NoNewline flag." -NoNewline
Write-Host "Notice no new line created the same line continues."
```
![-NoNewline output](https://github.com/aman556/Powershell/blob/main/images/Screenshot%202022-03-14%20at%2010.12.08%20AM.png)

## -Separator
If we have to some set of values with a separator/symbol between them then we can use `-Separator` flag.
```
Write-Host (99,45,36,27) -Separator " > "
```
![-Separator output](https://github.com/aman556/Powershell/blob/main/images/-Separater.png)
