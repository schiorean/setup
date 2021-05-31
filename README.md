# setup
New computer setup (steps, toys, dotfiles etc).

## WSL2

### Prevent idle SSH connections from disconnecting

Edit /etc/ssh/ssh_config
```
ServerAliveInterval 120
TCPKeepAlive yes
```

## PHPStorm

Exlude PHPStorm processes from Windows Defender https://intellij-support.jetbrains.com/hc/en-us/articles/360005028939-Slow-startup-on-Windows-splash-screen-appears-in-more-than-20-seconds
