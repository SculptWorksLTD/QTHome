# QTHome Trainer — guide des bêta-testeurs

QTHome Trainer écoute votre radio avec vous pendant que vous l'utilisez comme d'habitude
et compare le décodeur FT8/FT4 de QTHome avec celui de WSJT-X. Nous voyons ainsi où notre
décodeur se trompe, pour le corriger.

**Il n'émet jamais et ne commande jamais la radio.** Il lit seulement l'audio.

## Ce qu'il faut

- Un Mac (Apple ou Intel) ou un PC Windows 10/11.
- La radio reliée à l'ordinateur par le câble USB (sa carte son, ex. « USB Audio CODEC »).
- Rien d'autre : le Trainer télécharge seul, une fois, les outils WSJT-X nécessaires à la comparaison.

## Installer

1. Ouvrez la page des versions : <https://github.com/SculptWorksLTD/QTHome/releases/latest>
2. Téléchargez **QTHome-Trainer-Mac.pkg** (Mac) ou **QTHome-Trainer-Windows.zip** (Windows).
3. Mac : double-clic sur le .pkg. Si le Mac refuse : clic droit sur le fichier → **Ouvrir**.
   Windows : ouvrez le zip et lancez **QTHome Trainer.exe**. Si Windows avertit : **Informations complémentaires → Exécuter quand même**.

## La première fois

Un guide en 5 étapes s'ouvre :

1. **Bienvenue** : ce que fait le Trainer.
2. **Votre station** : le locator (4 ou 6 caractères, ex. JN45ab, seule la zone est utilisée), la radio, l'antenne.
3. **Audio de la radio** : choisissez la carte son de la radio et réglez une fréquence FT8 (ex. 14,074 MHz USB). Le niveau doit rester dans la zone verte. Sur Mac, la première fois, le système demande l'autorisation du micro : répondez **Autoriser**.
4. **Confidentialité** : ce que nous envoyons et si vous voulez envoyer des extraits audio.
5. **Tout est prêt** : appuyez sur **Commencer l'écoute**.

## La fenêtre

- **Vue d'ensemble** : l'écoute (entrée, niveau avec conseil, spectre), l'**État de la station** (audio, comparaison avec WSJT-X, radio, horloge, envoi) et vos chiffres. Les quatre voyants en haut disent la même chose d'un coup d'œil : vert c'est bon, jaune à regarder, rouge à corriger.
- **FT8 · FT4** : pour chaque créneau, les messages lus par QTHome et par WSJT-X (vert = les deux, rouge = WSJT-X seul, jaune = QTHome seul) et l'accord sur les derniers créneaux.
- **CW** et **Skimmer** : voir plus bas.
- **Réglages** : quoi écouter, usage de l'ordinateur, extraits audio, profil de la station, mises à jour.

Laissez le Trainer ouvert (même réduit) pendant que vous utilisez la radio : il reprend l'écoute seul à chaque démarrage.
L'horloge de l'ordinateur est vérifiée par internet : si elle est décalée, le Trainer corrige seul le découpage des créneaux.

## CW de la radio

Dans l'onglet **CW**, cochez **Lire le CW de la radio** (écoute allumée). Écoutez le CW comme d'habitude : toutes les
30 secondes deux décodeurs de QTHome relisent ce que vous avez entendu et les indicatifs sont vérifiés avec le
Reverse Beacon Network (RBN). Si The Rigger est allumé, le Trainer connaît aussi votre bande et la vérification est plus précise.

## Skimmer avec la clé SDR (Mac seulement, pour l'instant)

Il faut une clé RTL-SDR V3 ou V4 avec une antenne HF (la radio reste libre).
Dans **Réglages** cochez **Skimmer avec la clé SDR**, puis dans l'onglet **Skimmer** choisissez les bandes et appuyez sur
**Allumer le skimmer** : la clé chasse seule là où le RBN et le spectre montrent le plus de stations.
Dans le tableau ✓ signifie confirmé par le RBN, ? jamais entendu par le RBN.

## Ce qui part vers QTHome

- Seulement les cas utiles : signaux faibles, bandes chargées, messages lus par un seul des deux décodeurs.
- **Jamais votre indicatif**, jamais l'adresse IP, le nom de l'ordinateur ou vos dossiers personnels.
- Extraits audio de 15 secondes seulement si vous l'avez accepté, 6 par heure au plus. Effacés après 12 mois.
- Si l'envoi n'est pas encore actif ou sans internet, les cas attendent sur l'ordinateur et partent seuls plus tard : la ligne **Envoi** de l'état dit toujours où on en est.

## Licence gratuite pour les testeurs

Dans la vue d'ensemble se trouvent vos **heures d'écoute**, les barres vers la licence et votre **code testeur** (QT-XXXX-XXXX) : il est anonyme. Saisissez-le dans le formulaire de la page [Beta tester](https://iu1mvi.jimdofree.com/beta-tester/) avec votre indicatif.

- **10 heures** d'écoute : QTHome PRO gratuit pendant un an.
- **100 heures** sur au moins 3 mois différents : licence Fondateur, PRO gratuit pour toujours.

Seules comptent les heures avec la radio allumée et du signal.

## En cas de problème

Appuyez sur **Signaler** en haut à droite, décrivez ce qui s'est passé et envoyez. C'est anonyme ; sans internet, cela attend et part plus tard.

Réalisé par IU1MVI.
