# VotingProject

Un contrat intelligent simple en Solidity qui permet de mettre en place un système de vote.

Composé en plusieurs parties :

0. L'administrateur est la personne qui déploit le contrat intelligent
1. Inscription à la whitelist par l'administrateur
2. Ouverture d'une session de propositions par l'administrateur
3. Les whitelistés proposent une proposition chacun
4. Fermeture de la session de propositions par l'administrateur
5. Ouverture d'une session de vote par l'administrateur
6. Inscription de voteurs
7. Consultation des propositions par les voteurs
8. Chaque voteur séléctionne une proposition par son ID (commençant par 0)
9. Fermeture de la session de vote par l'administrateur
10. L'administrareur lance le décompte des voix
