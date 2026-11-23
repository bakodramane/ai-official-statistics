---
layout: post
title: "IA et statistique officielle : qualité et contrôle ciblé des données"
description: "Le nouveau cadre de l’OCDE, les orientations européennes et des travaux d’instituts de statistique sur la détection d’erreurs et le contrôle sélectif."
date: 2026-11-23
lang: fr
translation_key: weekly-ai-update-2026-11-23
permalink: /fr/ia-statistique-qualite-controle-cible/
categories: [statistique-officielle, intelligence-artificielle]
tags: [IA, statistiques-agricoles, qualite, controle, gouvernance]
---

## Synthèse

Cinq évolutions d’octobre et de novembre 2026 illustrent la manière dont les organismes statistiques documentent et évaluent les contrôles de qualité liés à l’IA. Le nouveau cadre de l’OCDE traite explicitement de l’IA et des sources secondaires. Le Conseil de l’Union européenne a salué les priorités relatives à l’IA approuvées par le comité du Système statistique européen. En Italie, des chercheurs ont utilisé l’apprentissage automatique pour remonter à la source d’une erreur récurrente dans les déclarations de superficies irriguées. L’institut de statistique espagnol indique l’avoir utilisé pour établir l’ordre de vérification des codes de profession. Un résumé de l’Istat présente des projets allant de la collecte à la diffusion. Ces éléments n’ont pas le même statut : cadre publié, conclusions politiques adoptées, étude de cas, application déclarée en production et résumé d’atelier. [1–5]

## Vue d’ensemble

| Évolution | Étape du cycle statistique | Maturité | Lecture pratique |
|---|---|---|---|
| Cadre qualité de l’OCDE, 18 novembre | Toutes les étapes | Cadre publié (référence stable) | Intégrer l’IA au système d’assurance qualité [1] |
| Conclusions du Conseil de l’UE, 9 novembre | Conception ; intégration ; diffusion | Conclusions adoptées (stables) | Préparer les produits pour l’IA avec supervision humaine [2] |
| Étude de l’Istat sur les superficies irriguées, octobre | Contrôle ; validation | Étude de cas | Rechercher l’origine des erreurs lorsque les mêmes contrôles de cohérence échouent à plusieurs reprises [3] |
| Contrôle sélectif de l’institut espagnol, octobre | Codification ; contrôle ; suivi | Application déclarée en production | Classer les dossiers à vérifier manuellement selon la probabilité d’erreur multipliée par le poids de sondage [4] |
| Résumé de l’Istat sur la chaîne statistique, 2 novembre | De la collecte à la diffusion | Résumé d’atelier prospectif, émergent | Évaluer plusieurs usages avec des critères communs [5] |

## Conception et acquisition : définir la qualité avant le modèle

**L’OCDE propose une référence pour tout le cycle statistique.** Publié le 18 novembre, son cadre actualise l’assurance qualité face aux nouvelles sources, aux données secondaires, aux méthodes avancées et à l’IA. Le communiqué associé insiste sur la provenance des données, la transparence des transformations, le jugement professionnel et les métadonnées lisibles par machine. Pour un recensement agricole, le plan qualité pourrait préciser l’origine des données d’apprentissage, la version du modèle, la personne habilitée à réviser les résultats et les effets sur la couverture, la comparabilité et la confidentialité. Ce cadre institutionnel ne valide aucun modèle particulier. [1]

**Le Conseil de l’UE salue les priorités relatives à l’IA en statistique officielle.** Dans ses conclusions du 9 novembre, le Conseil a salué les priorités approuvées par le comité du Système statistique européen : l’usage responsable de l’IA dans la production statistique, une diffusion permettant aux systèmes d’IA d’exploiter les statistiques de manière fiable, l’adoption de l’IA dans les activités des instituts nationaux de statistique et d’Eurostat, et la mesure de son adoption et de ses effets sur l’économie et la société. Le Conseil a aussi souligné l’importance de la qualité, de la transparence, de la sécurité et de la supervision humaine. Il a encouragé la réutilisation des données administratives et des données détenues par le secteur privé, et envisage une réutilisation accrue des sources administratives et numériques en statistique agricole. Dans un projet d’appariement avec un registre d’exploitations, il convient de documenter les conditions d’accès aux données, la concordance des unités et des périodes de référence, ainsi que la gestion des révisions des sources avant d’introduire l’IA dans l’appariement ou la codification. [2]

## Collecte, contrôle et codification : concentrer la révision sur les erreurs importantes

**Un cas concret : les erreurs de déclaration des superficies irriguées.** Dans l’enquête italienne sur la structure des exploitations agricoles, des chercheurs de l’Istat ont utilisé l’apprentissage automatique pour repérer les variables associées aux échecs d’un contrôle de cohérence sur les superficies de cultures maraîchères irriguées. La vérification manuelle a confirmé que les superficies de cultures maraîchères sous serre avaient été incluses à tort dans le total irrigué déclaré. Ce résultat porte sur une seule variable. Un autre essai pourrait évaluer l’approche sur des données de cheptel ou de main-d’œuvre à partir de cas vérifiés par des spécialistes, en examinant la détection selon la taille de l’exploitation et le mode de collecte. [3]

