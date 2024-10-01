**Voici les commandes markdwon et leurs équivalences en powershell**


_cp_ : Copy-Item "C:\users\Admin\powershell\nana.txt" -Destination "C:\users\Admin\"

_rm_ : Remove-Item "C:\users\Admin\nana.txt"

_cd_ : Set-Location "C:\users\Admin\powershell"

_mkdir_ : New-Item -Path "C:\users\Admin\" -Name "powershell" -ItemType Directory

_man_ : Get-Help Remove-Item

_history_ : History

_alias_ : New-Alias -Name rem -Value Remove-Item

_cat_ : Get-Content "C:\users\Admin\powershell\nana.txt"
