# DEs-UI packages

The apt repository for [DEs-UI](https://github.com/coxy-trophy/des-ui), a sci-fi
terminal desktop. For Ubuntu 26.04 on 64-bit Intel and AMD machines.

    curl -fsSL https://coxy-trophy.github.io/des-ui-apt/des-ui.gpg | sudo tee /usr/share/keyrings/des-ui.gpg >/dev/null
    echo "deb [signed-by=/usr/share/keyrings/des-ui.gpg] https://coxy-trophy.github.io/des-ui-apt ./" | sudo tee /etc/apt/sources.list.d/des-ui.list
    sudo apt update
    sudo apt install des-ui

Then log out and choose **DEs-UI** from the session menu on the login screen.
Updates arrive with the rest of the system's, through `sudo apt upgrade`.

The packages are signed with the key
`9095FB60A1CE0BC385FA0FF8CD808CD1DDFCF0DA`.
