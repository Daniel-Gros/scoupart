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


