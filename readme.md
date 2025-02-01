(Invoke-WebRequest -Uri "https://raw.githubusercontent.com/wentywenty/proxy_changer/main/install.ps1").Content | Invoke-Expression -ArgumentList "127.0.0.1", "7890"

