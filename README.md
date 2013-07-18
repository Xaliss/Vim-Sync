Vim-Sync
========

Ma  machine partout avec moi.

Ici on place les plugins installées sur ma machine Root avec leur reperes sur git pour mise a jour auto.
Et d'ici je peux mettre toute machine à mes spécifications avec un seul appel a Git.
Plus besoin de clé usb sauf, si absence de connexion web.

/////////
/ Usage: Merci à Neil Drew  à vimCast.org
/////////

Créer les liens symboliques
en faisant:

    ln -s ~/.vim/vimrc ~/.vimrc
    ln -s ~/.vim/gvimrc ~/.gvimrc

Basculer sur  `~/.vim` et 
chargez les submodules en faisant:

    cd ~/.vim
    git submodule init
    git submodule update
