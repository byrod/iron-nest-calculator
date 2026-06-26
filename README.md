# Iron Nest — Firing Calculator / Calculateur de tir

*Non-official fan-made tool. Iron Nest and its contents belong to their respective developers. Not affiliated.*
*Outil non officiel créé par un fan. Iron Nest et ses contenus appartiennent à leurs développeurs respectifs. Sans affiliation.*

---

## 🇫🇷 Français

### À quoi ça sert

Cette application calcule la **solution de tir** (élévation du canon et charge de poudre) à partir de la **distance** d'une cible dans Iron Nest. Tu peux aussi noter l'**azimut** et le **type d'obus**, enregistrer jusqu'à 8 cibles dans un carnet, et ajuster charge et obus directement sur chaque carte pour grouper tes tirs.

L'app est un **fichier HTML autonome** : ouvre-le dans n'importe quel navigateur, aucune installation, fonctionne hors-ligne.

### Utilisation rapide

1. **Distance** (obligatoire) : règle-la avec la réglette, les chevrons, les flèches du clavier, ou en tapant la valeur. Précision au centième de km.
2. **Azimut** (optionnel) : oriente l'aiguille de la boussole, ou tape la valeur. Clic au centre de la boussole pour effacer.
3. **Type d'obus** (optionnel) : choisis-le dans la liste. Il n'influe pas sur l'élévation, seulement sur l'effet.
4. Les **6 solutions de charge** s'affichent. Clique **Épingler** sur celle que tu retiens pour l'ajouter au carnet.

Sur une carte épinglée : **clic gauche / droit** sur *Obus* et *Charge* pour changer leur valeur (l'élévation se recalcule).

### Importer plusieurs cibles d'un coup (capture de texte)

Le jeu affiche les cibles au format `azimut° / distance km`. Plutôt que tout retaper, tu peux **extraire le texte d'une capture** avec l'outil Capture d'écran de Windows 11, puis le coller dans l'app.

**Étapes (Windows 11) :**

1. Dans le jeu, affiche la liste des cibles (touche **Tab** ouvre le bloc-note en grand, plus lisible).
2. Appuie sur **Windows + Maj + S** pour ouvrir la barre de capture.
3. Clique le bouton **Text Extractor** dans la barre d'outils (en haut au centre de l'écran).
4. Encadre en glissant la zone contenant les lignes `azimut° / distance km`. Le texte est reconnu aussitôt par OCR, sans avoir à enregistrer d'image.
5. Clique **Copier tout le texte** (*Copy all text*).
6. Reviens dans l'app, colle (**Ctrl + V**) dans la zone « Importer une liste de cibles », puis clique **Analyser**.
7. Vérifie les valeurs lues (les valeurs hors plage sont surlignées en rouge), corrige si besoin, puis **Ajoute au carnet**.

> **Raccourci direct** : selon ta version, **Windows + Maj + T** ouvre directement Text Extractor sans passer par la barre de capture.

> **Astuce qualité** : l'OCR lit beaucoup mieux un texte **net, droit et horizontal**. La vue « Tab » du bloc-note donne de meilleurs résultats qu'une photo d'écran prise de biais. Si une ligne est mal lue, agrandis l'affichage du jeu avant la capture.

> L'outil Capture traite l'OCR **localement**, sans envoyer tes images sur internet. Si le bouton « Text Extractor » est absent, mets à jour l'application Capture d'écran depuis le Microsoft Store.

### Sauvegarde

Les cibles ne sont gardées qu'en mémoire pendant la session. Utilise **Exporter (JSON)** pour sauvegarder une session et **Importer** pour la recharger. La langue choisie (FR/EN) est mémorisée automatiquement dans ton navigateur.

---

## 🇬🇧 English

### What it does

This app computes the **firing solution** (gun elevation and powder charge) from a target's **range** in Iron Nest. You can also record the **bearing** and **shell type**, save up to 8 targets in a log, and tweak charge and shell directly on each card to group your shots.

The app is a **standalone HTML file**: open it in any browser, no install, works offline.

### Quick start

1. **Range** (required): set it with the ruler, the chevrons, the keyboard arrows, or by typing. Precision to the hundredth of a km.
2. **Bearing** (optional): rotate the compass needle, or type the value. Click the compass center to clear it.
3. **Shell type** (optional): pick it from the list. It does not affect elevation, only the effect on target.
4. The **6 charge solutions** appear. Click **Pin** on the one you choose to add it to the log.

On a pinned card: **left / right click** on *Shell* and *Charge* to change their value (elevation recomputes).

### Import several targets at once (text capture)

The game shows targets as `bearing° / range km`. Instead of retyping everything, you can **extract the text from a screenshot** with the Windows 11 Snipping Tool, then paste it into the app.

**Steps (Windows 11):**

1. In the game, open the target list (the **Tab** key brings up the larger, more legible notepad view).
2. Press **Windows + Shift + S** to open the capture bar.
3. Click the **Text Extractor** button in the toolbar (top center of the screen).
4. Drag a box around the area containing the `bearing° / range km` lines. The text is recognised by OCR right away, with no need to save an image.
5. Click **Copy all text**.
6. Back in the app, paste (**Ctrl + V**) into the "Import a target list" box, then click **Analyse**.
7. Review the parsed values (out-of-range values are highlighted in red), fix if needed, then **Add to log**.

> **Direct shortcut**: depending on your version, **Windows + Shift + T** opens Text Extractor directly without going through the capture bar.

> **Quality tip**: OCR reads **clean, straight, horizontal** text far better. The "Tab" notepad view gives better results than a photo of the screen taken at an angle. If a line is misread, increase the game's display size before capturing.

> The Snipping Tool runs OCR **locally**, without uploading your images. If the "Text Extractor" button is missing, update the Snipping Tool from the Microsoft Store.

### Saving

Targets are kept in memory for the session only. Use **Export (JSON)** to save a session and **Import** to reload it. Your chosen language (FR/EN) is remembered automatically in your browser.

---

## Auteur / Author

Créé par **@byrod**.
Made by **@byrod**.

## Licence / License

Aucune licence open source pour l'instant — tous droits réservés. Le code est consultable et utilisable dans le navigateur, mais pas destiné à la redistribution ou à la réutilisation sans accord.

No open-source license for now — all rights reserved. The code is viewable and usable in the browser, but not intended for redistribution or reuse without permission.
