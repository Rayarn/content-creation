# Post 2 · mercredi 30 septembre 2026 · cas d'usage n°1

**Pilier :** Automatisation actuarielle + IA  
**Format :** carrousel 11 slides avec captures, question finale

## Texte

```text
𝘾𝙖𝙨 𝙙'𝙪𝙨𝙖𝙜𝙚 : 𝙡'𝙄𝘼 𝙚𝙩 𝙡'𝙖𝙪𝙩𝙤𝙢𝙖𝙩𝙞𝙨𝙖𝙩𝙞𝙤𝙣 𝙙𝙖𝙣𝙨 𝙡𝙚 𝙥𝙞𝙡𝙤𝙩𝙖𝙜𝙚 𝙙𝙪 𝙥𝙖𝙨𝙨𝙞𝙛.

Ici, le passif d'un fonds de pension. Mais si votre équipe calcule des provisions, explique leur évolution et rédige un rapport, vous allez vous reconnaître, quel que soit le secteur.

𝘾𝙤𝙣𝙩𝙚𝙭𝙩𝙚
Chaque année, l'équipe reçoit les données du portefeuille.
Elle les contrôle, calcule les provisions de chaque assuré, explique l'évolution depuis l'an dernier, teste les sensibilités, puis rédige le rapport.
Le tout entre des classeurs Excel et des notebooks Python sous Jupyter.
Ce travail prend généralement plusieurs semaines.

𝙊𝙗𝙟𝙚𝙘𝙩𝙞𝙛𝙨 𝙙𝙪 𝙥𝙧𝙤𝙘𝙚𝙨𝙨𝙪𝙨
-> Passer de plusieurs semaines de production à un recalcul suivi d'une relecture
-> Rendre chaque chiffre traçable et rejouable à l'identique
-> Consacrer le temps gagné à l'analyse

𝘼𝙫𝙖𝙣𝙩𝙖𝙜𝙚𝙨 𝙥𝙤𝙪𝙧 𝙡𝙚𝙨 é𝙦𝙪𝙞𝙥𝙚𝙨
-> Provisions, analyse de mouvement et sensibilités sortent du même calcul : plus de copier-coller entre fichiers
-> Un premier jet du rapport, dont chaque chiffre vient directement du calcul
-> Plus de temps pour interpréter, challenger et expliquer

𝘼𝙫𝙖𝙣𝙩𝙖𝙜𝙚𝙨 𝙥𝙤𝙪𝙧 𝙡𝙚𝙨 𝙢𝙖𝙣𝙖𝙜𝙚𝙧𝙨
-> Le passif lu en un seul écran : provisions, évolution, contrôles
-> Des résultats rejouables et documentés, simples à défendre en audit
-> Une validation humaine tracée : brouillon, relu, validé

𝙋𝙧é𝙨𝙚𝙣𝙩𝙖𝙩𝙞𝙤𝙣 𝙙𝙚 𝙡𝙖 𝙨𝙤𝙡𝙪𝙩𝙞𝙤𝙣
Une application qui enchaîne tout le processus à partir des données de l'année.
Un moteur actuariel calcule les provisions par assuré, l'analyse de mouvement (dont les étapes se somment exactement à la variation) et les sensibilités.
Des garde-fous signalent tout résultat qui sort de sa fourchette habituelle.
L'IA intervient là où elle aide vraiment : rédiger le premier jet du rapport et répondre aux questions sur les résultats. Elle n'écrit aucun chiffre et ne valide rien.

Elle part de l'existant : mêmes données, mêmes étapes, mêmes méthodes. Et elle répond à ce qu'on attend aujourd'hui de l'IA en actuariat : gagner du temps sans perdre la maîtrise des chiffres.

𝘾𝙚 𝙦𝙪𝙞 𝙣𝙚 𝙘𝙝𝙖𝙣𝙜𝙚 𝙥𝙖𝙨
Les hypothèses, l'interprétation et la décision restent à l'actuaire. L'IA lui fait gagner du temps. Elle ne le remplace pas.

𝙋𝙧𝙤𝙡𝙤𝙣𝙜𝙚𝙢𝙚𝙣𝙩
Le rapprochement comptable, souvent fait à part dans des fichiers Excel. C'est l'étape suivante.

Ce cas, c'est PensionPro, une application que j'ai développée. Les écrans sont dans le carrousel.

Chez vous, qu'est-ce qui prend le plus de temps : le calcul (A), ou tout ce qui vient après (B) ?
```

## À joindre

- Visuel : [carrousel-pensionpro.pdf](carrousel-pensionpro.pdf)
