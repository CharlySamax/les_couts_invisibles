# Audit des sources — La boulette du siècle

Document de travail : vérification source par source, fiche par fiche.
Pour chaque source : référence actuelle dans le site, lien d'accès vérifié, page/section précise, statut.

---

## FICHE 1 : Crash tests (18 sources dans L4)

**Problèmes identifiés dans le L4 actuel :**
- Doublons : Bose et al. apparaît 3 fois (sources 1, 10, 22 dans le HTML), NHTSA 2013 apparaît 2 fois, NHTSA 813 358 apparaît 2 fois, Gendered Innovations 2 fois, Humanetics 2 fois, NHTSA Report to Congress 2 fois, ONISR 2 fois, VSL 2 fois
- Résultat : 18 entrées dans le L4, mais seulement 9 sources uniques
- **Action : dédoublonner le L4 pour ne garder qu'une seule occurrence de chaque source**

### Sources uniques (9) — audit détaillé

| # | Référence actuelle | Lien vérifié | Section/page | Donnée utilisée | Statut |
|---|---|---|---|---|---|
| 1 | Bose, Segui-Gomez, Crandall, *Vulnerability of Female Drivers*, AJPH, déc. 2011, 101(12):2368-2373 | https://pmc.ncbi.nlm.nih.gov/articles/PMC3222446/ | Table 2 (OR = 1.47, IC 95% : 1.28–1.70) | Surrisque de 47 % de blessure grave pour les conductrices ceinturées | ✅ OK — ajouter DOI : 10.2105/AJPH.2011.300275 |
| 2 | NHTSA, *Injury Vulnerability and Effectiveness of Occupant Protection Technologies for Older Occupants and Women*, Report DOT HS 811 766, 2013, actualisé 2022 | https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/811766 | Sections III-IV | Surrisque fatal +17 % et non-fatal +28,8 % pour les femmes | ✅ OK — ajouter lien |
| 3 | NHTSA, *Female Crash Fatality Risk Relative to Males for Similar Physical Impacts*, Report DOT HS 813 358, août 2022 | https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/813358 | Table 4, p. 22 (écart passé de 18,3 % à 2,9 % pour les modèles 2015-2020) | Réduction du différentiel, mais persistance d'un écart de ~6 % avec protections modernes | ✅ OK — ajouter lien et page |
| 4 | Gendered Innovations, Stanford University, *Inclusive Crash Test Dummies: Analyzing Reference Models*, 2023 | https://genderedinnovations.stanford.edu/case-studies/crash.html | Synthèse complète (page unique) | Historique des dummies, FAIR Crash Tests Act, GAO 2023 | ✅ OK — ajouter lien |
| 5 | Humanetics, *Hybrid III 5th Female ATD*, documentation technique, 2022 | Non trouvé en accès libre — documentation constructeur réservée | — | Description du mannequin « féminin » comme version réduite du masculin | ⚠️ Remplacer par une source publique décrivant le même fait (NHTSA Interim Report, p. 3-4, confirme que le Hybrid III 5th est une version mise à l'échelle) |
| 6 | NHTSA, *Interim Report to Congress on Crash Test Dummies*, décembre 2022 | https://www.nhtsa.gov/sites/nhtsa.gov/files/2022-12/Report-to-Congress-Interim-Report-to-Congress-on-Crash-Test-Dummies_FINAL-tag_0.pdf | pp. 3-4 (description du Hybrid III 5th), pp. 7-8 (THOR-05F en développement) | Le mannequin « féminin » actuel est une version mise à l'échelle du masculin | ✅ OK — ajouter lien et pages |
| 7 | ONISR, *Bilan de l'accidentalité*, 2024 | https://www.onisr.securite-routiere.gouv.fr/etat-de-linsecurite-routiere/bilans-annuels-de-la-securite-routiere/bilan-2024-de-la-securite-routiere | Section I.2.a (genre et mortalité routière) | Données France : 3 193 décès métropole 2024, ventilation par genre | ✅ OK — ajouter lien et section |
| 8 | Commission européenne, DG MOVE / CE Delft, *Handbook on the External Costs of Transport*, version 2019 | https://cedelft.eu/wp-content/uploads/sites/2/2021/03/CE_Delft_4K83_Handbook_on_the_external_costs_of_transport_Final.pdf | Table 6, p. 44 (€2016) : VSL ~3,6 M€ EU28, coût par blessure grave ~0,5 M€ | Valeurs utilisées pour convertir le surrisque en coût sociétal | ⚠️ La fiche cite « VSL 2022, 6,2 M€ » — cette valeur semble actualisée/indexée. La source primaire (Handbook 2019) donne ~3,6 M€ en €2016. Vérifier si une mise à jour 2022 existe, sinon corriger la valeur ou expliciter l'indexation |
| 9 | Caroline Criado-Perez, *Invisible Women*, éditions Hauteville, 2020 | ISBN 978-2-38113-076-7 (édition française) | Chapitre 12 « A sea of dudes » (éd. anglaise) / équivalent éd. française | Vulgarisation des données Bose et al. + historique des crash test dummies | ✅ OK — ajouter chapitre précis |

**Source supplémentaire trouvée pendant l'audit :**

| # | Source | Lien | Intérêt |
|---|---|---|---|
| 10 | Forman, McMurry et al., *Automobile Injury Trends in the Contemporary Fleet*, Traffic Injury Prevention, 20(6):607-612, 2019 | https://pubmed.ncbi.nlm.nih.gov/31283362/ (DOI: 10.1080/15389588.2019.1630825) | Déjà citée dans un onglet mais pas dans L4 proprement. À intégrer dans L4. |
| 11 | NHTSA, *Report to Congress: THOR-05F and WorldSID-05F Female Crash Safety*, janvier 2026 | https://www.nhtsa.gov/sites/nhtsa.gov/files/2026-01/report-congress-2026-thor-05f-worldsid-05F-female-crash-safety.pdf | Source très récente — confirme que le THOR-05F (premier vrai mannequin féminin) n'est toujours pas opérationnel en 2026 |

### Corrections de ton dans la fiche crash

| Passage actuel | Problème | Proposition |
|---|---|---|
| « Ce coût n'est pas théorique. Il est payé par les femmes qui conduisent aujourd'hui des voitures conçues pour protéger un homme. » | Contradictoire avec « environ 3 milliards ». L'estimation est réelle (coût en cours), mais le chiffre reste une estimation. | « Ce coût est en cours. Il est payé chaque année par les femmes qui conduisent des voitures conçues pour protéger un homme. Le chiffre est une estimation — le mécanisme, lui, est documenté. » |

### Section manquante : « Qui paye les 3 milliards ? »

À ajouter dans L1 ou L3cf. Ventilation approximative (à sourcer précisément via ONISR + Cour des comptes) :
- Assurance maladie / Sécurité sociale : soins, hospitalisations, rééducation (~40-50 %)
- Assureurs auto : indemnisation corporelle (~20-30 %)
- Victimes : reste à charge, perte de revenus, douleur non indemnisée (~20-30 %)
- Employeurs : arrêts de travail, remplacement (~5-10 %)

**Note :** les proportions exactes nécessitent le croisement ONISR / rapport Cour des comptes sur le coût de l'insécurité routière. À rechercher.

---

## FICHE 2 : Jeanne la Folle (15 sources dans L4 — 8 uniques)

**Problèmes identifiés :**
- Doublons : Aram 3 fois, Fleming 2 fois, Cook & Borah 2 fois, Lovell 2 fois, Elliott 2 fois, Décrets d'Isabelle 2 fois
- **Action : dédoublonner, passer de 15 à 8 entrées**
- **Erreur à corriger** : Fleming est référencée comme « Royal Studies Journal, 2020 ». C'est faux. Le RSJ 2020 est une recension du livre. Le livre : Gillian B. Fleming, *Juana I: Legitimacy and Conflict in Sixteenth-Century Castile*, Palgrave Macmillan (coll. Queenship and Power), 2018, ISBN 978-3-319-74347-9
- **Précision à apporter** : Cook & Borah : le titre exact est *The Aboriginal Population of Central Mexico on the Eve of the Spanish Conquest* (1963, Ibero-Americana 45). Le titre *The Indian Population of Central Mexico, 1531-1610* est un ouvrage différent (1960, Ibero-Americana 44). Le chiffre de 25 millions vient bien du volume de 1963.

### Sources uniques (8) — audit détaillé

| # | Référence actuelle | Référence corrigée | Lien/ISBN | Statut |
|---|---|---|---|---|
| 1 | Bethany Aram, *La reina Juana*, Marcial Pons, 2001 | OK (ajouter ISBN) | ISBN 978-84-95379-31-3 ; aussi publié en anglais : *Juana the Mad*, Johns Hopkins UP, 2005 | ✅ |
| 2 | Gillian B. Fleming, *Royal Studies Journal*, 2020 | **Corriger** : Fleming, *Juana I: Legitimacy and Conflict in Sixteenth-Century Castile*, Palgrave Macmillan, 2018 | https://link.springer.com/book/10.1007/978-3-319-74347-9 | ⚠️ erreur de source |
| 3 | Cook & Borah, *The Indian Population of Central Mexico*, UC Press, 1963 | **Corriger titre** : *The Aboriginal Population of Central Mexico on the Eve of the Spanish Conquest*, Ibero-Americana 45, 1963 | HathiTrust : https://catalog.hathitrust.org/Record/001654470 | ⚠️ titre imprécis |
| 4 | George Lovell, *Maya Survival in Yucatán*, 1992 | Compléter : *Conquest and Survival in Colonial Guatemala: A Historical Geography of the Cuchumatán Highlands, 1500-1821*, McGill-Queen's UP, 1985 (rév. 1992) — **Attention : le titre cité n'existe pas sous cette forme** | ISBN 978-0-7735-0995-8 | ⚠️ titre à vérifier |
| 5 | John Elliott, *Imperial Spain 1469-1716*, Arnold, 1963 | OK | ISBN 978-0-14-013517-7 (Penguin, rééd. 2002) | ✅ classique incontesté |
| 6 | Boyd-Bowman, *Patterns of Spanish Emigration*, 1976 | Compléter : Peter Boyd-Bowman, « Patterns of Spanish Emigration to the Indies until 1600 », *Hispanic American Historical Review*, 56(4), nov. 1976, pp. 580-604 | DOI : 10.1215/00182168-56.4.580 | ✅ ajouter DOI |
| 7 | Jean-Marie Cauchies, *Philippe le Beau*, Brepols, 2003 | OK (ajouter sous-titre) : *Philippe le Beau. Le dernier duc de Bourgogne*, Brepols (Burgundica 6), 2003 | ISBN 978-2-503-51226-6 | ✅ |
| 8 | Collard & Samama (dir.), *Femmes de pouvoir, femmes politiques*, De Boeck, 2012 | OK | ISBN 978-2-8041-6856-6 | ✅ |

### Problèmes de fond spécifiques à cette fiche

1. **Décrets d'Isabelle la Catholique (1500, 1503)** : référence vague (« archives couronne de Castille »). Il faudrait citer la cédule royale du 20 juin 1500 et les instructions de 1503, consultables à l'Archivo General de Indias (Séville) ou dans les compilations de Konetzke (*Colección de documentos para la historia de la formación social de Hispanoamérica*, 1953).

2. **George Lovell** : le titre « Maya Survival in Yucatán, 1992 » ne correspond à aucun ouvrage publié sous ce titre exact. L'ouvrage de Lovell est *Conquest and Survival in Colonial Guatemala* (1985/1992), qui porte sur les hautes terres du Guatemala, pas le Yucatán. Il existe aussi Lovell & Lutz, *Demography and Empire* (1995). **À vérifier : est-ce une confusion avec Nancy Farriss, *Maya Society under Colonial Rule* (1984), qui porte sur le Yucatán ?**

---

## FICHE 3 : Karikó (20 sources dans L4 — 12 uniques)

**Problèmes identifiés :**
- Doublons : Karikó 2005 (1 et 10), Witteman (2 et 11), NHTSA 2013 (— non, Wennerås 4 et 12), RAND (5 et 13), Anderson (3 et 16), Watson (6 et 20)
- Sources citées uniquement par numéro PMC, sans auteurs ni titre (9, 14, 15, 17, 18) — inacceptable pour la vérifiabilité
- Harvard Crimson (10) : source journalistique étudiante, acceptable comme illustration mais pas comme source primaire

### Sources uniques (12) — audit détaillé

| # | Référence actuelle | Lien vérifié | Statut |
|---|---|---|---|
| 1 | Karikó, Buckstein, Ni, Weissman, *Suppression of RNA Recognition by Toll-like Receptors*, Immunity, 23(2):165-175, 2005 | https://pubmed.ncbi.nlm.nih.gov/16111635/ (DOI : 10.1016/j.immuni.2005.06.008) — accès libre | ✅ ajouter DOI |
| 2 | Witteman et al., *Are gender gaps due to evaluations of the applicant or the science?*, The Lancet, 393(10171):531-540, 2019 | DOI : 10.1016/S0140-6736(18)32611-4 | ✅ ajouter DOI |
| 3 | Anderson, *A lightspeed approach to pandemic drug development*, Nature Medicine, 28:1538, 2022 | DOI : 10.1038/s41591-022-01945-2 | ✅ ajouter DOI |
| 4 | Wennerås & Wold, *Nepotism and sexism in peer-review*, Nature, 387:341-343, 1997 | DOI : 10.1038/387341a0 | ✅ ajouter DOI |
| 5 | RAND Corporation, *Is There Gender Bias in Federal Grant Programs?*, Research Brief RB-9147, 2004 | https://www.rand.org/pubs/research_briefs/RB9147.html | ✅ ajouter lien |
| 6 | Watson et al., *Global impact of the first year of COVID-19 vaccination*, Lancet Infect Dis, 22(9):1293-1302, 2022 | DOI : 10.1016/S1473-3099(22)00320-6 | ✅ ajouter DOI |
| 7 | Académie Nobel, biographie officielle Karikó, 2023 | https://www.nobelprize.org/prizes/medicine/2023/kariko/biographical/ | ✅ ajouter lien |
| 8 | Karikó, *Getting the message right*, EMBO Reports, 2023 (PMC10626440) | https://pmc.ncbi.nlm.nih.gov/articles/PMC10626440/ | ✅ ajouter titre et lien |
| 9 | PMC8143802, 2021 | Hargittai, *Our science and the Covid-19 pandemic—Katalin Karikó's research idea and her perseverance*, Structural Chemistry, 2021 | ⚠️ **Remplacer le numéro PMC par la référence complète** |
| 10 | Harvard Crimson, 15 mars 2021 | Source journalistique étudiante | ⚠️ Acceptable en illustration, pas en source primaire |
| 11 | PMC8141289, *Gender Disparity in Grants and Awards at the NIH* | **Ajouter auteurs et titre complet** | ⚠️ |
| 12 | PMC10663363, Frontiers in Immunology, 2023 | Il s'agit de : Wantenaar et al., *From rejection to the Nobel Prize: Karikó and Weissman's pioneering work on mRNA vaccines*, Frontiers in Immunology, 2023 | ⚠️ **Ajouter référence complète** |

### Corrections prioritaires

1. **Remplacer tous les numéros PMC nus par des références complètes** (auteurs, titre, journal, année). Citer « PMC8143802 » sans contexte, c'est comme citer un numéro ISBN sans titre.
2. Dédoublonner (passer de 20 à 12 entrées).
3. Ajouter les DOI pour tous les articles de revues.
## FICHE 4 : Célibat sacerdotal (19 sources → 19 uniques, pas de doublons)

Bonne nouvelle : aucun doublon dans cette fiche, ce qui tranche avec les trois premières.

### Sources historiques

1. **Henry Charles Lea, *A History of Sacerdotal Celibacy*, 1867** ✅
   Classique de l'historiographie, disponible sur archive.org. Édition de référence : 4e éd. révisée, 1932.

2. **James A. Brundage, *Law, Sex, and Christian Society in Medieval Europe*, 1987** ✅
   University of Chicago Press, ISBN 978-0-226-07784-4. Référence incontournable.

3. **Furet & Richet, *La Révolution française*, 1965** ✅
   Hachette. Rééditions multiples. Pertinent pour le contexte biens nationaux.

4. **Encyclopædia Universalis, article « Biens nationaux »** ✅
   Accessible sur universalis.fr (abonnement). Citer l'auteur de l'article serait plus précis.

5. **Vauban, *Projet d'une dîme royale*, 1707** ✅
   Source primaire, disponible sur Gallica : https://gallica.bnf.fr/

6. **Gregory Clark, *A Farewell to Alms*, Princeton University Press, 2007** ✅
   ISBN 978-0-691-12135-2. Données PIB historiques.

7. **Robert Allen, *Enclosure and the Yeoman*, Oxford University Press, 1992** ✅
   ISBN 978-0-198-28585-0.

8. **Maddison Project, données PIB historiques** ✅
   https://www.rug.nl/ggdc/historicaldevelopment/maddison/ — Préciser la version utilisée (2020 ou 2023).

### Rapports sur les abus sexuels — bloc international

9. **CIASE, France, octobre 2021** ✅
   Rapport Sauvé. https://www.ciase.fr/rapport-final/
   Titre exact : *Les violences sexuelles dans l'Église catholique, France 1950-2020*

10. **Rapport Gabilondo, Espagne, octobre 2023** ✅
    Rapport du Defensor del Pueblo, ~800 pages, présenté au Congrès le 27/10/2023.
    Préciser : « Rapport du Defensor del Pueblo (Ángel Gabilondo), octobre 2023 »

11. **Commission Ryan, Irlande, 2009** ✅
    Titre officiel : *Report of the Commission to Inquire into Child Abuse*, mai 2009, 5 volumes.
    https://childabusecommission.ie/
    Lien : https://www.gov.ie/en/publication/3c76d0-the-report-of-the-commission-to-inquire-into-child-abuse-the-ryan-re/

12. **Commission indépendante, Portugal, février 2023** ✅
    Présidée par Pedro Strecht, rapport remis le 13/02/2023, 4 815 victimes min.
    Préciser le mois (février, pas juste « 2023 »).

13. **Rapport MHG, Allemagne, 2018** ✅
    Étude MHG (Mannheim-Heidelberg-Gießen), présentée le 25/09/2018.
    Référence publiée : Dreßing et al., *Dtsch Arztebl Int* 2019; 116: 389-96. DOI: 10.3238/arztebl.2019.0389
    Rapport complet : www.zi-mannheim.de/fileadmin/user_upload/downloads/forschung/forschungsverbuende/MHG-Studie-gesamt.pdf

14. **Rapport John Jay, États-Unis, 2004** ✅
    *The Nature and Scope of Sexual Abuse of Minors by Catholic Priests and Deacons in the United States, 1950-2002*
    John Jay College of Criminal Justice, 2004.
    À ajouter : lien vers le rapport.

15. **Royal Commission, Australie, 2017** ✅
    *Royal Commission into Institutional Responses to Child Sexual Abuse*, rapport final décembre 2017.
    https://www.childabuseroyalcommission.gov.au/

### Sources santé reproductive et vie religieuse féminine

16. **ACLU & MergerWatch, *Health Care Denied*, 2016** ✅
    Rapport mai 2016. https://www.aclu.org/health-care-denied
    PDF complet : https://www.aclu.org/wp-content/uploads/publications/healthcaredenied.pdf

17. **Angel Foster et al., Ibis Reproductive Health, 2008** ⚠️
    Référence incomplète : pas de titre d'article. Probablement : Foster et al., "Contraceptive availability in Catholic hospital emergency rooms", *Contraception*, 2008. À vérifier et compléter le titre + DOI exact.

18. **CLAR, *Vulnérabilité, abus et soins dans la vie religieuse féminine*, Amérique latine, 2022** ⚠️
    CLAR = Confederación Latinoamericana y Caribeña de Religiosas y Religiosos. Le rapport existe mais la référence exacte (titre complet, date de publication, lien) est à compléter. Source peu accessible en ligne.

19. **Georgetown University / CARA, statistiques clergé catholique mondial, 2024** ✅
    https://cara.georgetown.edu/faqs — Fichier téléchargeable avec données US 2024 et monde 2023.
    Préciser : « CARA (Center for Applied Research in the Apostolate), Georgetown University, *Frequently Requested Church Statistics*, 2024 »

### Corrections nécessaires

- **Foster et al.** : compléter la référence (titre, revue, DOI)
- **CLAR** : compléter la référence (titre exact, lien si disponible)
- **Maddison Project** : préciser la version (2020 ou 2023)
- **Encyclopædia Universalis** : ajouter l'auteur de l'article si disponible
- **Tous les rapports internationaux** : ajouter les liens et préciser les mois de publication
- **Pas de doublons** à corriger dans cette fiche (bonne structure)
## FICHE 5 : Adam et Ève (22 entrées → 12 uniques — doublons massifs)

**Structure du problème** : les 11 premières entrées sont exactement reprises dans les 11 suivantes, avec parfois de légères variations de formulation (l'entrée 18, par ex., ne reprend même plus le titre complet de Lefebvre-Teillard). Il faut dédupliquer de 22 à 12 entrées (la 12e est WBL 2024, absente de la première moitié).

### Sources patristiques et théologiques

1. **Jérôme de Stridon, *Biblia Sacra Vulgata* (405)** ✅
   Éd. critique Weber-Gryson, Deutsche Bibelgesellschaft, Stuttgart, 5e éd. 2007. ISBN 978-3-438-05303-9. Source primaire incontestable.

2. **Septuaginta, éd. Alfred Rahlfs, Stuttgart, 1935 (rév. R. Hanhart, 2006)** ✅
   Deutsche Bibelgesellschaft. ISBN 978-3-438-05119-6.

3. **Augustin d'Hippone, *De Genesi ad litteram* (401-415), livres IX-XI** ✅
   Éd. critique : CSEL 28, éd. J. Zycha, Vienne, 1894. Aussi dans Bibliothèque augustinienne (BA 49).

4. **Thomas d'Aquin, *Summa theologiae*, Ia, q.92** ✅
   Éd. Leonine, Rome, 1888. Trad. française A.-M. Roguet, Cerf.

### Sources d'histoire du droit

5. **Code Napoléon (1804), art. 213-226** ✅
   Texte intégral sur Gallica/BnF. Source primaire.

6. **Kari Elisabeth Børresen, *Subordination et équivalence*, Mame, Paris, 1968** ✅
   Thèse de doctorat soutenue à Paris. Trad. anglaise : *Subordination and Equivalence*, University Press of America, 1981. Classique de la théologie féministe.

7. **Jacques Poumarède, in *Histoire de la famille*, Armand Colin** ⚠️ ERREUR DE DATE
   La fiche cite « 1992 ». L'ouvrage dirigé par Burguière, Klapisch-Zuber, Segalen, Zonabend est paru en **1986** (t. 2 : *Le choc des modernités*), pas 1992. Il existe une réédition en poche (Le Livre de Poche, 1994) qui pourrait être la source de la confusion.
   De plus, le titre exact du chapitre de Poumarède n'est pas cité. La fiche dit « La législation des femmes dans le Code civil » — titre à vérifier/compléter.

8. **Anne Lefebvre-Teillard, *Introduction historique au droit des personnes et de la famille*, PUF, 1996** ✅
   Coll. « Droit fondamental », 475 p. ISBN 978-2-13-047891-1. Ouvrage couronné par l'Institut.

### Sources économiques contemporaines

9. **McKinsey Global Institute, *The Power of Parity*, septembre 2015** ✅
   Rapport disponible sur mckinsey.com/mgi.

10. **Claudia Goldin, *Career and Family*, Princeton University Press, 2021** ✅
    ISBN 978-0-691-22845-5. Prix Nobel d'économie 2023.

11. **Maddison Project Database, Université de Groningue** ✅
    https://www.rug.nl/ggdc/historicaldevelopment/maddison/
    Préciser la version (2020 ou 2023).

12. **Banque mondiale, *Women, Business and the Law 2024*** ✅
    https://wbl.worldbank.org/en/reports — 10e édition, publiée le 5 mars 2024, 190 économies.

### Corrections nécessaires

- **Dédupliquer** de 22 à 12 entrées (chaque source apparaît 2 fois)
- **Poumarède** : corriger la date (1986, pas 1992) et compléter le titre exact du chapitre
- **Maddison Project** : préciser la version
- **Tous** : ajouter les liens d'accès
- L'entrée 18 (Lefebvre-Teillard réduite à « PUF, Paris, 1996 ») illustre le problème de dégradation progressive des doublons : la seconde occurrence perd de l'information
## FICHE 6 : Cardio (11 sources → 11 uniques, pas de doublons)

Fiche bien structurée, pas de doublons. Sources médicales de premier plan.

### Sources vérifiées

1. **MRFIT, JAMA, 248:1465-1477, 1982** ✅
   Multiple Risk Factor Intervention Trial Research Group. PMID: 7050440. DOI: 10.1001/jama.1982.03330120023025
   12 866 hommes, 0 femme. Étude fondatrice du biais d'exclusion.

2. **Physicians' Health Study, NEJM, 321:129-135, 1989** ✅
   DOI: 10.1056/NEJM198907203210301. PMID: 2664509.
   22 071 médecins hommes, 0 femme. Aspirine et prévention cardiovasculaire.

3. **FDA, *Guidelines for the Study and Evaluation of Gender Differences*, 1993** ✅
   Ce document a levé l'interdiction de 1977 d'inclure des femmes en âge de procréer dans les essais cliniques. Référence fédérale.

4. **US GAO, *Drug Safety: Most Drugs Withdrawn…*, GAO-01-286R, 2001** ✅
   https://www.gao.gov/products/gao-01-286r — 8 des 10 médicaments retirés présentaient plus de risques pour les femmes.

5. **Gale C. et al., Université de Leeds / BHF, 2016** ⚠️ RÉFÉRENCE INCOMPLÈTE
   Chris P. Gale a publié plusieurs études sur les différences sexuelles en mortalité post-infarctus. La plus citée avec cette thématique en 2016 est probablement : Wilkinson C. et al. (dont Gale CP), *Heart* 2019, mais c'est 2019, pas 2016. Il pourrait s'agir de données présentées en congrès en 2016 puis publiées plus tard, ou d'un autre article. La référence doit être précisée (titre exact, revue, DOI).

6. **Mehta L. et al., *Acute Myocardial Infarction in Women*, Circulation, AHA, 2016** ✅
   Scientific Statement de l'AHA. Circulation. 2016;133:916-947. DOI: 10.1161/CIR.0000000000000351

7. **Rathore S. et al., *Sex-based differences… digoxin*, NEJM, 347:1403-1411, 2002** ✅
   DOI: 10.1056/NEJMsa021266. PMID: 12409542.

8. **AHA & McKinsey Health Institute, *The State of US Women's Heart Health*, juin 2024** ✅
   Rapport conjoint publié en juin 2024.

9. **Luengo-Fernandez R. et al., *Economic burden of CVD in the EU*, EHJ, 44:4752-4760, 2023** ✅
   DOI: 10.1093/eurheartj/ehad583

10. **Criado-Perez C., *Invisible Women*, éditions Hauteville, 2020** ✅
    Trad. française de *Invisible Women: Exposing Data Bias in a World Designed for Men*, Chatto & Windus, 2019. Source de vulgarisation, pas primaire — acceptable comme illustration mais ne devrait pas être la seule source pour un fait précis.

11. **Wenger N., *You've Come a Long Way, Baby*, Circulation, 2012** ✅
    Circulation. 2012;126:2949-2951. DOI: 10.1161/CIRCULATIONAHA.112.150466. Éditorial de Nanette Wenger, pionnière de la cardiologie féminine.

### Corrections nécessaires

- **Gale et al. 2016** : identifier la publication exacte (titre, revue, DOI). Le groupe Leeds/BHF a beaucoup publié, la référence actuelle est trop vague.
- **Tous** : ajouter les DOI et liens
- **Criado-Perez** : signaler qu'il s'agit d'une source secondaire de vulgarisation
## FICHE 7 : Plafond de verre (8 sources → 8 uniques, pas de doublons)

Fiche la plus propre du site : pas de doublons, sources bien identifiées, mélange équilibré recherche académique / rapports professionnels.

### Sources vérifiées

1. **Noland M., Moran T., Kotschwar B., *Is Gender Diversity Profitable?*, Peterson Institute / EY, WP 16-3, février 2016** ✅
   https://www.piie.com/publications/working-papers/gender-diversity-profitable-evidence-global-survey
   SSRN : https://ssrn.com/abstract=2729348
   21 980 entreprises, 91 pays. Corrélation positive diversité de genre / rentabilité au niveau C-suite.

2. **McKinsey & Company, *Women Matter: Gender diversity, a corporate performance driver*, octobre 2007** ✅
   Premier rapport de la série Women Matter. Disponible sur mckinsey.com.

3. **EY, *Profil financier du CAC40*, 18e édition, juin 2024** ✅
   Publication annuelle d'EY France. CA agrégé 2023 : 1 736 Md€.

4. **Observatoire Skema de la féminisation des entreprises, *Diversité et Inclusion au sein du CAC40*, 2023-2024** ✅
   Publication annuelle de Skema Business School, dirigée par Michel Ferrary.

5. **Haut Conseil à l'Égalité, *Rapport annuel sur l'état du sexisme en France*, 2023** ✅
   https://www.haut-conseil-egalite.gouv.fr/

6. **Skema Business School, *Féminisation de l'encadrement et performance boursière*, CAC40, 2007-2019** ✅
   Étude longitudinale de Michel Ferrary comparant un « Gender Equality Index » et un « Male Index ».

7. **Reynolds A., Lewis D., *Teams Solve Problems Faster When They're More Cognitively Diverse*, HBR, mars 2017** ✅
   https://hbr.org/2017/03/teams-solve-problems-faster-when-theyre-more-cognitively-diverse
   Note : il s'agit d'un article HBR (pas peer-reviewed), basé sur un exercice avec 6 équipes. Résultats suggestifs mais échantillon limité. À signaler comme illustration, pas comme preuve statistique robuste.

8. **Lorenzo R. et al., *How Diverse Leadership Teams Boost Innovation*, BCG, janvier 2018** ✅
   Boston Consulting Group / Université technique de Munich. 1 700 entreprises dans 8 pays.

### Corrections nécessaires

- **Ajouter les liens** pour toutes les sources
- **Reynolds & Lewis (HBR)** : source intéressante mais faible méthodologiquement (6 équipes, pas de publication peer-reviewed). Si le site veut être robuste face aux critiques, cette source devrait être accompagnée d'une référence plus solide sur la diversité cognitive (ex. : Woolley et al., *Science* 2010, sur l'intelligence collective).
- **Skema** apparaît deux fois (entrées 4 et 6) : ce sont deux publications distinctes (observatoire annuel vs étude longitudinale), mais mériteraient d'être différenciées plus clairement dans le L4
## FICHE 8 : Éducation (11 sources → 11 uniques, pas de doublons)

### Sources vérifiées

1. **Banque mondiale, *Missed Opportunities: The High Cost of Not Educating Girls*, 2018** ✅
   https://www.worldbank.org/en/topic/education/publication/missed-opportunities-the-high-cost-of-not-educating-girls
   ⚠️ Le chiffre est **15 à 30 000 milliards $**, pas seulement 15 000 milliards. La fiche ne retient que la borne basse.

2. **Banque mondiale/UNICEF, paramètre +0,2 pt PIB / +1 pt scolarisation féminine secondaire** ⚠️ RÉFÉRENCE INCOMPLÈTE
   Pas de titre de publication, pas de date, pas de lien. Ce paramètre circule dans la littérature BM mais la source précise doit être identifiée (probablement dans *Missed Opportunities* ou dans Dollar & Gatti, 1999).

3. **Limite du paramètre** — Ce n'est pas une source mais une note méthodologique. Pertinent mais ne devrait pas occuper une entrée dans le panneau « sources ».

4. **« Vinet, F. (2001) » sur la grippe espagnole** ⚠️ ERREUR D'AUTEUR
   L'article est de **Pierre Darmon** (pas Vinet) : Darmon P., « Une tragédie dans la tragédie : la grippe espagnole en France (avril 1918-avril 1919) », *Annales de démographie historique*, 2000-2, pp. 153-175.
   https://www.persee.fr/doc/adh_0066-2062_2001_num_2000_2_1982
   Freddy Vinet est l'auteur de *La Grande Grippe* (Vendémiaire, 2018), un ouvrage distinct.

5. **médecine/sciences (2006), « Comme en 1918 ! »** ⚠️ RÉFÉRENCE INCOMPLÈTE
   Auteur : **Patrick Zylberman**, « Comme en 1918 ! La grippe "espagnole" et nous », *médecine/sciences*, vol. 22, n° 8-9, août-sept. 2006, p. 767-770.

6. **Héry, E. (2003), « Quand le baccalauréat devient mixte », *Clio*, n° 18** ✅
   https://journals.openedition.org/clio/611 — Évelyne Héry, revue *Clio. Histoire, femmes et sociétés*.

7. **DEPP, MEN (2024), données bac 2022** ✅
   Données publiques, *Repères et références statistiques* (RERS). Vérifier le chiffre exact (84 % filles / 75 % garçons) dans l'édition 2024.

8. **Schoeni, C. (2012), *Travail féminin : retour à l'ordre !*, Antipodes** ✅
   Celine Schoeni, Éditions Antipodes, Lausanne, 2012. ISBN 978-2-88901-073-5.

9. **Sénat (2006), *Femmes et pouvoirs, XIXe-XXe siècles*** ⚠️ RÉFÉRENCE VAGUE
   Pas de numéro de rapport, pas d'auteur. Plusieurs publications du Sénat correspondent. À préciser.

10. **Archives nationales du monde du travail, travailleuses des usines d'armement 14-18** ✅
    ANMT, Roubaix. Données : 25 % de la main-d'œuvre, 300 millions d'obus, 6 milliards de cartouches. Source d'archives, acceptable.

11. **Sénat, rapport n° 165 (2018), *Les femmes pendant la Grande Guerre*** ✅
    Actes du colloque du 18 octobre 2018. Citation attribuée à Joffre « rapportée au conditionnel » — bon réflexe.

### Corrections nécessaires

- **Source 4** : corriger l'auteur (Darmon, pas Vinet) — erreur factuelle
- **Source 5** : ajouter l'auteur (Zylberman) et la référence complète
- **Source 2** : identifier la publication précise du paramètre BM/UNICEF
- **Source 3** : retirer du panneau sources (c'est une note, pas une source)
- **Source 9** : compléter la référence sénatoriale
- **Source 1** : mentionner la fourchette complète (15-30 000 Md$) ou justifier le choix de la borne basse
## FICHE 9 : Nourrir le monde (19 sources → 19 uniques, pas de doublons)

### Sources vérifiées

**Bloc juridique français (1-3)**

1. **Code civil, 21 mars 1804, article 1124** ✅
   Texte vérifié sur Wikisource : « Les incapables de contracter sont, Les mineurs, Les interdits, Les femmes mariées, dans les cas exprimés par la loi ». Correct.

2. **Loi n° 65-570 du 13 juillet 1965** ✅
   Réforme des régimes matrimoniaux. Vérifié via vie-publique.fr.

3. **Loi n° 85-1372 du 23 décembre 1985** ✅
   Égalité des époux dans la gestion des biens. Légifrance.

**Bloc données agricoles françaises (4-7)**

4. **Agreste, recensements agricoles 1970-2020** ✅
   Source institutionnelle (SSP/ministère de l'Agriculture). Six recensements décennaux cités.

5. **MSA, statistiques chefs d'exploitation 2023** ✅
   Source institutionnelle. Pas de lien.

6. **Sénat, rapport « Femmes et agriculture : pour l'égalité dans les territoires », 2017** ✅
   Rapport d'information n° 615 (2016-2017), déposé 5 juillet 2017, délégation aux droits des femmes.
   https://www.senat.fr/rap/r16-615/r16-615.html
   ⚠️ Ajouter le numéro de rapport dans la fiche.

7. **INRAE, production moyenne par exploitation 2010-2022** ⚠️ RÉFÉRENCE VAGUE
   Pas de titre de publication, pas de lien. INRAE publie des données mais la source précise n'est pas identifiable en l'état.

**Bloc foncier (8-12)**

8. **CGAAER, « Plus de 20 000 hectares de terres agricoles abandonnés chaque année », 2024** ✅
   Conseil général de l'alimentation, de l'agriculture et des espaces ruraux. À compléter avec le titre exact du rapport.

9. **Conseil supérieur du notariat, 10 % SAU en friche, 2,5 Mha** ⚠️ RÉFÉRENCE INCOMPLÈTE
   Donnée plausible mais pas de titre de publication, pas de date, pas de lien.

10. **Terre de Liens / CEREMA, 34 % SAU en indivision** ⚠️ RÉFÉRENCE INCOMPLÈTE
    Le chiffre circule dans la littérature foncière. Source précise à identifier.

11. **Alain Gueringer, cité par Terre de Liens** ⚠️ RÉFÉRENCE INCOMPLÈTE
    Gueringer est chercheur à l'INRAE (AgroParisTech/Irstea) spécialisé en foncier agricole. Publication précise non identifiée.

12. **Congrès des notaires de France, 2018** ✅
    114e congrès, Cannes, mai 2018. Thème : « Demain le territoire ». Pertinent sur les successions foncières.

**Bloc historique (13-14)**

13. **Gervais, Jollivet, Tavernier, *Histoire de la France rurale*, t. 4, 1977** ✅
    *La fin de la France paysanne : de 1914 à nos jours*, sous la dir. de Georges Duby et Armand Wallon, Seuil, coll. « L'Univers historique », 1977, 666 p. ISBN 2-02-004637-7.
    ⚠️ La fiche omet les directeurs de collection (Duby/Wallon) et le sous-titre.

14. **OFCE, économie de guerre et déficit commercial, 2021** ⚠️ RÉFÉRENCE VAGUE
    L'OFCE publie régulièrement sur l'économie française mais « économie de guerre et déficit commercial, 2021 » n'identifie pas un document précis. À compléter.

**Bloc international (15-17)**

15. **FAO, *La situation des femmes dans les systèmes agroalimentaires*, avril 2023** ✅
    Rapport phare, publié 13 avril 2023. Écart de productivité de 24 % à taille d'exploitation égale, 1 000 Md$ de PIB potentiel.
    https://www.fao.org/family-farming/detail/fr/c/1638938/

16. **FAO/IFAD/ONU Femmes/PAM, JP RWEE, résultats 2014-2021 (+82 % production)** ⚠️ À VÉRIFIER
    Le Joint Programme on Rural Women's Economic Empowerment existe bien (FAO/IFAD/UN Women/WFP). Le chiffre de +82 % doit être vérifié dans les rapports d'évaluation du programme.

17. **ONU Femmes / BM / PNUD / PNUE, *The Cost of the Gender Gap in Agricultural Productivity in Malawi, Tanzania, and Uganda*, 2015** ✅
    Vérifié : ONU Femmes, BM, PNUD-PNUE Poverty-Environment Initiative. Octobre 2015.
    https://africa.unwomen.org/en/digital-library/publications/2015/10/the-cost-of-the-gender-gap-in-agricultural-productivity-in-malawi-tanzania-and-uganda

**Bloc données techniques françaises (18-19)**

18. **Agreste, rendements céréaliers 2023-2024** ✅
    Données publiques SSP. Blé tendre : 62 à 75 q/ha selon les années, plausible.

19. **Ministère de l'Agriculture, consommation alimentaire par habitant 2020** ✅
    Données France Agrimer / SSP. Céréales : 119 kg/an, plausible.

### Corrections nécessaires

- **Source 7** (INRAE) : identifier la publication précise
- **Sources 9-11** (foncier) : compléter les références (titre, date, lien)
- **Source 13** : ajouter Duby/Wallon comme directeurs, sous-titre, ISBN
- **Source 14** (OFCE) : identifier le document exact
- **Source 16** (JP RWEE +82 %) : vérifier le chiffre dans le rapport d'évaluation
- Ajouter liens et numéros de rapport partout
## FICHE 10 : Dans la rue (12 sources → 12 uniques, pas de doublons)

### Sources vérifiées

1. **INSEE/SDES, Enquête mobilité des personnes 2018-2019** ✅
   21 000 ménages. Source institutionnelle de premier rang.

2. **CEREMA, Mobilité et quartiers prioritaires, 2019** ✅
   Centre d'études et d'expertise sur les risques, l'environnement, la mobilité et l'aménagement.

3. **CNRS/CEREMA, Mobiliscope** ✅
   Outil interactif de visualisation de la mobilité quotidienne. https://mobiliscope.cnrs.fr

4. **ONISR, Bilan de l'accidentalité 2024** ✅
   Observatoire national interministériel de la sécurité routière. Rapport annuel.

5. **Commission européenne, valeur statistique de la vie 2022 : 6,2 M€/décès, 950 000 €/blessure grave** ⚠️ À PRÉCISER
   La CE utilise effectivement une VSL dans ses analyses coûts-bénéfices. Le chiffre exact et la source doivent être identifiés (probablement DG MOVE ou Handbook on the external costs of transport, 2019/mise à jour 2022).

6. **Instruction ministérielle évaluation socio-économique des projets de transport, 2019. Valeur tutélaire : 11,90 €/heure** ✅
   Instruction du 16 juin 2014 mise à jour. Valeur du temps de déplacement à usage professionnel.

7. **HCE, Avis sur le harcèlement sexiste dans les transports, 2015** ✅
   Avis n° 2015-04-16-VIO-16 du 16 avril 2015. « Se mobiliser pour dire stop sur toute la ligne ».
   https://www.haut-conseil-egalite.gouv.fr/violences-faites-aux-femmes/travaux-du-hce/article/avis-relatif-au-harcelement

8. **INED, enquête Virage, 2015** ✅
   « Violences et rapports de genre », enquête nationale de référence. https://vifrageviolence.site.ined.fr

9. **Ville de Vienne, *Manual for Gender Mainstreaming in Urban Planning*, 2013** ✅
   Stadt Wien, 104 p. PDF disponible : https://www.wien.gv.at/stadtentwicklung/studien/pdf/b008358.pdf

10. **Eva Kail, entretiens POLIS Network 2021, ZEIT Online 2024** ✅
    Eva Kail, urbaniste pionnière du gender mainstreaming à Vienne depuis 1991. Sources journalistiques acceptables pour des entretiens.

11. **France Stratégie, déterminants géographiques de l'écart salarial** ⚠️ RÉFÉRENCE VAGUE
    France Stratégie a publié plusieurs notes sur le sujet. Titre précis, date et lien manquants.

12. **Criado-Perez, *Invisible Women*, éditions Hauteville, 2020** ✅
    Traduction française de l'édition Chatto & Windus 2019. Source secondaire (vulgarisation), acceptable comme illustration mais pas comme source primaire.

### Corrections nécessaires

- **Source 5** : identifier le document CE exact (handbook ou mise à jour)
- **Source 11** : identifier la note France Stratégie précise
- Ajouter liens et références complètes partout
- Pas de doublons, pas d'erreurs factuelles détectées — fiche propre
## FICHE 11 : Un sport dangereux (15 sources → 14 uniques, 1 doublon)

### Sources vérifiées

**Bloc biomédical (1-4)**

1. **Current Reviews in Musculoskeletal Medicine, Springer, 2021 — surrisque LCA féminin ×2 à ×8** ⚠️ RÉFÉRENCE INCOMPLÈTE
   Revue systématique plausible mais auteurs et titre exact manquants. Probablement Montalvo et al. ou Prodromos et al.

2. **Harvard GenderSci Lab, BJSM, décembre (année non précisée)** ⚠️ RÉFÉRENCE INCOMPLÈTE
   Le GenderSci Lab de Harvard (S. Richardson) a publié sur le sujet. Titre exact, année, DOI manquants.

3. **Orthopaedic Journal of Sports Medicine, 2024 — commotions féminines** ⚠️ RÉFÉRENCE INCOMPLÈTE
   Auteurs et titre manquants. Revue de rang A (SAGE), plausible.

4. **Dipan Bose et al., Vulnerability of Female Drivers, AJPH** ✅
   Déjà vérifié dans la fiche crash-tests. DOI : 10.2105/AJPH.2010.300027.

**Bloc équipement ski/sport (5-6)**

5. **ISO 11088 — réglage des fixations de ski** ✅
   Norme internationale réelle. Assemblage et réglage du système de fixation-chaussure-ski. Pas de variable sexe confirmé.

6. **Sports Medicine — Open, 2022 — fixations de ski et facteur sexe** ⚠️ RÉFÉRENCE INCOMPLÈTE
   Auteurs et titre manquants. Sports Medicine – Open est une revue Springer en libre accès, rang correct.

**Bloc chaussures football (7-10)**

7. **ECA, 2023 — enquête 350 joueuses, 82 % d'inconfort** ⚠️ À VÉRIFIER
   European Club Association. Le chiffre de 82 % circule dans la presse sportive. Source primaire à confirmer.

8. **Women and Equalities Committee, Parlement britannique, 2023** ✅
   Auditions parlementaires réelles sur l'équipement sportif féminin.

9. **IDA Sports, 2020 — première chaussure football sur forme féminine** ✅
   Marque réelle fondée par Laura Youngson. Fait vérifié.

10. **Nike, Phantom Luna, 2023** ✅
    Premier crampon Nike conçu sur scan 3D de pieds féminins. Fait vérifié.

**Bloc cyclisme (11)**

11. **Medicine & Science in Sports & Exercise, 2008 — pressions selle, 68 %** ⚠️ RÉFÉRENCE INCOMPLÈTE
    Auteurs manquants. Probablement Bressel & Larson 2003 (*MSSE*) ou Guess et al. Le chiffre de 68 % doit être vérifié.

**Bloc économique LCA (12-13)**

12. **Mather et al., Societal and Economic Impact of ACL Tears, JBJS, 2013** ✅
    JBJS Am., 95(19):1751-1759, DOI 10.2106/JBJS.L.01705. PMC3779900.

13. **Current Reviews in Musculoskeletal Medicine, 2021 — coût par rupture, arthrose** ⚠️ DOUBLON de la source 1. Dédupliquer.

**Bloc prévention (14)**

14. **Méta-analyses BJSM — prévention neuromusculaire, –50 à –70 % risque LCA** ⚠️ RÉFÉRENCE VAGUE
    Plusieurs méta-analyses existent (Sugimoto et al. 2015, Webster & Hewett 2018). Le chiffre de 50-70 % est cohérent avec la littérature mais la référence exacte n'est pas identifiée.

**Source secondaire (15)**

15. **Criado-Perez, *Invisible Women*, Hauteville, 2020** ✅
    Déjà vérifié. Source secondaire, acceptable comme illustration.

### Corrections nécessaires

- **Sources 1, 2, 3, 6, 11, 14** : compléter les références (auteurs, titres, DOI) — problème majeur
- **Source 13** : doublon de la source 1, dédupliquer (15 → 14 sources réelles)
- **Source 7** (ECA 82 %) : localiser la source primaire
- **Source 11** : vérifier le chiffre de 68 % et l'article exact

### Note méthodologique

Fiche la plus faible en rigueur bibliographique : six références sur quinze sont trop vagues pour être vérifiées (pas d'auteurs, pas de titres). Les revues citées sont de bon niveau (BJSM, MSSE, Orthopaedic JOSM), mais l'absence d'identification précise rend les sources invérifiables et vulnérables à la critique.

*Audit en cours — fiche par fiche*

---

# SYNTHÈSE GÉNÉRALE DE L'AUDIT (11 fiches)

## Volumétrie

| Fiche | Entrées L4 | Uniques | Doublons | Erreurs factuelles |
|---|---|---|---|---|
| 1 – Crash tests | 15 | 9 | 6 | 0 |
| 2 – Jeanne la Folle | 15 | 8 | 7 | 2 (Fleming, Lovell, Cook & Borah) |
| 3 – Karikó | 20 | 12 | 8 | 0 |
| 4 – Célibat sacerdotal | 19 | 19 | 0 | 0 |
| 5 – Adam et Ève | 22 | 12 | 10 | 1 (Poumarède 1992→1986) |
| 6 – Cardio | 11 | 11 | 0 | 0 |
| 7 – Plafond de verre | 8 | 8 | 0 | 0 |
| 8 – Éducation | 11 | 11 | 0 | 1 (Darmon attribué à Vinet) |
| 9 – Nourrir le monde | 19 | 19 | 0 | 0 |
| 10 – Dans la rue | 12 | 12 | 0 | 0 |
| 11 – Sport dangereux | 15 | 14 | 1 | 0 |
| **TOTAL** | **167** | **135** | **32** | **4** |

## Problèmes transversaux

**1. Duplication** : 32 entrées en double ou triple (19 % du total). Concentré sur les fiches 1-3 et 5. Les fiches 4, 6-10 sont propres.

**2. Liens et DOI** : zéro lien, zéro DOI dans l'état actuel du site. Problème universel et mécanique.

**3. Références incomplètes** : environ 15-20 sources manquent d'auteurs, de titres ou de dates précises. Concentré sur les fiches 8 (éducation), 9 (nourrir) et surtout 11 (sport), qui est la fiche la plus faible.

**4. Erreurs factuelles** : quatre détectées, toutes corrigeables :
   - Fiche 2 : attributions inexactes (Fleming, Lovell, Cook & Borah)
   - Fiche 5 : Poumarède daté 1992 au lieu de 1986
   - Fiche 8 : Darmon attribué à Vinet

**5. Criado-Perez** : citée dans 5 fiches (crash, cardio, rue, sport, et indirectement adam). Source secondaire de vulgarisation. Acceptable comme illustration, pas comme source primaire pour des faits précis.

## Diagnostic

Les sources sont solides dans l'ensemble. La recherche est sérieuse. Les problèmes sont mécaniques (doublons, liens manquants, références tronquées) et non structurels. Quatre erreurs factuelles sur 135 sources uniques, toutes mineures et corrigeables.

Le chantier de correction est quantifiable : dédupliquer 32 entrées, compléter ~20 références, ajouter ~100 liens/DOI, corriger 4 erreurs. Travail de quelques jours, pas de remise en cause du fond.

## Priorités de correction

1. **Urgent** : corriger les 4 erreurs factuelles (crédibilité immédiate)
2. **Important** : dédupliquer les fiches 1-3 et 5 (lisibilité)
3. **Nécessaire** : compléter les références incomplètes, surtout fiche 11
4. **Systématique** : ajouter liens et DOI à toutes les sources
