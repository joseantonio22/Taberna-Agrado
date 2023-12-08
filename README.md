# Taberna-Agrado
Download nodejs version v18.19.0
    https://nodejs.org/download/release/v18.19.0/node-v18.19.0-linux-x64.tar.gz

Unzip and move to helpers folder
    mkdir ~/Documents/helpers
    cd ~/Downloads
    -zxvf node-v18.19.0-linux-x64.tar.gz
    rm node-v18.19.0-linux-x64.tar.gz
    sudo mv node-v18.19.0-linux-x64 ../Documents/helpers

Export binaries into PATH
    vi ~/.zshrc
        export PATH="$HOME/Documents/helpers/node-v18.19.0-linux-x64/bin:$PATH"

