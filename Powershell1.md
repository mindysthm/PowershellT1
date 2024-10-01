Markdown,Powershell
cp,Copy-Item "C:\users\Admin\powershell\nana.txt" -Destination "C:\users\Admin\"
rm,Remove-Item "C:\users\Admin\nana.txt"
cd,Set-Location "C:\users\Admin\powershell"
mkdir,New-Item -Path "C:\users\Admin\" -Name "powershell" -ItemType Directory
man,Get-Help Remove-Item
history,History
alias,New-Alias -Name rem -Value Remove-Item
cat,Get-Content "C:\users\Admin\powershell\nana.txt"
