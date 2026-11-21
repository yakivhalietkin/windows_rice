# The Apps setup. The all-powerfull scoop.

So this will be a simple list of commands to be run to get everything I need. Maybe I will make a script later. But not now.

## scoop

Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
Invoke-RestMethod -Uri https://get.scoop.sh | Invoke-Expression

scoop install git
scoop install main/winget
scoop install main/winget-ps
scoop bucket add extras
scoop install extras/vcredist2022
scoop install main/btop
scoop install extras/discord
scoop install main/fastfetch
scoop install extras/feishin
scoop bucket add versions
scoop install versions/lightshot
scoop install extras/notepadplusplus
scoop install extras/notesnook
scoop install extras/obs-studio
scoop install extras/telegram
scoop install main/vim
scoop install extras/windows-terminal
scoop install extras/yasb
scoop install versions/windowsdesktop-runtime-8.0

winget install Brave.Brave 
winget install Valve.Steam
winget install Tailscale.Tailscale
winget install Nextcloud.NextcloudDesktop

### for nvidia
scoop install extras/tinynvidiaupdatechecker