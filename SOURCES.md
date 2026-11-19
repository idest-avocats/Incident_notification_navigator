# Sources

© 2026 id est avocats Sàrl ; texte sous licence [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/deed.fr). Version 1.0 (beta), textes consultés en novembre 2026.

## Textes légaux

| Texte | Utilisation dans l’outil |
|---|---|
| Loi fédérale sur la protection des données (LPD, RS 235.1), [Fedlex](https://www.fedlex.admin.ch/eli/cc/2022/491/fr) | Champ d’application : personnes privées et organes fédéraux (art. 2) ; personne chargée de tâches publiques de la Confédération assimilée à un organe fédéral (art. 5 let. i) ; annonce des violations de la sécurité des données au PFPDT, information du responsable par le sous-traitant et information des personnes concernées (art. 24) |
| Ordonnance sur la protection des données (OPDo, RS 235.11), [Fedlex](https://www.fedlex.admin.ch/eli/cc/2022/568/fr) | Contenu de l’annonce et documentation conservée au moins deux ans (art. 15) |
| Loi sur la sécurité de l’information (LSI, RS 128), [Fedlex](https://www.fedlex.admin.ch/eli/cc/2022/232/fr) | Obligation de signaler les cyberattaques contre les infrastructures critiques (art. 74a à 74h) : organisations visées (art. 74b), attaques à signaler (art. 74d), délai de 24 heures, amende de 100 000 francs au plus (art. 74h) ; signalements volontaires |
| Ordonnance sur la cybersécurité (OCyS) | Exemptions et modalités du signalement ; non reprises en détail |
| Loi sur la surveillance des marchés financiers (LFINMA, RS 956.1) | Obligation d’annoncer sans délai les faits d’importance substantielle (art. 29 al. 2) |
| Règlement (UE) 2016/679 (RGPD) | Notification dans les 72 heures et communication aux personnes concernées (art. 33 et 34) |

## Documents des autorités

| Source | Utilisation |
|---|---|
| FINMA, communication sur la surveillance 05/2020 | Annonce des cyberattaques touchant des fonctions ou données critiques dès une gravité moyenne ; annonce initiale dans les 24 heures, rapport dans les 72 heures |
| FINMA, communication sur la surveillance 03/2024 | Délais en jours ouvrables bancaires sauf attaque grave ; point de départ lors de l’identification par l’assujetti ou son prestataire ; annonce par téléphone ou courriel |
| PFPDT, formulaire d’annonce des violations de la sécurité des données | Canal de l’annonce |
| OFCS, Cyber Security Hub | Canal du signalement |

Aucun lien stable n’est donné pour les communications de la FINMA et pour l’OCyS ; ces documents se trouvent sur finma.ch et sur Fedlex.

## Choix de l’outil

- **Matrice de risque.** Gravité et probabilité sont notées de 1 à 4. Le risque est élevé lorsque le produit atteint 8, moyen de 4 à 6 et faible en dessous. Ces seuils sont un choix de l’outil et ne résultent pas de la loi. Un risque élevé donne une annonce requise au PFPDT ; un risque moyen ou non évalué donne « à évaluer », avec la mention qu’une annonce est indiquée en cas de doute.
- **Infrastructures critiques.** La liste affichée résume l’art. 74b LSI. L’utilisateur répond lui-même ; la réponse « pas sûr » donne « à vérifier ».
- **Organes publics.** Les autorités fédérales, cantonales et communales figurent à l’art. 74b LSI ; l’outil ne répond pas à leur place à la question de l’infrastructure critique.
- **Organes cantonaux et communaux.** La LPD ne s’applique pas ; l’outil renvoie à la loi cantonale, qu’il ne couvre pas.
- **Échéances.** Les délais de 24 et 72 heures sont calculés en heures calendaires, sauf pour la FINMA lorsque l’attaque n’est pas grave : les samedis et dimanches sont alors exclus. Les jours fériés ne sont pas pris en compte.
- **OFCS et prestataire.** Lorsque l’attaque est découverte par un prestataire, le point de départ du délai de la LSI n’est pas tranché ; l’outil compte depuis le moment saisi.
