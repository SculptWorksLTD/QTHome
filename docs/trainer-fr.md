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

## Signalements

Les bêta-testeurs utilisent QTHome comme d'habitude et, quand quelque chose ne va pas ou qu'ils ont une idée, appuient sur **Signaler** : cela arrive anonymement, avec le journal du programme utile pour comprendre le problème.

Réalisé par IU1MVI.
