# Mission Rétro-automatique · V2 (en construction)

Branche de travail pour les missions 5 et 6 (Partie 4 : systèmes particuliers, Partie 5 : correcteurs).
La version en ligne du jeu (`retro-automatique/` sur la branche `main`) n'est pas modifiée.

## Contenu
- `index.html` : le jeu complet avec les missions 5 et 6. Il réutilise les images, sons et documents du dossier `retro-automatique/` (balise `<base>`) et enregistre sa progression à part (`retro-auto-v2-dev`), sans toucher à celle des élèves.
- `capsules/capsule3-premier-ordre-generalise.html` : capsule interactive sur le premier ordre généralisé.

## Mission 5 : Démasquer la carte de régulation
- Déblocage après la mission 4 avec un code donné en cours (provisoire : `PARTICULIER`).
- Bureau de l'ingénieur en chef : note manuscrite, puis message d'ICAM_BOT et apparition du bouton du tiroir.
- Tiroir : 6 cartes A à F à brancher sur l'ordinateur (type de système, puis un paramètre à lire).
- Ordinateur : vidéo ressource (lien à renseigner dans `LINKS.vidM5`), simulateur, test de la carte en service C(p) = (1 + 100.p)/p.
- Fin : code de la mission 6 donné en cours (provisoire : `CORRECTEUR`).

## Mission 6 : Reprogrammer la carte de régulation
- Déblocage à la fin de la mission 5 avec le code donné en cours (provisoire : `CORRECTEUR`).
- Salle de maintenance : cahier de laboratoire de l'ingénieur (5 essais à expliquer : P et écart statique, saturation, classe 1, phase de l'intégrateur, avance de phase), puis message d'ICAM_BOT.
- Ordinateur de maintenance : vidéo ressource (lien à renseigner dans `LINKS.vidM6`), simulateur de correcteurs (P, PI, PD, PID, avance, retard), banc de synthèse du PI (4 questions : défaut de la carte d'origine, τi = 8732 s par compensation de pôle, Mφ = 90°, Kp ≥ 728), puis réglage libre avec les voyants du cahier des charges (Mφ ≥ 45°, MG ≥ 12 dB, tr5% ≤ 3600 s, ε ≤ 2 %).
- Armoire de régulation : essai en service (réponse indicielle comparée à la carte d'origine), puis écran « Niveau 2 terminé » et sondage.

## Parcours e-learning : chapitre 6 « Choisir et régler un correcteur »
- Même code de déverrouillage que la mission 6 ; 9 questions (cahier de laboratoire puis banc de synthèse), avec la vidéo, le simulateur et le banc en ressources.

## Parcours e-learning : chapitre 5 « Identifier les systèmes particuliers »
- Même code de déverrouillage que la mission 5 ; 18 questions : 6 systèmes (type + paramètre) puis l'analyse du correcteur de la régulation.

## Progression commune aux deux formats
- Chacun peut passer de l'escape game au parcours e-learning (menu ☰ ou bandeau du parcours).
- Une mission validée dans le jeu valide le chapitre correspondant (réponses justes en place, mention « validé dans l'escape game »), et un chapitre validé fait avancer le jeu. Les codes saisis dans un format comptent dans l'autre. La synchronisation se fait à chaque ouverture et à chaque changement de format.

## Score commun et indices
- Même score dans les deux formats : départ 100 pts, +10 par bonne réponse, −10 par erreur, −5 par indice. Dans le parcours, une bonne réponse rapporte des points une seule fois, à la première validation juste.
- ICAM_BOT donne aussi des indices dans le parcours : l'élève choisit la question (par défaut, la première non résolue).

## À faire
- Codes définitifs des missions 5 et 6, liens des vidéos ressources (missions 5 et 6).
- Harmoniser la constante de temps : 8372 s (R.m.c, mission 1) contre 8732 s (modèle des missions 2 à 6).
- Identifiants des nouvelles questions à ajouter au tableau de bord Moodle.
