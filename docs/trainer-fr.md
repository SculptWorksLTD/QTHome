# QTHome Trainer — guide pour les bêta-testeurs

QTHome Trainer écoute votre radio avec vous pendant que vous utilisez WSJT-X comme d'habitude, et compare le décodeur FT8/FT4 de QTHome à celui de WSJT-X. Cela nous montre où notre décodeur se trompe, pour le corriger.

**Il n'émet jamais et ne commande jamais la radio.** Il lit seulement l'audio.

## Ce qu'il faut

- Un Mac (Apple ou Intel) ou un PC Windows 10/11.
- La radio reliée à l'ordinateur par sa carte son USB (celle que vous utilisez pour WSJT-X).
- **WSJT-X installé** (gratuit : <https://wsjt.sourceforge.io/wsjtx.html>). Le Trainer utilise son décodeur comme référence. Il n'a pas besoin d'être ouvert.

## Installer

1. Ouvrez la page des versions : <https://github.com/SculptWorksLTD/QTHome/releases/latest>
2. Téléchargez **QTHome-Trainer-Mac.pkg** (Mac) ou **QTHome-Trainer-Windows.zip** (Windows).
3. Mac : double-cliquez sur le .pkg. Si le Mac refuse : clic droit sur le fichier → **Ouvrir**.
   Windows : ouvrez le zip et lancez **QTHome Trainer.exe**. Si Windows avertit : **Informations complémentaires → Exécuter quand même**.

## La première fois

1. Saisissez votre **locator** (4 ou 6 caractères, ex. JN45ab) : seule la zone est utilisée.
2. Cochez avec quoi vous recevez et votre antenne.
3. Décidez si vous envoyez des **extraits audio** (lisez l'encadré) : ils aident beaucoup, mais vous pouvez refuser.
4. **Enregistrer et commencer**.

## À chaque fois

1. Choisissez l'**entrée audio de la radio** (ex. « USB Audio CODEC »).
2. Appuyez sur **Commencer l'écoute**. Sur Mac, la première fois, le système demande l'accès au micro : répondez **Autoriser**.
3. Réglez la radio sur une fréquence FT8 (ex. 14,074 MHz USB) et laissez tourner.

À la fin de chaque créneau de 15 secondes un tableau s'affiche : pour chaque message, ✓ si QTHome l'a décodé et ✓ si WSJT-X l'a décodé.

Si la fenêtre ne peut pas utiliser l'audio, un bouton **Ouvrir dans le navigateur** apparaît : le Trainer s'ouvre dans votre navigateur, où le micro fonctionne toujours.

## CW depuis la radio

Dans **Réglages** cochez **CW** et appuyez sur **Commencer l'écoute** sur la carte son de la radio. Écoutez le CW comme d'habitude : toutes les 30 secondes deux décodeurs de QTHome relisent ce que vous avez entendu et les indicatifs sont vérifiés avec le Reverse Beacon Network (RBN). Si The Rigger est ouvert, le Trainer connaît aussi votre bande. Seuls les cas utiles sont envoyés : un indicatif que le RBN n'a jamais entendu, ou les deux décodeurs en désaccord.

## Skimmer avec la clé SDR (Mac seulement, pour l'instant)

Il faut une clé RTL-SDR V3 ou V4 avec une antenne HF (la radio reste libre). Cochez **Skimmer avec la clé SDR**, choisissez les bandes et appuyez sur **Allumer le skimmer** : la clé chasse toute seule. Elle va sur la bande où le RBN et le spectre montrent le plus de stations, les lit toutes ensemble et change dès que plus aucun nouvel indicatif n'arrive. Plus vous choisissez de bandes, plus elle fait d'essais. Les indicatifs sont comparés au RBN ; dans le tableau ✓ veut dire confirmé, ? jamais entendu par le RBN.

## Ce qui est envoyé à QTHome

- Seulement les cas utiles : signaux faibles, bandes encombrées, messages décodés par un seul des deux décodeurs.
- **Jamais votre indicatif**, ni l'adresse IP, le nom de l'ordinateur ou vos dossiers personnels.
- Des extraits audio de 15 secondes seulement si vous l'avez accepté, 6 par heure au maximum. Ils sont effacés après 12 mois.

## Si quelque chose ne va pas

Appuyez sur **Signaler** en haut à droite, décrivez ce qui s'est passé et envoyez. C'est anonyme ; sans internet l'envoi attend dans une file.

Réalisé par IU1MVI.
