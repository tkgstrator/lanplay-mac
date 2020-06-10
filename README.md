# lanplay-mac


## Install Homebrew, libpcap, switch-lan-play

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
brew install libpcap
brew install switch-lan-play
sudo reboot
```

## Run LanPlay

```bash
git clone https://github.com/tkgstrator/lanplay-mac
cd lanplay-mac
chmod +x lan-play
sh lanplay_jp.sh
```
