# mullvad-deb
A Debian repository for Mullvad package updates

You can configure Debian to use this repository as follows:

```
sudo curl -s -o /etc/apt/trusted.gpg.d/rail5.gpg "https://mv.rail5.org/rail5.gpg"

sudo curl -s -o /etc/apt/sources.list.d/mullvad-rail5.list "https://mv.rail5.org/mullvad-rail5.list"

sudo apt update
```

Although, you really shouldn't trust third-party packages distributed by fourth-party strangers. I happen to know that I'm not altering these packages, but how do you?
