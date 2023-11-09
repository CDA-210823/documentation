# documentation

**Lien Trello**
==> https://trello.com/b/hQZaK34a/site-e-commerce

**Lien dictionnaire de données**
==> https://docs.google.com/spreadsheets/d/1bECHQCp8kdQq1rBVJR2LGDJ28AHE7O3ZYnz7_iIfhno/edit?usp=sharing

**Charte Git**

**COMMIT GIT**
- Les messages de commit doivent respecter une syntaxe bien précise :
[NOM_FEATURE][TYPE_COMMIT][INITIAL] - description du commit
- Nom de la feature
Optionnel. Représente la feature sur laquelle on travaille. Peut être le nom ou le code de celle-ci.Exemple: [connection] ou [EL-125]
- Type de Commit
Spéficie le type du commit. C'est à dire s'il s'agit d'une fonctionnalité, d'une correction, d'une addtion à la documentation, etc...

**Listes des codes:**
- Fonctionnalité: [FEAT]
- Correction de bug: [FIX]
- Refactorisation de code: [REFACTO]
- Modification d'un README: [DOC]
- Initialisation (de branche par exemple): [INIT]
- Description du commit
Description détaillée du commit, de ce qui a été fait dedans.

**Exemple**
git commit -m "[connection][FEAT][PM] - Création de page de connection, bouton connection redirigeant vers AUTH0, reception du token de conn