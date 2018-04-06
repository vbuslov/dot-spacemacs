# Spacemacs Config

This is my spacemacs config to use it run the following in your home dir:

    git clone git@github.com:vbuslov/dot-spacemacs.git ~/.config/spacemacs
    
    mkdir -p .config/systemd/user
    ln ~/.config/spacemacs/emacs.service ~/.config/systemd/user/emacs.service
    systemctl enable --now --user emacs.service
    
    ln -s ~/.config/spacemacs/.spacemacs ~/.spacemacs
