---
title: "Combining Multiple Coverage Criteria in Search-Based Unit Test Generation"
authors: "J. Miguel Rojas, J. Campos, M. Vivanti, G. Fraser, A. Arcuri"
conference: "Symposium on Search-Based Software Engineering (SSBSE), 2015"
publication: 2015-09-05
paper: /assets/pdfs/SSBSE2015-compositional-paper.pdf
slides: /assets/pdfs/SSBSE2015-compositional-slides.pdf
award: "Best Paper with industry-relevant SBSE results"
tags: [ASE, fault-localization, test generation, evosuite]
---

<!-- Excerpt -->
J. Miguel Rojas, J. Campos, M. Vivanti, G. Fraser, A. Arcuri  
Symposium on Search-Based Software Engineering (SSBSE), 2015


### Abstract

Automated test generation techniques typically aim at maximising coverage of well-established structural criteria such as statement or branch coverage. In practice, generating tests only for one specific criterion may not be sufficient when testing object oriented classes, as standard structural coverage criteria do not fully capture the properties developers may desire of their unit test suites. For example, covering a large number of statements could be easily achieved by just calling the main method of a class; yet, a good unit test suite would consist of smaller unit tests invoking individual methods, and checking return values and states with test assertions. There are several different properties that test suites should exhibit, and a search-based test generator could easily be extended with additional fitness functions to capture these properties. However, does search-based testing scale to combinations of multiple criteria, and what is the effect on the size and coverage of the resulting test suites? To answer these questions, we extended the EVOSUITE unit test generation tool to support combinations of multiple test criteria, defined and implemented several different criteria, and applied combinations of criteria to a sample of 650 open source Java classes. Our experiments suggest that optimising for several criteria at the same time is feasible without increasing computational costs: When combining nine different criteria, we observed an average decrease of only 0.4% for the constituent coverage criteria, while the test suites may grow up to 70%.

### Bibtex

```tex
@incollection{Rojas:SSBSE:2015,
  author = {Rojas, Jos{\'e} Miguel and Campos, Jos{\'e} and Vivanti,
  Mattia and Fraser, Gordon and Arcuri, Andrea},
  title = {Combining Multiple Coverage Criteria in Search-Based Unit
  Test Generation},
  booktitle = {Search-Based Software Engineering (SSBSE)},
  series = {Lecture Notes in Computer Science},
  year = {2015},
  isbn = {978-3-319-22182-3},
  volume = {9275},
  editor = {Barros, Márcio and Labiche, Yvan},
  doi = {10.1007/978-3-319-22183-0_7},
  url = {http://dx.doi.org/10.1007/978-3-319-22183-0_7},
  publisher = {Springer International Publishing},
  pages = {93-108},
}
```
