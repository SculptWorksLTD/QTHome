# QTHome — guide des bêta-testeurs

Plus besoin d'un programme séparé : QTHome fait maintenant le travail du Trainer.

## Comment l'activer

1. Ouvrez QTHome et allez dans **Réglages › Aider à améliorer le CW**.
2. Cochez **Aider à améliorer le CW (anonyme)**.
3. Choisissez l'**entrée audio de la radio** (ex. « USB Audio CODEC »).
4. Si vous le souhaitez, autorisez aussi l'envoi d'**extraits audio** des cas douteux.

Écoutez ensuite le CW comme d'habitude. Toutes les 30 secondes deux décodeurs de QTHome relisent ce qui est arrivé et les
indicatifs sont vérifiés avec le Reverse Beacon Network (RBN). Si le skimmer de la fonction CW est allumé (clé SDR), ses
indicatifs sont aussi vérifiés toutes les 2 minutes. **Il n'émet jamais et ne commande pas la radio.**

FT8 et FT4 ne sont plus nécessaires : QTHome les décode avec le moteur de WSJT-X, téléchargé seul la première fois.

## Ce qui part vers QTHome

- Seulement les cas utiles : désaccords entre les deux décodeurs, indicatifs jamais entendus par le RBN, stations fortes non lues.
- **Jamais votre indicatif**, ni l'adresse IP, le nom de l'ordinateur ou vos dossiers ; le locator seulement à 4 caractères.
- Extraits audio seulement si vous l'avez accepté, 6 par heure au plus, effacés après 12 mois.
- Si l'envoi n'est pas encore actif ou sans internet, les cas attendent sur l'ordinateur et partent seuls plus tard.

## Licence gratuite pour les testeurs

Sur la même page : vos **heures d'écoute**, les barres vers la licence et votre **code testeur** (QT-XXXX-XXXX, anonyme).
Saisissez-le dans le formulaire de la page [Beta tester](https://iu1mvi.jimdofree.com/beta-tester/) avec votre indicatif.

- **10 heures** d'écoute : QTHome PRO gratuit pendant un an.
- **100 heures** sur au moins 3 mois différents : licence Fondateur, PRO gratuit pour toujours.

Seuls comptent les passages où du CW arrive vraiment.

Réalisé par IU1MVI.
