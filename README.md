# Windows_API_Tools
（如不免杀，Email）

## AddUser.exe 

作用：添加管理员  

用法：AddUser.exe Username Password

## Guest_Activate.exe

作用： 激活guest，并加入管理员组

用法：Guest_Activate.exe Password

## Start_Rdp.exe

作用：开启rdp服务

用法： Start_Rdp.exe

## User_Del.exe

作用：删除用户

用法：User_Del.exe Username

## Lsass_Dump.exe(64位系统使用)

作用：创建 lsass.exe 的转储文件，配合 mimikatz 使用

用法：Lsass_Dump.exe

## Lsass_Dumpx86.exe(32位系统使用)

作用：创建 lsass.exe 的转储文件，配合 mimikatz 使用

用法：Lsass_Dumpx86.exe

## Get_WinPass.exe

作用：抓取 Windows 密码，实现 Mimikatz sekurlsa::wdigest 功能，（Win2008 以上需要开启 UseLogonCredential）

用法：Get_WinPass.exe

