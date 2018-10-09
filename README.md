# DirectAdmin - Skin Evolution - Traduction Française 
## DirectAdmin - Evolution Skin - French Translation
Traduction française pour le skin Evolution pour le panel adminstrateur DirectAdmin

En date du 07 octobre 2018, la traduction est complète à 56%.
De nouvelles traductions sont ajoutées chaque semaine.

Tout le monde est libre participer et fournir des améliorations à la traduction française.

Vous pouvez soumettre vos amélioration via un Pull requests ou bien nous pouvons en discuter dans la section Issues.

Le fichier de traduction actuel est basé sur DirectAdmin: 1.54.1. 

Le fichier dictionary.pot et fr.po est basé sur la version du skin Evolution: 57d79f90beecb6976abc42a577f661ef16016738

## Installation
Rendez-vous dans le répertoire lang de votre installation du skin Evolution (généralement /usr/local/directadmin/data/skins/evolution/lang/) et télécharger la dernière version de la traduction française à l'aide de wget avec la commande suivante:

```bash
wget https://raw.githubusercontent.com/webalternative/DirectAdmin-Evolution-FR/master/fr.po -O fr.po

```

## Mise-à-jour automatique
Vous pouvez ajouter une tâche cron pour automatiquement télécharger la dernière version disponible tous les 5 jours.

```bash
0 0 */5 * * wget https://raw.githubusercontent.com/webalternative/DirectAdmin-Evolution-FR/master/fr.po -O /usr/local/directadmin/data/skins/evolution/lang/fr.po
```
Assurez-vous d'avoir ajusté le répertoire de votre installation du skin Evolution dans la commande de la tâche cron.


### Contributions Importantes
- Philippe Robert - https://webalternative.net - philippe.robert (at) webalternative (.) net
- Idescap 
