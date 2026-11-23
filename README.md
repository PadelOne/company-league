# Padel One League · Entreprises

Application de gestion des journées padel d'entreprise organisées par **Padel One** : joueurs, tirage au sort, scores, classement en direct, écran TV et branding au logo du client.

Une seule page (`index.html`), sans installation ni serveur. Fonctionne dans Chrome, Edge ou Safari, sur ordinateur ou tablette.

---

## Utilisation

Au premier lancement sur un appareil, l'événement **Azqore (23.11.2026, 18h30–20h30)** est déjà chargé avec ses 18 joueurs.

1. **Événements** → *+ Nouvel événement* (ou *Dupliquer* un événement précédent).
2. **Réglages & branding** :
   - nom de l'entreprise, date, lieu ;
   - **logo de l'entreprise** (PNG, JPG ou SVG) et couleur d'accent — le logo Padel One reste toujours affiché ;
   - terrains, nombre de rotations, **début et fin de la ligue**, **durée d'une rotation** et temps de changement de terrain. L'app indique si le programme tient dans le créneau et propose de l'ajuster.
3. **Joueurs** → collez la liste reçue de l'entreprise, une ligne par joueur : `Prénom niveau` (ex. `Marc 6`, `Julie 3 F`). `F` = joueuse.
4. **Tirage** → 🎲. Les contrôles affichent : nombre de matchs par joueur, partenaires jamais répétés, mixité, équilibre des matchs.
5. **Scores** → tapez les scores, *Entrée* passe au champ suivant. Chrono intégré.
6. **Écran live ↗** → à ouvrir sur la TV du club (fenêtre séparée, plein écran). Il se met à jour dès qu'un score est saisi sur le même ordinateur.
7. **Classement** → podium, impression / PDF, copie pour WhatsApp.

### Critères de tirage
| Mode | Principe |
|---|---|
| **Fort + moins fort** | Chaque équipe = 1 joueur de la moitié forte + 1 de la moitié moins forte ; matchs équilibrés par somme des niveaux |
| **Par niveau** | Les joueurs de niveau proche jouent ensemble |
| **Aléatoire** | Partenaires au hasard |

Dans tous les modes : jamais deux fois le même partenaire (si mathématiquement possible), adversaires variés, repos répartis sur tous les joueurs, jamais deux tours de suite au repos. Option « pas deux femmes ensemble ».

### Désistement en cours de journée
*Joueurs* → décocher le joueur → *Tirage* → **Recalculer les tours restants**. Les tours déjà joués sont conservés.

### Nombre de matchs inégal
Si le nombre de joueurs ne permet pas à tout le monde de jouer autant, le classement est calculé **en moyenne par match** et l'app indique le nombre de tours qui rétablit l'égalité.

---

## ⚠️ Données
- Les données sont enregistrées **dans le navigateur de l'appareil utilisé**, pas sur GitHub. Rien n'est envoyé sur internet.
- Un autre ordinateur ne voit pas vos événements : utilisez **Exporter** (fichier JSON) puis **Importer** sur l'autre appareil.
- Exportez une sauvegarde après chaque événement.
- Ne publiez jamais les fichiers JSON d'export dans ce dépôt : ils contiennent les noms des participants.

---

## Mise en ligne (GitHub Pages)
1. Créer le dépôt `padel-one-league` sur le compte **PadelOne**.
2. Déposer `index.html`, `README.md` et `.nojekyll`.
3. *Settings* → *Pages* → *Deploy from a branch* → `main` / `root` → *Save*.
4. L'app est disponible après une minute environ à l'adresse `https://padelone.github.io/padel-one-league/`.

© Padel One