**L’institut espagnol indique utiliser le contrôle sélectif en production.** Les auteurs signalent la mise en œuvre d’une procédure de contrôle des codes de profession dans l’enquête nationale sur la santé en Espagne. Pour classer les dossiers à vérifier manuellement, la procédure multiplie la probabilité estimée d’une erreur de codification par le poids de sondage du dossier. Des indicateurs automatisés servent au suivi de la qualité. Une équipe de statistique agricole pourrait tester ce principe sur les codes de cultures ou de professions, en conservant la réponse initiale, en consignant les corrections et en mesurant les effets sur les estimations, y compris dans les petits domaines. La mise en œuvre rapportée concerne une seule variable dans une seule enquête. [4]

## Intégration, rapports et diffusion : préserver le sens des résultats

**L’Istat présente un programme couvrant la chaîne statistique.** Un résumé daté du 2 novembre, préparé pour l’atelier de décembre de la CEE-ONU, mentionne la codification des produits, le contrôle des données, l’anonymisation de textes, l’intégration sémantique et l’accès en langue naturelle. Il rappelle que reproductibilité, comparabilité et confidentialité restent indispensables, quelles que soient les performances du modèle. Il s’agit de projets décrits dans un résumé prospectif, pas d’un produit unique disponible de bout en bout. Pour une diffusion assistée par IA, chaque statistique retrouvée devrait conserver sa définition, sa période, ses révisions et son incertitude. [5]

## Précautions de mise en œuvre et de gouvernance

- Distinguer les *références stables* (cadre de l’OCDE et conclusions adoptées) de l’*application déclarée en production* et des *travaux émergents*. La publication d’un document n’établit pas la disponibilité d’un logiciel.
- Comparer l’approche proposée aux règles de contrôle existantes et à la révision humaine sur des dossiers représentatifs tenus à l’écart de l’apprentissage ; mesurer les erreurs non détectées, les fausses alertes, le temps de révision et l’effet sur les estimations.
- Examiner les résultats par langue, taille d’exploitation et domaine géographique. Conserver valeurs sources, versions des nomenclatures et des modèles, corrections et journal d’exécution.
- Traiter les microdonnées confidentielles dans une infrastructure autorisée ; tester les risques de divulgation, les injections d’instructions et les droits d’accès avant tout essai d’IA générative.

## Conséquences pour les instituts de statistique

Un usage limité et vérifiable — détection d’erreurs systématiques ou sélection des dossiers à réviser — offre un point de départ concret. Le plan qualité et les métadonnées de diffusion doivent progresser en parallèle. La validation statistique demeure sous la responsabilité de l’équipe habilitée. [1–5]

## Prochaines actions

1. Choisir une variable d’enquête agricole et constituer un échantillon de validation expertisé tenant compte du plan de sondage.
2. Comparer les contrôles actuels à un classement assisté par IA selon les erreurs influentes manquées et le temps de travail.
3. Ajouter au journal de traitement les versions des modèles et des sources, ainsi que les corrections humaines.
4. Vérifier que les tableaux publiés exposent des définitions, périodes de référence et révisions lisibles par machine.

## Sources

1. OCDE (18 novembre 2026), [*OECD Statistics and Data Quality Assurance Framework*](https://www.oecd.org/en/publications/oecd-statistics-and-data-quality-assurance-framework_1d7d2416-en.html) ; [communiqué](https://www.oecd.org/en/about/news/press-releases/2026/11/as-ai-transforms-the-data-landscape-oecd-strengthens-safeguards-for-trustworthy-statistics.html).
2. Conseil de l’Union européenne (9 novembre 2026), [conclusions 2026 sur les statistiques européennes](https://data.consilium.europa.eu/doc/document/ST-15472-2026-INIT/en/pdf).
3. Rosati et al. (octobre 2026), [« Detecting Systematic Errors in Agricultural Survey Data Using Machine Learning: A Feature Selection Approach »](https://unece.org/taxonomy/term/620?page=1#:~:text=SDE2026%20%2D%20PAPER%20%2D%20Detecting%20Systematic%20Errors%20in%20Agricultural%20Survey%20Data%20Using%20Machine%20Learning), communication à la réunion de la CEE-ONU sur le contrôle des données statistiques.
4. Barragán et al. (octobre 2026), [« Machine Learning-Based Selective Editing for Categorical Data in Official Statistics: From Methodology to Monitored Production »](https://unece.org/taxonomy/term/698#:~:text=SDE2026%20%2D%20PAPER%20%2D%20S4%20Machine%20Learning%2DBased%20Selective%20Editing), communication à la réunion de la CEE-ONU sur le contrôle des données statistiques.
5. Summa, D. (2 novembre 2026), [« AI and LLMs across modern statistical pipeline: the Istat's experience »](https://unece.org/taxonomy/term/620#:~:text=AI%20and%20LLMs%20across%20modern%20statistical%20pipeline), résumé pour l’atelier de la CEE-ONU sur la modernisation des statistiques officielles.
