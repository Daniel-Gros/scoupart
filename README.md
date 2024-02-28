# scoupart
évaluation sur un projet fictif de site web et webmobile d'une diététicienne fictive
Le projet est codé en PHP avec Symfony

# Protocole pour faire fonctionner le projet en local

## Pour faire fonctionner le projet en local vous aurez besoin de certains prérecquis que je vais vous expliquer ci-dessous:  
Pour commencer vous devrez effectuer plusieurs téléchargements ou commande sur powershell (pour Windows) / terminal (pour Mac) :  
  
 - l'IDE de votre choix (Visual studio code, PHP storm etc...)

 - Git que vous pouvez installer en cliquant [ici](https://git-scm.com/downloads)
  
 - Xampp que vous pouvez télécharger en cliquant [ici](https://www.apachefriends.org/fr/index.html)
**Vous n'aurez pas besoin de télécharger PHP** car il sera intégré dans Xampp lors de son installation nous verrons plus tard comment le configurer  
  
 - Ouvrir votre powershell/terminal (version 5.1 ou supérieur pour powershell) et tapez :
     
   >  Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser  
   > Invoke-RestMethod -Uri https://get.scoop.sh | Invoke-Expression

Cela installera scoop sur votre machine qui est un installer en ligne de commande

# Mise en place de l'environnement PHP

Une fois les prérecquis logiciels faits, vous devrez configurer PHP sur votre machine.  
Pour se faire vous devrez vous rendre dans le PHP installé avec Xampp au chemin qui doit ressembler à ceci :  

**C:\xampp\php**  

Vous y trouverez le fichier php.exe  
 - Faites un clic droit sur ce fichier, cliquez sur *copier en tant que chemin d'accès* (ctrl + shift + C sur Windows)

Vous allez ensuite devoir modifier le **Path** de vos variables d'environnement en suivant cette procédure :  
*Sur Windows**
 - Cliquer sur le menu démarrer.
 - Dans la barre de recherche écrivez "variables d'environnement"
 - Cliquez sur l'icône "Modifier les variables d'environnement système"
 - Vous êtes à présent dans le menu des **Propriétés système**
 - Cliquez sur le bouton "Variables d'environnement..."
 - Dans le 1er bloc appelé "Variables utilisateurs pour *username*" , cliquez sur **Path**, puis cliquez sur le bouton "Nouvelle..."
 - Appelez votre variable PHP dans le Nom de la variable
 - Faites un ctrl + V (chemin d'accès de php.exe vu plus haut) dans "Valeur de la variable et cliquez sur OK

Vous avez configuré correctement la variable d'environnement pour faire fonctionner PHP sur votre machine.

# XAMPP

Vous allez ensuite démarrer Xampp que vous avez préalablement installé sur votre machine.  
Une fois Xampp démarré vous devrez cliquer sur le bouton config à la ligne **Apache**, puis cliquez sur PHP(php.ini).  
Ceci vous ouvrira un bloc-note par défaut du fichier php.ini , faites un ctrl + F et dans la barre de recherche écrivez zip puis Entrée  
vous allez arriver sur une ligne qui doit ressembler à : **;extension=zip** , retirez le ";" et sauvegardez le fichier, cela décommentera la ligne et rendra l'extension zip utilisable
dans votre workspace.  

Retournez ensuite sur Xampp et cliquez sur les boutons Start pour Apache et MySQL.

