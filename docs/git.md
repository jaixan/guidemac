# GIT

# Installation de GIT sur Mac

## Installation de XCode Command Line Tools

Avant l'installation de Homebrew, il faut installer les outils de ligne de commande XCode. Pour l'installer, ouvrir le terminal et exécuter cette commande :  

```
xcode-select --install  
```

## Installation de Homebrew  

Homebrew est un gestionnaire de paquets (Package Manager) pour le Mac.  

Pour l'installer, ouvrir le terminal et exécuter cette commande :  

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

Suivre les indications dans le terminal.  

## Ajouter Homebrew au PATH  

Faire les commandes suivantes pour ajouter Homebrew au PATH de zsh :  

```
cd /opt/homebrew/bin/  
  
PATH=$PATH:/opt/homebrew/bin  
  
cd  
  
touch .zshrc  
  
export PATH="/opt/homebrew/bin:${PATH}" >> .zshrc  
```

## Installation de GIT  

Installer GIT avec Homebrew, faire la commande suivante dans le terminal :  

```
brew install git  
```

Vérifier si git est bien installé :  

```
git --version    
```

# Références  
[Installation de Homebrew](https://brew.sh)  
[Ajouter brew à zsh](https://stackoverflow.com/questions/65619529/fixing-zsh-command-not-found-brew-installing-homebrew)  
[Installation de git pour Mac](https://www.makeuseof.com/how-to-install-git-mac/)  
