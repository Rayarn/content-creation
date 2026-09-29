# Post 4 · lundi 5 octobre 2026 · cas d'usage n°2

**Pilier :** Python / R / VBA  
**Format :** texte + visuel avant/après, question en un mot

> ⚠️ Ce texte contient une anecdote marquée [ANECDOTE À CONFIRMER]. Ne la publiez que si elle est vraie ; sinon, retirez-la ou remplacez-la par un vrai souvenir.

## Texte

```text
𝙋𝙡𝙪𝙨 𝙙'𝙪𝙣𝙚 𝙨𝙚𝙢𝙖𝙞𝙣𝙚 𝙙𝙚 𝙩𝙧𝙖𝙫𝙖𝙞𝙡 𝙧𝙖𝙢𝙚𝙣é𝙚 à 𝟱 𝙢𝙞𝙣𝙪𝙩𝙚𝙨.
𝘿𝙖𝙣𝙨 𝙀𝙭𝙘𝙚𝙡, 𝙖𝙫𝙚𝙘 𝙑𝘽𝘼.

Cas d'usage : l'automatisation des scénarios d'actif d'une projection ALM. Si votre équipe prépare des fichiers à partir de plusieurs sources dans Excel, le schéma va vous parler.

Pendant mon alternance à l'ERAFP, j'ai appris à produire ces scénarios aux côtés de l'équipe. Une tâche essentielle, qui demandait beaucoup de manipulations. Alors j'ai cherché à automatiser la partie mécanique, sans jamais sortir d'Excel.

𝘾𝙤𝙣𝙩𝙚𝙭𝙩𝙚
À chaque exercice de projection ALM, l'équipe produit les scénarios déterministes de l'actif.
Elle rassemble des données de plusieurs sources, intègre les chocs actions dans chaque scénario, puis produit les fichiers d'entrée de l'outil de projection.
Tout se passe dans Excel : mettre à jour des liens, adapter des formules, dupliquer des fichiers, vérifier que rien n'a cassé.
Plus d'une semaine de travail à chaque fois.

𝙊𝙗𝙟𝙚𝙘𝙩𝙞𝙛𝙨 𝙙𝙪 𝙥𝙧𝙤𝙘𝙚𝙨𝙨𝙪𝙨
-> Réduire la production des scénarios de plus d'une semaine à 5 minutes
-> Supprimer les mises à jour manuelles de liens et de formules
-> Produire les fichiers d'entrée de la même façon d'un exercice à l'autre

𝘼𝙫𝙖𝙣𝙩𝙖𝙜𝙚𝙨 𝙥𝙤𝙪𝙧 𝙡𝙚𝙨 é𝙦𝙪𝙞𝙥𝙚𝙨
-> Une semaine de manipulations rendue à l'analyse
-> Moins d'occasions de casser un lien ou d'oublier une formule
-> On reste dans Excel : rien de nouveau à apprendre

𝘼𝙫𝙖𝙣𝙩𝙖𝙜𝙚𝙨 𝙥𝙤𝙪𝙧 𝙡𝙚𝙨 𝙢𝙖𝙣𝙖𝙜𝙚𝙧𝙨
-> Des scénarios relancés en quelques minutes si une hypothèse change
-> Des fichiers produits à l'identique, donc des résultats comparables d'un exercice à l'autre
-> Rien à installer, aucune infrastructure à faire valider

𝙋𝙧é𝙨𝙚𝙣𝙩𝙖𝙩𝙞𝙤𝙣 𝙙𝙚 𝙡𝙖 𝙨𝙤𝙡𝙪𝙩𝙞𝙤𝙣
Un outil VBA, directement dans Excel, avec une interface pensée comme une page web.
[ANECDOTE À CONFIRMER, à retirer avant publication si inventée : La première fois que je l'ai montré, on m'a demandé sur quel site il tournait. Réponse : dans Excel.]
Trois étapes : préparer les données de la période cible, appliquer les scénarios et les chocs, produire les fichiers d'entrée.
Pourquoi VBA ? Parce qu'il est déjà sur tous les postes. Pour une équipe qui travaille dans Excel, c'est souvent le chemin le plus court pour automatiser, sans lancer de projet informatique.
Et non, un outil VBA n'a aucune raison d'être moche.

𝘾𝙚 𝙦𝙪𝙞 𝙣𝙚 𝙘𝙝𝙖𝙣𝙜𝙚 𝙥𝙖𝙨
Le choix des hypothèses et des chocs, et la lecture des résultats, restent le travail de l'actuaire. L'outil retire la mécanique, pas le jugement.

𝙋𝙧𝙤𝙡𝙤𝙣𝙜𝙚𝙢𝙚𝙣𝙩
Des contrôles automatiques de cohérence sur les fichiers produits, avant leur chargement dans l'outil de projection.

Et dans votre équipe, pour automatiser : VBA, Python, ou les deux ?
```

## À joindre

- Visuel : [visuel-avant-apres.png](visuel-avant-apres.png)
