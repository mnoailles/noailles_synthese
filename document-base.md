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

MGL
  ~ Maitrise en génie logiciel

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

%inclure:textes/sommaire_anglais.md

%inclure:textes/introduction.md

%inclure:textes/contexte.md

%inclure:textes/problematique.md

%inclure:textes/objectifs.md

%inclure:textes/moyens.md

%inclure:textes/livrables.md

%inclure:textes/echeancier.md

%inclure:textes/resultats.md

%inclure:textes/reflexion.md

%inclure:textes/evaluation.md

%inclure:textes/conclusion.md

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

Al-Elaimat, A. et Al-Ghuwairi, A.-R. (2015). Procedural Assessment Process of Software Quality Models Using Agility. Proceedings of the International Conference on Intelligent Information Processing, Security and Advanced Communication, 61:1--61:5. doi:10.1145/2816839.2816884
April, A. et Laporte, C. Y. (2011). L’assurance qualité logicielle 1. Paris : Paris : Hermès science.
Beck, K., Beedle, M., Bennekum, A. van, Cockburn, A., Cunningham, W., Fowler, M., … Thomas, D. (2001a). Manifeste pour le développement Agile de logiciels. Agile manifesto. Repéré à http://agilemanifesto.org/iso/fr/manifesto.html
Beck, K., Beedle, M., Bennekum, A. van, Cockburn, A., Cunningham, W., Fowler, M., … Thomas, D. (2001b). Principes sous-jacents au manifeste. Agile manifesto. Repéré à http://agilemanifesto.org/iso/fr/principles.html
Boisvert, M. et Trudel, S. (2011). Choisir l’agilité : Du développement logiciel à la gouvernance (Etude, développement et intégration) (French édition) (Kindle Edi). Dunod.
Bourque, P. et Fairley, R. E. (2014). Guide to the Software Engineering - Body of Knowledge. IEEE Computer Society. doi:10.1234/12345678
Brooks, F. P. J. (1986). No silver bullet-essence and accidents of software engineering. Proceedings of the IFIP Tenth World Computing Conference,

1069‑1076. doi:10.1109/MC.1987.1663532
Buchalcevova, A. (2009). Software Development using ISO/IEC 29110 TR - Engineering and Management guide. Repéré à http://profs.etsmtl.ca/claporte/vse/Education/Software_Development_using_ISO 29110_rev0.ppt
Connor, R. V. O. et Laporte, C. Y. (2010). Towards the Provision of Assistance for Very Small Entities in Deploying Software Lifecycle Standards. ACM International Conference Proceeding Series, 4‑7. doi:10.1145/1961258.1961259
Dingsøyr, T., Nerur, S., Balijepally, V. et Moe, N. B. (2012). A decade of agile methodologies: Towards explaining agile software development. Journal of Systems and Software, 85(6), 1213‑1221. doi:10.1016/j.jss.2012.02.033
Dybå, T. et Dingsøyr, T. (2008). Empirical studies of agile software development: A systematic review. Information and Software Technology, 50(9‑10), 833‑859. doi:10.1016/j.infsof.2008.01.006
Fortin, M. F., Gagnon, J., Fournier, H. et Lauzier, M. (2016). Fondements et Étapes du processus de recherche : méthodes quantitatives et qualitatives. Montréal : Chenelière éducation.
Galván-cruz, S., Mora, M. et Connor, R. O. (2018). A Means-Ends Design of SCRUM + : an agile-disciplined balanced SCRUM enhanced with the ISO / IEC 29110 Standard. Advances in Intelligent Systems and Computing, (688), 13‑23.
Galvan-Cruz, S., Mora, M., O’Connor, R. V., Acosta, F. et Álvarez, F. (2017a). An Objective Compliance Analysis of Project Management Process in Main Agile Methodologies with the ISO/IEC 29110 Entry Profile. International Journal of

Information Technologies and Systems Approach, 10(1), 75‑106. doi:10.4018/IJITSA.2017010105
Galvan-Cruz, S., Mora, M., O’Connor, R. V., Acosta, F. et Álvarez, F. (2017b). An Objective Compliance Analysis of Project Management Process in Main Agile Methodologies with the ISO/IEC 29110 Entry Profile. International Journal of Information Technologies and Systems Approach, 10(1), 75‑106. doi:10.4018/IJITSA.2017010105
Galvan, S., Mora, M., O’Connor, R. V., Acosta, F. et Alvarez, F. (2015). A Compliance Analysis of Agile Methodologies with the ISO/IEC 29110 Project Management Process. Procedia Computer Science, 64, 188‑195. doi:10.1016/j.procs.2015.08.480
Glazer, H., Dalton, J., Anderson, D., Konrad, M. et Shrum, S. (2008). CMMI ® or Agile : Why Not Embrace Both ! (CMU/SEI-2008-TN-003). Software Engineering Institut, (November), 48. doi:10.1109/AGILE.2006.30
Gouvernement du Canada. (2016a). Terminuim Plus. Repéré 21 novembre 2016, à http://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=DEVELOPPEMENT+LOGICIEL&index=alt&codom2nd_wet=1#resultrecs
Gouvernement du Canada. (2016b). Terminuim Plus. Repéré 23 novembre 2016, à http://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-eng.html?lang=eng&i=1&index=alt&codom2nd_wet=1
Groupe de travail 24 de ISO/IEC JTC1/SC7. (s.d.). Normes ISO/IEC 29110 pour l’ingénierie de systèmes et l’ingénierie de logiciels pour les très petits organismes. Repéré 28 mars 2018, à http://profs.etsmtl.ca/claporte/VSE/Groupe24-menu.html

