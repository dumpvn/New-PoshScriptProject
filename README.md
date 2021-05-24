# New-PoshScriptProject
New powershell script project


```powershell
$Parms = @{
    Path = "C:\workspace\New-PoshScriptProject\Source\New-PoshScriptProject.ps1"
    Version = "0.1"
    Author = "phuc.vinh@outlook.com"
    Description = "Powershell Script Project"
    CompanyName = "PhucNguyen"
    ProjectUri = "https://github.com/dumpvn/New-PoshScriptProject"
    LicenseUri = "https://raw.githubusercontent.com/dumpvn/New-PoshScriptProject/main/LICENSE"
}
New-ScriptFileInfo @Parms
Get-Content -Path C:\workspace\New-PoshScriptProject\Source\New-PoshScriptProject.ps1
```
