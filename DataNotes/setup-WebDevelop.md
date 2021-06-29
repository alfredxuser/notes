[Root](../index.md) -> [Setups](Setups.md) -> Web develop basic

# SETUP / web develop

---
### Setup 1 - [Browser Reload Linux][1]

- [ ] Open html file on firefox browser

- [ ] Browser Reload; manual reload `:FirefoxReload` | auto reload `:FirefoxReloadStart`

- [ ] Hit `Ctrl Enter` to avoid conflicts with terminal (tmux) if doesn't auto reload

- [ ] Before closing the browser, kill plugin Browser auto reload `:FirefoxReloadStop`

###### Ss; original source
![Google Drive](https://drive.google.com/uc?export=view&id=12F2orB50fZJa0aXl-FnBQRSp_HJL04Qn)


---
### Setup 2 - [Browser-sync][2]

- [ ] Open a terminal

- [ ] Opt 1: ` $ browser-sync start --server /home/user/path/to/start/server/ --watch '*' --browser firefox --port 3000`

- [ ] Opt 2: ` $ browser-sync start --server --watch '*' --browser firefox --port 3000`

- [ ] [Allow browser-sync by UFW firewall.](UFW.md)

- [ ] Open in a smartphone the localhost by typing the ip address.

---
### Setup 3 - [Live-server][3]

[Root](../index.md) -> [Setups](Setups.md)

<!--Referenced links-->
[1]:https://github.com/lordm/vim-browser-reload-linux "Browser Reload Linux Repository"
[2]:https://www.browsersync.io/docs/command-line "Oficial site for Browser Sync"
[3]:https://github.com/ "Liver Server Repository"
