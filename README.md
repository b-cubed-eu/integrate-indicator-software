<!-- badges: start -->
![GitHub](https://img.shields.io/github/license/b-cubed-eu/integrate-indicator-software)
[![repo status](https://www.repostatus.org/badges/latest/wip.svg)](https://www.repostatus.org/#wip)
![GitHub repo size](https://img.shields.io/github/repo-size/b-cubed-eu/integrate-indicator-software)
<!-- badges: end -->

# Integrate and streamline indicator software

[Langeraert, Ward![ORCID logo](https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png)](https://orcid.org/0000-0002-5900-8109)[^aut][^cre][^INBO]
[Van Daele, Toon![ORCID logo](https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png)](https://orcid.org/0000-0002-1362-853X)[^aut][^INBO]
Research Institute for Nature and Forest (INBO)[^cph]
European Union's Horizon Europe Research and Innovation Programme (ID No 101059592)[^fnd]

[^cph]: copyright holder
[^fnd]: funder
[^aut]: author
[^cre]: contact person
[^INBO]: Research Institute for Nature and Forest (INBO), Herman Teirlinckgebouw, Havenlaan 88 PO Box 73, B-1000 Brussels, Belgium

**keywords**: R packages; software integration; software streamlining; biodiversity indicators; data cubes

<!-- community: b3 -->

### Description

<!-- description: start -->
Scripts to explore the streamlining and integration of software (with focus on R packages) related to the calculation of indicators based on biodiversity data cubes.
<!-- description: end -->

This code is developed in context of **T5.5** of the [B-Cubed project](https://b-cubed.eu/).

### Repo structure

```
├── source                         ├ R markdown files
│   └── scripts                    ├ R scripts
├── data
│   ├── raw                        ├ store raw data
│   ├── intermediate               ├ store intermediate data
│   └── processed                  ├ store processed data
├── checklist.yml                  ├ options checklist package (https://github.com/inbo/checklist)
├── organisation.yml               ├ organisation info (https://inbo.github.io/checklist/articles/organisation.html)
├── inst
│   └── en_gb.dic                  ├ dictionary with words that should not be checked by the checklist package
├── .github                        │ 
│   ├── workflows                  │ 
│   │   └── checklist_project.yml  ├ GitHub repo settings
│   ├── CODE_OF_CONDUCT.md         │ 
│   └── CONTRIBUTING.md            │
├── indicator-uncertainty.Rproj    ├ R project
├── README.md                      ├ project description
├── LICENSE.md                     ├ licence
├── LICENSE                        │
├── CITATION.cff                   ├ citation info
├── .zenodo.json                   ├ zenodo metadata
└── .gitignore                     ├ files to ignore
```
