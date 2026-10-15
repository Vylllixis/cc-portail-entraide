Moitrier-Cabodi Théo

* 36c2233 (HEAD -> main, origine/main, origine/hotfix/duree, hotfix/duree) wqRevert "Mettre à jour la durée de référence des créneaux"
*   3cedad5 :bug: fix(merge): merge branch feature/tutorat
|\  
| * a43f314 (origine/feature/tutorat, feature/tutorat) Préciser le tutorat individuel sur inscription
* |   400e253 Merge branch 'feature/contact'
|\ \  
| * | 503a6a5 (origine/feature/contact, feature/contact) ✨ feat(link): make the contact email address clickable
| |/  
* / cc963bf (origine/feature/acceuil, feature/acceuil) 📝 feat(display): update the announcement for office hours
|/  
* 76184a8 Ajouter le conseil de vérification du compteur
* b88cc98 Mettre à jour la durée de référence des créneaux
* 4a266e1 Créer le portail et le simulateur de créneaux

### Étapes réalisées avec Git et GitHub

1. Création du repository sur GitHub.
2. Liaison du repository local avec le repository distant grâce à `git remote add origine "URL"`.
3. Création et utilisation des branches `feature/accueil` et `feature/contact` pour effectuer les modifications séparément.
4. Publication de `feature/contact` sur GitHub avec `git push --set-upstream origine feature/contact`.
5. Retour sur `main` et fusion successive des branches `feature/accueil` et `feature/contact`.
6. Fusion de `feature/tutorat` dans `main`. Un conflit est apparu dans `index.html`. Après résolution du conflit, j'ai validé la fusion avec un commit, puis publié les modifications sur GitHub.
7. Création de la branche `hotfix/duree` depuis `main`.
8. Annulation ciblée du commit contenant l'erreur de durée avec `git revert b88cc98bf3fae11998895be8365305f22b2cc49c`. Cette opération a créé un nouveau commit d'annulation sans réécrire l'historique.
9. Fusion de `hotfix/duree` dans `main`, puis publication de la branche principale sur GitHub.
10. Vérification de la présence des branches sur GitHub et publication des branches manquantes avec `git push -u origine nom_de_la_branche`.

Utilisation de l'intelligence artificielle pour corriger et améliorer la rédaction du fichier Explication.md.