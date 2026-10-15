# Rapport de contrôle continu

- **Nom / Prénom** : Cotte Axel
- **Commits** : a43f314 (feature/tutorat) Préciser le tutorat individuel sur inscription
* 76184a8 (HEAD -> main) Ajouter le conseil de vérification du compteur
* b88cc98 Mettre à jour la durée de référence des créneaux
* 4a266e1 Créer le portail et le simulateur de créneaux


* c5d0b25 (HEAD -> main, hotfix/duree) Revert "Mettre à jour la durée de référence des créneaux"
*   8ef7571 merge integration de feature/tutorat et resolution du conflit
|\  
| * a43f314 (feature/tutorat) Préciser le tutorat individuel sur inscription
* |   8b77cee Merge branch 'feature/contact'
|\ \  
| * | e0678e1 (feature/contact) Ajout lien cliquable mail
| |/  
* / b56b5af (feature/accueil) Ajout de la mention sans inscription dans les permanences
|/  
* 76184a8 Ajouter le conseil de vérification du compteur
* b88cc98 Mettre à jour la durée de référence des créneaux
* 4a266e1 Créer le portail et le simulateur de créneaux
~

## 3. Annulation ciblée de la durée
- **Commit erroné annulé** : `b88cc98bf3fae11998895be8365305f22b2cc49c`
- **Vérification** : Le conseil dans `README.md` est bien conservé et la durée unitaire est revenue à 20 minutes.

## 4. Tests fonctionnels
- **Simulation** : 2 clics sur « Ajouter » donnent bien 2 créneaux et 40 minutes. « Recommencer » remet le compteur à 0.