Hevner, A. R., March, S. T., Park, J. et Ram, S. (2004). Design Science in Information Systems Research 1. Design Science in IS Research MIS Quarterly, 28(1), 75‑105. doi:10.2307/25148625
Highsmith, J. (2001). History: The Agile Manifesto. The Agile Alliance. Repéré 28 mars 2018, à http://agilemanifesto.org/history.html
International Organization for Standardization (ISO), I. E. C. (IEC). (2008). ISO/IEC 12207:2008 Systems and software engineering -- Software life cycle processes. Genève : ISO/IEC 12207.
International Organization for Standardization (ISO), I. E. C. (IEC). (2014). Ingénierie des systèmes et du logiciel — Profils de cycle de vie pour les très petits organismes (TPO) — Partie 5-6-2: Ingénierie des systèmes — Guide de gestion et d’ingénierie: Groupe de profils génériques: Profil basique. ISO/IEC 29110-5-6-2.
International Organization for Standardization (ISO), I. E. C. (IEC). (2016a). TECHNICAL REPORT ISO / IEC TR Systems and software engineering — Lifecycle profiles for Very Small and engineering guide : Generic profile group : Basic profile. Repéré à http://standards.iso.org/ittf/PubliclyAvailableStandards/c062711_ISO_IEC_TR_29110-1_2016.zip
International Organization for Standardization (ISO), I. E. C. (IEC). (2016b). TR 29110-1: Software engineering — Lifecycle profiles for Very Small Entities ( VSEs ) —Part 1: Overview. Geneva : ISO/IEC 29110-1.
Laporte, C. Y. (2008). History Leading to an ISO/IEC JTC1/SC7 Working Group for VSEs developing Systems and/or Software. École de technologie supérieure - Génie logiciel et des technologie de l’information. Repéré 6 décembre 2016, à

http://profs.etsmtl.ca/claporte/English/VSE/index.html
Laporte, C. Y. et April, A. (2011). L’assurance qualité logicielle 2. Paris : Paris : Hermès science.
Laporte, C. Y. et O’Connor, R. V. (2014). A Systems Process Lifecycle Standard for Very Small Entities: Development and Pilot Trials. Communications in Computer and Information Science, 425, 13‑24. doi:10.1007/978-3-662-43896-1_2
Laporte, C. Y., Ptack, K. et Fanmuy, G. (2012). The Development of Systems Engineering International Standards and Support Tools for Very Small Enterprises. 22nd Annual International Symposium of the International Council on Systems Engineering.
Lebel, K. et Laporte, C. Y. (2016). Développement, en mode Agile, d’une application à l’aide de la norme ISO/CEI 29110. GÉNIE LOGICIEL, (118), 48‑58. doi:10.1109/TDEI.2009.5211872
López-Lira Hinojo, F. J. (2014). Agile, CMMI®, RUP®, ISO/IEC 12207... ACM SIGSOFT Software Engineering Notes, 39(2), 1‑5. doi:10.1145/2579281.2579299
Moreno-Campos, E., Sanchez-Gordón, M. L., Colomo-Palacios, R. et de Amescua Seco, A. (2014). Towards Measuring the Impact of the ISO/IEC 29110 Standard: A Systematic Review. Communications in Computer and Information Science, 425, 1‑12. doi:10.1007/978-3-662-43896-1_1
O’Connor, R. V. et Laporte, C. Y. (2014). An Innovative Approach to the Development of an International Software Process Lifecycle Standard for Very Small Entities. International Journal of Information Technologies and Systems

Approach, 7(1), 1‑22. doi:10.4018/ijitsa.2014010101
Organisation internationale de Normalisation. (2012). Ingénierie du logiciel--profils de cycle de vie pour très petits organismes (TPO). Partie 5-1-1, Guide de gestion et d’ingénierie : groupe de profil générique : Profil d’entrée. Guide de gestion et d’ingénierie : groupe de profil générique : Profil d’entrée, 2011.
Séguin, N. (2016). Note de cours MGL-7260.
Tripathy, P. et Naik, K. (2014). Software evolution and maintenance: A practitioner’s approach. Software Evolution and Maintenance: A Practitioner’s Approach. doi:10.1002/9781118964637
Trudel, S. (2006). Comparing Scrum and CMMI: to which extent can an Agile method be part of a mature process? Dans SPIN de Montréal, Septembre 2006 (p. 1‑27). CRIM.
Wikipedia. (s.d.-a). Agile software development. Repéré à https://en.wikipedia.org/wiki/Agile_software_development
Wikipedia. (s.d.-b). Agile software development.
Wikipedia. (s.d.-c). Incremental build model. Repéré 27 janvier 2018, à https://en.wikipedia.org/wiki/Incremental_build_model
Wikipedia. (s.d.-d). Spiral model. Repéré 27 janvier 2018, à https://en.wikipedia.org/wiki/Spiral_model