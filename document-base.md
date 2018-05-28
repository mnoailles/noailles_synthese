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
            \vfill
            Rapport d'activité de synthèse présenté\break
            comme exigence partielle\break
            de la maitrise en informatique de gestion
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

SWEBOK
~ Guide

TPO
  ~ Très petite organisation

UQAM
  ~ Université du Québec à Montréal

<!-- Inclure ci-après le résumé -->
<!-- L'espacement entre les lignes est augmenté à partir d'ici-->

\onehalfspacing

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

%inclure:textes/introduction.md
\newpage

%inclure:textes/problematique.md
\newpage

%inclure:textes/conclusion.md
\newpage
<!-- Le début des annexes est indiqué -->

\appendix

<!-- Inclure ci-après les annexes -->

%inclure:textes/appendix.md

<!-- Inclure ci-après la bibliographie -->

# Bibliographie {-}

<!--
    Note : les principales commandes d'espacement sont :
    \singlespacing
    \onehalfspacing
    \doublespacing
-->
