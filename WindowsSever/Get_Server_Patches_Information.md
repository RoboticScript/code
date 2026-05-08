## Example 1: Get all hotfixes on the local computer
```PowerShell
Get-HotFix | Sort-Object -Property InstalledOn -Descending
```

## Example 2: Get hotfixes from multiple computers filtered by a string
```PowerShell
Get-HotFix -ComputerName Server01, Server02 -Credential Domain01\admin01
```
