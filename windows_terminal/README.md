# Windows Terminal Configuration

## Install [oh-my-posh](https://ohmyposh.dev/)

```powershell
winget install JanDeDobbeleer.OhMyPosh -s winget
```

```powershell
Set-ExecutionPolicy RemoteSigned

New-Item -Path $PROFILE -Type File -Force

notepad $PROFILE

oh-my-posh init pwsh | Invoke-Expression

. $PROFILE
```

## [Themes](https://ohmyposh.dev/docs/themes)

### Set a theme

```powershell
oh-my-posh init pwsh --config "$env:POSH_THEMES_PATH/atomicBit.omp.json" | Invoke-Expression
```
