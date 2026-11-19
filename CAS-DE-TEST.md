# Cas de test

Cas vérifiés avec l’outil (version 1.0). À refaire après chaque modification. Point de départ de chaque cas : réponses par défaut (personne privée, pas de tâche déléguée, pas d’infrastructure critique, pas d’assujetti FINMA, données personnelles touchées, cyberattaque, pas de RGPD, aucune case de la matrice choisie).

## Protection des données

| # | Données | Résultat attendu |
|---|---|---|
| 1 | Réponses par défaut | PFPDT : à évaluer ; personnes concernées : à évaluer ; OFCS : facultatif ; aucune annonce requise, 2 points à évaluer |
| 2 | Matrice : gravité maximale, probabilité importante | PFPDT : requis, dans les meilleurs délais ; 1 annonce requise |
| 3 | Matrice : gravité négligeable, probabilité limitée | PFPDT : non requis ; personnes concernées : en principe non requis |
| 4 | Matrice : gravité limitée, probabilité limitée (produit 4) | PFPDT : à évaluer |
| 5 | Aucune donnée personnelle | PFPDT : non requis ; pas de carte « personnes concernées » |
| 6 | Sous-traitant | Responsable du traitement : requis ; pas de carte PFPDT |
| 7 | Sous-traitant, RGPD applicable | Carte RGPD « par le responsable », non comptée comme annonce requise |
| 8 | RGPD applicable, découverte le vendredi 20 novembre 2026 à 18h00 | Autorité de l’UE : requis, jusqu’au lundi 23 novembre à 18h00 |

## Organes publics et tâches déléguées

| # | Données | Résultat attendu |
|---|---|---|
| 9 | Organe cantonal ou communal | Autorité cantonale : voir le droit cantonal ; PFPDT : non compétent ; la question des tâches déléguées disparaît |
| 10 | Organe fédéral, risque élevé | PFPDT : requis |
| 11 | Privé, tâches déléguées par un canton | Carte supplémentaire « autorité cantonale (tâches publiques déléguées) » : à vérifier |
| 12 | Privé, tâches déléguées par la Confédération | Carte « autorité fédérale délégante » : à vérifier |

## Cybersécurité et FINMA

| # | Données | Résultat attendu |
|---|---|---|
| 13 | Infrastructure critique, cyberattaque, aucun critère coché | OFCS : facultatif |
| 14 | Infrastructure critique, cyberattaque, un critère coché, découverte le vendredi 20 novembre 2026 à 18h00 | OFCS : requis, jusqu’au samedi 21 novembre à 18h00 |
| 15 | Infrastructure critique « pas sûr », un critère coché | OFCS : à vérifier |
| 16 | Infrastructure critique, erreur ou panne | OFCS : facultatif ; les critères ne sont pas affichés |
| 17 | Assujetti FINMA, attaque grave, découverte le vendredi 20 novembre 2026 à 18h00 | FINMA : annonce jusqu’au samedi 21 à 18h00, rapport jusqu’au lundi 23 à 18h00 |
| 18 | Cas 17 avec gravité moyenne ou élevée | FINMA : annonce jusqu’au lundi 23 à 18h00, rapport jusqu’au mercredi 25 à 18h00 |
| 19 | Assujetti FINMA, gravité faible | FINMA : à évaluer |
| 20 | Assujetti FINMA, erreur ou panne | FINMA : à évaluer (obligation générale) |

## Interface

| # | Données | Résultat attendu |
|---|---|---|
| 21 | Passage du français à l’anglais après saisie | Les réponses et le résultat sont conservés |
| 22 | Réinitialiser | Retour aux réponses par défaut |
| 23 | Affichage sombre | Textes et matrice lisibles |
