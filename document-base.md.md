---
bibliography: bibliographie.bib
link-citations: true
csl: iso690-author-date-fr-no-abstract-lm.csl
nocite: |
  @*
---
<!--
    Version du 2018-03-30 - Louis Martin
-->

<!-- Page de titre -->
\begin{titlepage}
    \begin{center}
    { \setstretch{1.2} \large
        \MakeUppercase{
            { \Large Université du Québec à Montréal }
            \vfill
            Titre long du rapport\break
            s'étendant sur plus d'une ligne
            \vfill
            Rapport d'activité de synthèse présenté\break
            comme exigence partielle\break
            de la maitrise informatique de gestion
            \vfill
            par \break Mac-Frantz Noailles
            \vfill
            août 2018
        }
    }
    \end{center}
\end{titlepage}


<!-- Pagination en chiffre romain au départ -->
\pagenumbering{roman}
\setcounter{page}{2}


<!-- Optionnellement, inclure ci-après les remerciements -->

# Remerciements {-}

Cette section est optionnelle.

<!-- Optionnellement, inclure ci-après la dédicace -->
<!-- La dédicace est justifiée à droite -->

# Dédicace {-}

\begin{flushright} {\itshape

Cette section est optionnelle.\break
Deuxième ligne de la dédicace.\break

} \end{flushright}

<!-- Optionnellement, inclure ci-après l'avant-propos -->

# Avant-propos {-}

Cette section est optionnelle.

<!-- Commandes pour la génération de la table des matières et des pages associées -->

\tableofcontents

\listoffigures

\listoftables

\lstlistoflistings

<!-- Optionnellement, inclure ci-après les abréviations, sigles et acronymes -->

# Liste des abréviations, sigles et acronymes {-}

MGL
  ~ Maitrise en génie logiciel

UQAM
  ~ Université du Québec à Montréal

<!-- Inclure ci-après le résumé -->
<!-- L'espacement entre les lignes est augmenté à partir d'ici-->

\onehalfspacing

# Summary

Petit texte.

# Résumé {-}

Exemple avec une petite note de bas de page.[^petite_note]

[^petite_note]: Ceci est le texte de la petite note.

<!-- Forcer une fin de page, la pagination est remise en chiffre romain et le compteur de page à un, l'espacement entre les lignes est augmenté  -->

\singlespacing
\newpage
\setcounter{page}{1}
\pagenumbering{arabic}
\onehalfspacing

<!-- Inclure ci-après le corps du mémoire dans l'ordre désiré -->

# Introduction {-}


Le développement de logiciel de qualité est équivalent à la quête du Saint Graal, car on se demande si ce n’est pas un mythe. Or, de nos jours les logiciels prolifèrent dans nos vies quotidiennes. Ils permettent de nous rendre plus efficaces, de communiquer avec nos collègues, nos familles et amis. Ils facilitent notre quotidien. Pensons aux multiples logiciels dans nos appareils portatifs tels nos téléphones intelligents. Pensez à Waze1[^petite_note], P$2[^petite_note] associé à Stationnement de Montréal, mais aussi aux Microsoft[^petite_note] et Facebook[^petite_note].
Avant d’être les titans d’aujourd’hui Microsoft, Facebook ont vu le jour dans des garages, des dortoirs d’université. Ils étaient tous de très petites organisations à leurs débuts. Il est donc important de soutenir ces types d’organisations. D’un autre côté, comme utilisateur, le public s’attend à ce que les applications offertes par des très petites organisations (après TPO) remplissent ses attentes ou à tout le moins soient à la hauteur des prétentions de leurs développeurs. Par conséquent, les logiciels développés par des TPO se doivent être de qualité. Nous ne pouvons pas prédire les bonnes idées de logiciels et encore moins le succès d’une organisation, mais, il y a-t-il un moyen d’augmenter les chances de succès des très petites organisations. Peut-on faciliter l’atteinte de la qualité ?
Une manière de s’assurer d’avoir un produit de qualité est d’avoir un processus de développement de qualité. Les grandes organisations ont le choix des moyens pour optimiser leurs processus. Elles disposent autant des outils, des ressources financières que du personnel nécessaire pour optimiser leur processus de développement. Les choix des très petites organisations doivent être judicieux, car leurs ressources et le personnel dont ils disposent sont moindres. Ils peuvent difficilement mettre en place les structures ou des processus comparables aux grandes organisations. Par ailleurs, ces structures et ces processus ne leur conviendraient pas. De surcroit, devant la multitude de propositions des outils, méthodes, normes, modèles, méthodologies comment faire un choix éclairé ?
Dans le cadre de cette étude, je mets de l’avant un cadre conceptuel pour permettre à une très petite organisation d’avoir une vision globale de ses efforts d’amélioration de son processus de développement. Je fais et je teste une proposition théorique visant à guider les très petites organisations dans le choix et l’intégration des moyens à mettre en place pour améliorer ce processus.
L’Agilité et la norme ISO/IEC 29110 (après la 29110) sont des moyens à la portée des TPO pour améliorer leur processus de développement. Cependant, les perceptions porteraient à croire qu’ils sont incompatibles. On entend souvent que l’on ne documente pas lorsque l’on fait du développement Agile et la 29110 décrit la documentation minimale afin de fournir une assurance de la qualité d’un logiciel. Toutefois, les principes et les valeurs Agile n’excluent pas la documentation. Plusieurs études démontrent qu’individuellement elles optimisent le processus des organisations. Il serait donc intéressant d’étudier leurs effets combinés. Quel type de relation ont-elles ?
~~~
Une très petite organisation conforme à la norme aurait-elle avantage à chercher à respecter les principes et valeurs Agile ?
Une très petite organisation respectant les principes et valeurs Agile aurait-elle avantage à chercher à se conformer aux exigences de la 29110 ?
~~~
[^petite_note]:www.waze.com
[^petite_note]:www.statdemtl.qc.ca/fr/infos-pratiques/pservicemobile.html
[^petite_note]:www.microsoft.com
[^petite_note]:www.facebook.com