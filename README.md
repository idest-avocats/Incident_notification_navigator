# Incident de sécurité – annonce aux autorités – id est avocats

Outil en ligne d’orientation, développé par id est avocats Sàrl : après un incident de sécurité, quelles autorités faut-il informer en droit suisse, à quelles conditions et dans quel délai.

> **Première orientation uniquement.** Le résultat dépend des réponses données et de règles simplifiées. Voir [AVERTISSEMENT.md](AVERTISSEMENT.md).

Version 1.0 (beta), novembre 2026. Historique : [CHANGELOG.md](CHANGELOG.md).

## Ce que fait l’outil

L’outil part du cas le plus simple, celui d’une personne ou d’une entreprise privée sans statut particulier. Chaque réponse ajoute ou retire une autorité.

- **Qui annonce** : personne ou entreprise privée, organe fédéral, organe cantonal ou communal ; délégataire de tâches publiques de la Confédération, d’un canton ou d’une commune ; infrastructure critique au sens de la loi sur la sécurité de l’information ; banque ou autre assujetti à la surveillance de la FINMA ; sous-traitant.
- **Ce qui s’est passé** : données personnelles touchées ou non, cyberattaque ou simple panne, critères de signalement de l’art. 74d LSI à cocher, gravité pour les fonctions et données critiques d’un assujetti FINMA.
- **Matrice de risque** : gravité des conséquences pour les personnes concernées et probabilité, sur quatre niveaux chacune. La case choisie donne un risque faible, moyen ou élevé, dont dépend l’annonce au PFPDT.
- **Résultat par autorité** : Préposé fédéral à la protection des données et à la transparence (PFPDT), personnes concernées, autorité cantonale de protection des données, Office fédéral de la cybersécurité (OFCS), FINMA et, en option, autorité de protection des données de l’UE (RGPD). Chaque carte indique le statut (requis, à vérifier, à évaluer, facultatif, non requis), le délai, le contenu et la base légale.
- **Échéances** : si la date et l’heure de découverte sont saisies, l’outil calcule les échéances de 24 et 72 heures, en jours ouvrables bancaires pour la FINMA lorsque l’attaque n’est pas grave.
- **Autres démarches** : plainte pénale, obligations contractuelles, cyberassurance.
- Interface en français et en anglais, affichage clair ou sombre, impression du résultat.

## Ce que l’outil ne couvre pas

Le droit cantonal de la protection des données n’est pas intégré : pour un organe cantonal ou communal et pour un délégataire de tâches publiques cantonales, l’outil renvoie à la loi cantonale. Les règles sectorielles (santé, télécommunications, assurances sociales), le secret professionnel, les obligations contractuelles et le droit étranger autre que le RGPD ne sont que mentionnés. La liste des infrastructures critiques est un résumé de l’art. 74b LSI et ne tient pas compte des exemptions de l’ordonnance sur la cybersécurité. Les jours fériés ne sont pas pris en compte dans le calcul des échéances.

## Utilisation

1. Indiquer qui annonce : organe public ou non, tâches publiques déléguées, infrastructure critique, surveillance de la FINMA.
2. Décrire l’incident : données personnelles, position dans la matrice de risque, sous-traitance, cyberattaque et critères applicables, gravité.
3. Le cas échéant, indiquer si le RGPD s’applique et le moment de la découverte.
4. Lire le résultat par autorité et l’imprimer au besoin.

## État du droit

Les textes ont été consultés en novembre 2026 (voir [SOURCES.md](SOURCES.md)). L’obligation de signaler les cyberattaques contre les infrastructures critiques est en vigueur depuis le 1er avril 2025. Les modifications de l’outil sont consignées dans [CHANGELOG.md](CHANGELOG.md).

## Protection des données

id est avocats ne collecte aucune donnée dans le cadre de l’utilisation de l’outil : l’évaluation est effectuée dans le navigateur et les réponses ne sont pas conservées. Seuls le mode d’affichage et la langue choisis sont mémorisés dans le stockage local du navigateur (clés `idest-notification:theme` et `idest-notification:lang`). L’outil est hébergé sur GitHub, qui peut collecter certaines informations, notamment au moyen de cookies, conformément à sa propre déclaration relative à la protection des données.

## Sources et tests

- Bases légales et choix de l’outil : [SOURCES.md](SOURCES.md).
- Cas de référence à refaire après chaque modification : [CAS-DE-TEST.md](CAS-DE-TEST.md).

## Licence

© 2026 id est avocats Sàrl.

Le code est distribué sous licence GNU Affero General Public License, version 3 ou toute version ultérieure (AGPL-3.0-or-later). Voir [LICENSE](LICENSE).

Les tableaux et textes juridiques (critères, seuils, résumés, documentation) sont en outre mis à disposition sous licence [Creative Commons Attribution – Pas d’utilisation commerciale 4.0 International (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/deed.fr). Attribution : « id est avocats Sàrl, Incident de sécurité – annonce aux autorités ».

---

## English

An online orientation tool for the notification of a security incident to the authorities under Swiss law. It starts from an ordinary private person or company and adds criteria through simple questions: public body (federal, or cantonal and communal with a reference to cantonal law), delegated public tasks, critical infrastructure under the Information Security Act, supervision by FINMA, processor. A severity and likelihood matrix gives the level of risk for the persons concerned. The result lists, for each authority (FDPIC, persons concerned, cantonal data protection authority, Federal Office for Cybersecurity, FINMA and, optionally, an EU data protection authority under the GDPR), whether a notification is required, the deadline, the content and the legal basis, and computes the deadlines from the time of discovery. French and English interface. The assessment runs in the browser and no data is stored. Code under the GNU AGPL 3.0 or any later version; legal texts also under CC BY-NC 4.0 (attribution: id est avocats Sàrl).
