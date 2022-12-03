# rekordbox-playlist-toolbox

### Stade

Mise en place de l'idée.

### Doc intéressante

https://rekordbox.com/en/support/developer/

### Next Steps

- Faire un trello / Jira ?
  - Deplacer les next steps dedans
- Gestion des PRs
- Guidelines Git
- Documentation
- Ajouter des liens dans le README
- Définir un MVP
  - UX
    - On propose quoi ?
    - A qui ?
    - Dans quel but ?
  - Mac ? Windows ? Linux ?
  - Technos ?

### 😎 Challenges

Le faire en fucking web assembly / emscript et compagnie pour que ce soit full navigateur.
On selectionne un dossier, ça lit les metadatas, on génère un xml en output.
Pas besoin d'avoir Rekordbox.
Les sons ne seront bien pas pas analysés. (en tout cas dans le MVP, mais je pense que ce n'est pas le but de l'outil, on ne pourra pas "rivaliser" avec Rekordbox là dessus)

### Install

- Cloner le projet
- Suivre le Hello World Emscripten
- Installer `serve`
- Lancer
```
  serve
```

### Remarques
Quand je lance `emsdk_env.bat` puis `emcmdprompt.bat`
sur Powershell / le nouveau Terminal Windows, j'ai plus accès à certaines commandes genre `ls`, et faire un `npm install --global serve` n'a pas installé serve en global une fois sortie de mon onglet Terminal (kill prompt). Autant donc ouvrir 3 onglets :
- Un pour `emsdk_env.bat` et `emcmdprompt.bat`, puis pouvoir ensuite lancer `emcc` quand nécessaire
- Un pour `serve` et monitorer
- Un pour git & co

### Liens

Hello World Emscripten : https://code-boxx.com/get-started-webassembly-beginners/

Préfix des commits :
- `semantic` https://gist.github.com/joshbuchea/6f47e86d2510bce28f8e7f42ae84c716
- `emoji` (opt.) : https://gitmoji.dev/

Forme :
`semantic`: `emoji` message

Exemple :
```
chore: :tada: Première guideline ? 
```
Donne :

chore: :tada: Première guideline ? 
