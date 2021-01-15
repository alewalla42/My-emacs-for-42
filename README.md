.emacs.d
========
.emacs d'origine https://github.com/Peltoche/.emacs.d

# Warning

This repos is no longer maintained. 

# Description

Configuration Emacs **Special 42** avec commentaires

**WARNING** *Some of these configurations and/or commands may be specific to a certain setup (42 school), some commands might useless to others or could lead to troubleshooting*


# Installation

### Si Emacs n'est pas installe

```
brew install emacs
```

### Si HomeBrew n'est pas installe
```
rm -rf $HOME/.brew && git clone --depth=1 https://github.com/Homebrew/brew $HOME/.brew && export PATH=$HOME/ .brew/bin:$PATH && brew update && echo "export PATH=$HOME/.brew/bin:$PATH" >> ~/.zshrc
```

#### Proteger les anciennes configs

```
cd ~ ; mv .emacs .emacs.old ; mv .emacs.d/ .emacs.d.old/;

```
*Vous pourrez toujours revenir a votre ancienne config en enlevant les .old*

#### Telecharger le github dans le home:

```
cd ~ ; git clone https://github.com/alewalla42/My-emacs-for-42.git .emacs.d;

```
*Pensez a cloner de temps en temps si vous voulez profiter des nouvelles trouvailles*

#### Deplacer le .myemacs et le .emacs dans le home

```
cd ~/.emacs.d/ ; cp emacs ~/.emacs;

```
##### Enjoy !


