---
page_type: data
description: Official WHO and CORD-19 data releases linked to MAG
---

# Official WHO COVID-19 and CORD-19 data releases linked to MAG

These files contain metadata to map Microsoft Academic Graph (MAG) paper entities to paper references collected for two different efforts:

* World Health Organization: [Global research on coronavirus disease (COVID-19)](https://www.who.int/emergencies/diseases/novel-coronavirus-2019/global-research-on-novel-coronavirus-2019-ncov)
* [COVID-19 Open Research Dataset (CORD-19)](https://pages.semanticscholar.org/coronavirus-research)

## Contents

File/folder | Description
--- | ---
`2020-03-23-WHO-MappedTo-2020-03-13-MicrosoftAcademicGraph.csv` | 2020-03-23 [WHO COVID-19 database](https://www.who.int/emergencies/diseases/novel-coronavirus-2019/global-research-on-novel-coronavirus-2019-ncov) linked to 2020-03-13 MAG
`2020-03-20-CORD-19-MappedTo-2020-03-13-MicrosoftAcademicGraph.csv` | 2020-03-20 [CORD-19 dataset](https://pages.semanticscholar.org/coronavirus-research) linked to 2020-03-13 MAG

## Linked WHO COVID-19 data schema

Column # | Name | Source | Description
--- | --- | --- | ---
1 | Title | WHO | Paper title
2 | Authors | WHO | List of paper author names
3 | Abstract | WHO | Paper abstract text
4 | Published Year | WHO | Paper publication year
5 | Published Month | WHO | Paper publication month
6 | Journal | WHO | Paper publication journal
7 | Volume | WHO | Paper publication journal volume
8 | Issue | WHO | Paper publication journal issue
9 | Pages | WHO | Paper publication journal pages
10 | Accession Number | WHO | Accession number
11 | DOI | WHO | Paper Digital Object Identifier (DOI)
12 | Ref | WHO | Reference number
13 | Covidence # | WHO | Unique paper ID associated with WHO COVID-19 data set
14 | Study | WHO | Study name
15 | Notes | WHO | WHO specific notes for the paper
16 | Tags | WHO | WHO specific tags for the paper
17 | MagScore | MAG | Score that reflects the accuracy of the mapping based on how much of the paper metadata could be linked to MAG
18 | MagMappedLabels | MAG | String used for mapping the paper metadata to MAG paper entity with embedded XML labels indicating what terms were mapped to what fields, and the confidence of that mapping
19 | MagPaperId | MAG | MAG paper entity ID supplied by Microsoft
20 | MagDoi | MAG | MAG paper entity DOI
21 | MagPaperFamilyId | MAG | MAG paper entity family ID
22 | MagPubmedId | MAG | MAG paper entity pubmed ID

## Linked CORD-19 data schema

Column # | Name | Source | Description
--- | --- | --- | ---
1 | sha | CORD-19 | 40-character sha1 of the PDF
2 | source_x | CORD-19 | Paper source
3 | title | CORD-19 | Paper title
4 | doi | CORD-19 | Paper Digital Object Identifier (DOI)
5 | pmcid | CORD-19 | PubMed Central reference number (PMCID)
6 | pubmed_id | CORD-19 | PubMed reference number (PMID)
7 | license | CORD-19 | Fulltext licensing (see [CORD-19 site](https://pages.semanticscholar.org/coronavirus-research))
8 | abstract | CORD-19 | Paper abstract text
9 | publish_time | CORD-19 | Paper publication date
10 | authors | CORD-19 | List of paper author names
11 | journal | CORD-19 | Paper publication journal
12 | Microsoft Academic Paper ID | CORD-19 | MAG paper entity ID supplied by CORD-19
13 | WHO #Covidence | CORD-19 | Unique paper ID associated with WHO COVID-19 data set
14 | has_full_text | CORD-19 | Indicates if paper has full text in CORD-19 data set
15 | full_text_file | CORD-19 | Indicates licensing terms of full text in CORD-19 data set
16 | MagMappingScore | MAG | Score that reflects the accuracy of the mapping based on how much of the paper metadata could be linked to MAG
17 | MagPaperId | MAG | MAG paper entity ID supplied by Microsoft
18 | MagPaperFamilyId | MAG | MAG paper entity family ID
19 | MagDoi | MAG | MAG paper entity DOI
20 | MagPubMedId | MAG | MAG paper entity pubmed ID
21 | MagMappedLabels | MAG | String used for mapping the paper metadata to MAG paper entity with embedded XML labels indicating what terms were mapped to what fields, and the confidence of that mapping

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.