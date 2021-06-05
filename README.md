# Hugo
1. 安裝Choco https://chocolatey.org/install
    * open powershell.exe 
    ```bash
    Get-ExecutionPolicy
    ```
    ```bash
    Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
    ```
2. 安裝hugo
* in powershell.exe
```bash
choco install hugo -confirm
```
* check
```bash
hugo version
```
## Hugo command
* 建立新專案
```bash
hugo new #projectnem
```

* 輸出靜態文件
```bash
hugo server -D
```

# Theme User documentation
* https://github.com/kakawait/hugo-tranquilpeak-theme/blob/master/docs/user.md