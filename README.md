# Metasploit Framework 6 in Termux
[![GitLab Testing status](https://gitlab.com/gushmazuko/metasploit_in_termux/badges/master/pipeline.svg)](https://gitlab.com/gushmazuko/metasploit_in_termux/-/pipelines) ![GitHub Repo stars](https://img.shields.io/github/stars/gushmazuko/metasploit_in_termux?style=social) [![](https://img.shields.io/badge/GitLab-Mirror-succes?link=https://gitlab.com/gushmazuko/metasploit_in_termux)](https://gitlab.com/gushmazuko/metasploit_in_termux)

![Metasploit 6 running](https://i.imgur.com/yLFQhvP.png)

## How to Install
### Auto
```bash
source <(curl -fsSL https://kutt.it/msf)
```

### Manual
```bash
apt update && apt upgrade && apt install wget && apt install ruby && wget https://raw.githubusercontent.com/RSecxXx/RSecxXx-MetasPloit/master/metasploit.sh && chmod +x metasploit.sh && ./metasploit.sh
```

## Launch metasploit
After installation complete execute:
```bash
msfconsole
```
