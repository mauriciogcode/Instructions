# Instructions


#Box Drive Login Loop
Close app
reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Box\Box" /v "LoginWithExternalBrowser" /t REG_DWORD /d 0 /f
Run App


