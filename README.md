# CHEMANE Platform

This page is related to the Wiki of the Cooperative Human sEMantic dAta maNagement & Exploitation (CHEMANE) platform. CHEMANE platform is composed of several modules ([MFS4UDB](https://forge.lias-lab.fr/projects/mfs4udb), [QaRS](https://forge.lias-lab.fr/projects/qars), [QaRS4UKB](https://forge.lias-lab.fr/projects/qars4ukb) and [TMA4KB](https://forge.lias-lab.fr/projects/tma4kb)). Each module supplies several algorithms developped by the members of LIAS Laboratory.

## Publications

### Journals

* Louise Parkin, Brice Chardin, Stéphane Jean, Allel Hadjali, Mickael Baron. A Cooperative Treatment of the Plethoric Answers Problem in RDF. Knowledge and Information Systems (KAIS), 2022, 64 (9), pp.2481-2514.

* Ibrahim Dellal, Stéphane Jean, Allel Hadjali, Brice Chardin, Mickael Baron. Query Answering over Uncertain RDF Knowledge Bases: Explain and Obviate Unsuccessful Query Results. Knowledge and Information Systems (KAIS), 2019, 61, pp.1633-1665.

* Chourouk BELHEOUANE, Stéphane JEAN, Hamid Azzoune, Allel HADJALI, Cooperative treatment of failing queries over uncertain databases: a matrix-computation-based approach, Journal of Intelligent Information Systems (JIIS), vol. 52, 2019, pp. 211--238

* Ibrahim Dellal, Stéphane Jean, Allel Hadjali, Brice Chardin, Mickael Baron. Traitement coopératif des requêtes RDF dans le contexte des bases de connaissances incertaines. Document numérique - Revue des sciences et technologies de l'information. Série Document numérique, 2018, 21 (1-2), pp.9--35. 

* Géraud Fokou, Stéphane Jean, Allel Hadjali, Mickael Baron. Handling Failing RDF Queries: From Diagnosis to Relaxation. Knowledge and Information Systems, 2016, 50, pp.167--195.

### Conferences

* Louise Parkin, Brice Chardin, Stéphane Jean, Allel Hadjali. Explaining Unexpected Answers of SPARQL Queries. Web Information Systems Engineering – WISE 2022, Nov 2022, Biarritz, France. pp.136-151

* Louise Parkin, Brice Chardin, Stéphane Jean, Allel Hadjali, Mickaël Baron. Dealing with Plethoric Answers of SPARQL Queries. Proceedings of the 32nd International Conference on Database and Expert Systems Applications, Sep 2021, Linz, Austria. pp.292-304,

* Louise Parkin, Ibrahim Dellal, Brice Chardin, Stéphane Jean, Allel Hadjali. Traitement coopératif du problème des réponses pléthoriques dans les bases de connaissances RDF. Proceedings of the BDA 2020 conference, Oct 2020, Paris, France. pp.24-25.

* Chourouk BELHEOUANE, Stéphane JEAN, Brice CHARDIN, Allel HADJALI, Hamid Azzoune, Borders of Theories for Cooperative Querying over Uncertain Databases, IEEE International Conference on Fuzzy Systems (FUZZ-IEEE 2018), 2018

* Ibrahim Dellal, Stéphane Jean, Allel Hadjali, Brice Chardin, Mickaël Baron. On Addressing the Empty Answer Problem in Uncertain Knowledge Bases. Proceedings of the 28th International Conference on Database and Expert Systems Applications, Aug 2017, Lyon, France. pp.120-129

* Chourouk BELHEOUANE, Stéphane JEAN, Allel HADJALI, Hamid Azzoune, Handling failing queries over uncertain databases, IEEE International Conference on Fuzzy Systems (FUZZ-IEEE 2017), 2017, pp. 1-6

* Ibrahim DELLAL, Stéphane JEAN, Allel HADJALI, Brice CHARDIN, Mickael BARON, On Addressing the Empty Answer Problem in Uncertain Knowledge Bases, Database and Expert Systems Applications (DEXA 2017), vol. 10438, LNCS, edited by Springer, 2017, pp. 120-129

* Géraud FOKOU, Stéphane JEAN, Allel HADJALI, Mickael BARON, RDF Query Relaxation Strategies Based on Failure Causes (Best Research Paper Award), 13th International Extented Semantic Web Conference, Heraklion, Greece (ESWC16), 2016, pp. 439-454

* Géraud FOKOU, Stéphane JEAN, Allel HADJALI, Mickael BARON, QaRS: A User-Friendly Graphical Tool for Semantic Query Design and Relaxation (Demo Paper) , 18th International Conference on Extending Database Technology, Brussels, Belgium (EDBT 2015), 2015, pp. 553-556

* Géraud FOKOU, Stéphane JEAN, Allel HADJALI, Mickael BARON, Cooperative Techniques for SPARQL Query Relaxation in RDF Databases, 12th Internationa Extended Semantic Web Conference, Portoroz, Slovenia (ESWC15), 2015, pp. 237-252

* Géraud FOKOU, Stéphane JEAN, Allel HADJALI, Endowing Semantic Query Languages with Advanced Relaxation Capabilities, 21st International Symposium on Methodologies for Intelligent Systems (ISMIS 2014), 2014

### Thesis

* Louise Parkin. Techniques coopératives pour l'exploitation des bases de connaissances et passage à l'échelle. Autre [cs.OH]. ISAE-ENSMA Ecole Nationale Supérieure de Mécanique et d'Aérotechique - Poitiers, 2022. Français.

* Ibrahim Dellal. Gestion et exploitation de larges bases de connaissances en présence de données incomplètes et incertaines. Autre [cs.OH]. ISAE-ENSMA Ecole Nationale Supérieure de Mécanique et d'Aérotechique - Poitiers, 2019. Français.

* Géraud Fokou. Conception d'un famework pour la relaxation des requêtes SPARQL. Autre [cs.OH]. ISAE-ENSMA Ecole Nationale Supérieure de Mécanique et d'Aérotechique - Poitiers, 2016. Français.

## CHEMANE ecosystem

Dedicated CHEMANE modules are following:

* [MFS4UDB](https://forge.lias-lab.fr/projects/mfs4udb): this module deals with the empty-answer problem in the uncertain relational database (SQL) context by proposing efficient approaches to find Minimal Failing Subqueries (MFSs) and maXimal Succeeding Subqueries (XSSs) of failing conjunctive queries.
* [QaRS](https://forge.lias-lab.fr/projects/qars): this module gives explanation for the failure of a SPARQL query and it performs relaxation of a SPARQL query in order to return top-k alternative answers.
* [QaRS4UKB](https://forge.lias-lab.fr/projects/qars4ukb): this module computes αMFSs and αXSSs of a failing RDF query for a given threshold α (αLBA algorithm) and it computes αMFSs and αXSSs of a failing RDF query for several thresholds (NLBA, Bottom-Up, Top-Down and Hybrid algorithm).
* [TMA4KB](https://forge.lias-lab.fr/projects/tma4kb): this modules provides four algorithms: *Base* algorithm executes all subqueries of a failing query, *BFS* algorithm does not execute queries that have a succeedign superquery, *Var* algorithm  BFS + uses a variable-based property to deduce query failure, *Card* algorithm Var + uses a cardinality-based property to deduce query failure.

## Historic Contributors (alphabetical order)

* [Mickael BARON](https://www.lias-lab.fr/members/mickaelbaron/)
* [Chourouk BELHEOUANE](https://www.lias-lab.fr/members/chouroukbelheouane/)
* [Brice CHARDIN](https://www.lias-lab.fr/members/bricechardin/)
* [Ibrahim DELLAL](https://www.lias-lab.fr/members/ibrahimdellal/)
* [Géraud FOKOU](https://www.lias-lab.fr/members/geraudfokou/)
* [Allel HADJ ALI](https://www.lias-lab.fr/members/allelhadjali/)
* [Stéphane JEAN](https://www.lias-lab.fr/members/stephanejean/)
* [Louise PARKIN](https://www.lias-lab.fr/members/louiseparkin/)
