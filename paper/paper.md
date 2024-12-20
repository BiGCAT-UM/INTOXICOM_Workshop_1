---
title: 'INTOXICOM Workshop Report: FAIRification of Toxicological Research Output: Leveraging ELIXIR Resources'
title_short: 'INTOXICOM #1: FAIRification of Toxicological Research Output'
tags:
  - toxicology
  - ELIXIR Europe
  - FAIR
authors:
  - name: Marvin Martens
    orcid: 0000-0003-2230-0840
    affiliation: 1
  - name: Iseult Lynch
    orcid: 0000-0003-4250-4584
    affiliation: 2
  - name: Thomas Exner
    orcid: 0000-0002-1849-5246
    affiliation: 3
  - name: Rob Stierum
    orcid: 0000-0002-4409-1974
    affiliation: 4
  - name: Penny&nbsp;Nymark
    orcid: 0000-0002-3435-7775
    affiliation: 5
  - name: Dominik Martinát
    orcid: 0000-0001-6611-7883
    affiliation: 6
  - name: Javier Millán Acosta
    orcid: 0000-0002-4166-7093
    affiliation: 1
  - name: Ulrike&nbsp;Wittig
    orcid: 0000-0002-9077-5664
    affiliation: 7
  - name: Clemens Wittwehr
    orcid: 0000-0003-2760-7702
    affiliation: 8
  - name: Meike Bünger
    orcid: 0009-0002-7664-0058
    affiliation: 9
  - name: Gerhard&nbsp;Burger
    orcid: 0000-0003-1062-5576
    affiliation: 10
  - name: Tooba&nbsp;Abbassi-Daloii
    orcid: 0000-0002-4904-3269
    affiliation: 1
  - name: Uday Killi
    orcid: 0000-0001-6267-7541
    affiliation: 11, 12
  - name: Jente&nbsp;Houweling
    orcid: 0009-0005-3680-0645
    affiliation: 1, 13
  - name: Riju&nbsp;Roy&nbsp;Chowdhury
    orcid: 0009-0002-4110-241X
    affiliation: 14
  - name: Tamara&nbsp;Danilyuk
    orcid: 0000-0001-6125-6147
    affiliation: 10
  - name: Lucy&nbsp;Sinke
    orcid: 0000-0002-9209-1266
    affiliation: 10 
  - name: Ozan&nbsp;Cinar
    orcid: 0000-0003-0329-1977 
    affiliation: 1
  - name: Egon&nbsp;Willighagen
    orcid: 0000-0001-7542-0286
    affiliation: 1
affiliations:
  - name: Dept of Translational Genomics, NUTRIM, FHML, Maastricht University, Maastricht, NL
    index: 1
  - name: University of Birmingham, Birmingham, UK
    index: 2
  - name: Seven Past Nine GmbH, Schopfheim, DE
    index: 3
  - name: The&nbsp;Netherlands&nbsp;Organisation for Applied Scientific Research. Risk Analysis for Prevention, Innovation & Development, Utrecht, NL
    index: 4
  - name: Institute of Environmental Medicine, Karolinska Institutet, Stockholm, SE
    index: 5
  - name: Department of Physical Chemistry, Palacký University Olomouc, CZ
    index: 6
  - name: Heidelberg Institute for Theoretical Studies, Heidelberg, DE
    index: 7
  - name: European Commission, Joint Research Centre (JRC), Ispra, IT
    index: 8
  - name: Stichting Health-RI, Utrecht, NL
    index: 9
  - name: Leiden Academic Centre for Drug Research (LACDR), Leiden University, Leiden, NL
    index: 10
  - name: University of Eastern Finland, FI
    index: 11
  - name: University of South Bohemia, CZ
    index: 12
  - name: RIVM, Bilthoven, NL
    index: 13
  - name: IUF – Leibniz Research Institute for Environmental Medicine, Düsseldorf, DE
    index: 14
date: 29 May 2024
cito-bibliography: paper.bib
event: INTOXICOM
biohackathon_name: "INTOXICOM Workshops"
biohackathon_url:   "https://elixir-europe.org/internal-projects/commissioned-services/integrating-toxicology-community"
biohackathon_location: "Utrecht, 28-29 May 2024"
group: Workshop 1
git_url: https://github.com/BiGCAT-UM/INTOXICOM_Workshop_1
authors_short: Martens \emph{et al.}
---

<!--

RS GENERAL REMARK: ADD SOME ILLUSTRATIONS? E.G. ON THE OUTCOME OF THE FAIR COOK BOOK, ON THE TOXICOLOGY REPOSITORY UNDER FAIRSHARING.ORG ?? ETC.

-->

# Introduction

This report documents the first workshop of the ELIXIR
Toxicology Community [@citesAsRecommendedReading:Martens2023ELIXIR], held in Utrecht on May 28-29, 2024 [@citesAsEvidence:Aanmelder], as part of the INTOXICOM Implementation Study workshop series [@citesAsEvidence:INTOXICOM]. The main topic of
the meeting was the FAIRification of toxicological research outputs and exploring the potential role of ELIXIR resources in this process. A team of ten people from the ELIXIR Toxicology Community, including Marvin Martens, Penny Nymark,
Iseult Lynch, Meike Bünger, Rob Stierum, Thomas Exner, Egon Willighagen, Ammar Ammar,
Dominik Martinát, and Karel Berka, coordinated the event. 

The target audience of this first INTOXICOM
workshop was toxicologists interested in implementing FAIR data practices in their
research or making their datasets more FAIR, as well as data managers, data stewards,
and researchers working with adverse outcome pathways (AOPs). 

The agenda comprised presentations and interactive sessions to apply FAIR solutions specifically within toxicology research. The workshop was divided into two main parts. The first part focused on the application of FAIR solutions to toxicology databases
and datasets. This included discussions on using compact identifiers to reference specific records in databases in narratives such as project deliverables, e.g.
in the European Partnership for the Assessment of Risks from Chemicals (PARC, [eu-parc.eu](https://eu-parc.eu)) [@citesForInformation:PARC].

The second part addressed the FAIRification of AOPs in the AOP-Wiki, aiming to improve their findability and accessibility. Continuing on the efforts of the Modelling the Pathogenesis of COVID-19 Using the Adverse Output Pathway Framework (CIAO) project
(ciao-covid.net), that assessed the FAIRness of
AOPs [@citesForInformation:Carusi2023], the workshop aimed to create a FAIR Implementation Profile for AOPs.

Key deliverables for the workshop include: 
1. this report
2. A FAIR Implementation Profile (FIP) for AOPs
3. A proposed standard on how to use compact identifiers on project reports.

This report describes the outcomes of the workshop, provides links to presentations (when applicable), and discusses the initial hands-on results that emerged from collaborative sessions.

# The workshop

The workshop welcomed 16 in-person participants and several online contributors, with two presenters and three additional attendees joining remotely. 
The participants represented a diverse set of organisations, including universities (Karolinska Institutet, Leiden University,
Maastricht University, Palacký University Olomouc, University of Eastern Finland, and University of Birmingham), as well as research institutes (TNO, EU-JRC, RIVM). Additionally, representatives from regulatory bodies and various ELIXIR Platforms participated.
Furthermore, in preparation to the workshop to set the stage, multiple ongoing toxicology research projects and initiatives were contacted to identify data-related challenges, and these were also represented at the workshop. These included VHP4Safety
([vhp4safety.nl](https://vhp4safety.nl)) [@VHP4Safety2024],
PARC, RISK-HUNT3R ([risk-hunt3r.eu](https://risk-hunt3r.eu)), NanoSafetyCluster ([nanosafetycluster.eu](https://nanosafetycluster.eu)),
HARMLESS ([harmless-project.eu](https://harmless-project.eu)), SbD4Nano
([sbd4nano.eu](https://sbd4nano.eu)), PINK ([pink-project.eu](https://pink-project.eu)),
and SysBioToP-Moving.
This mix of projects contributed to the focus of the workshop by bringing in ongoing data challenges and solutions, helping to guide discussions on FAIRification in toxicology.

Geographically, the workshop represented expertise from across Europe, with attendees from The Netherlands, Finland, Italy, the UK, Germany, Czechia, and Sweden. This broad representation underscored the European interest in FAIRification in toxicological research and highlighted the collaborative approach of the INTOXICOM workshop series.

## Presentations

The workshop contained a series of presentations to introduce ELIXIR, the ELIXIR Toxicology Community, the scope of the workshop, and the specific workshop sessions designed to address FAIRification in toxicology. Table 1 gives an overview of the presentations.

Table1 : Presentations at the workshop.

| Speaker | Talk Title  |
| --- | -------- |
| David Lloyd | ELIXIR Introduction |
| Marvin Martens | ELIXIR Toxicology Community [@martens_2024_14005367] |
| Iseult Lynch | FAIR data to support Chemical Risk Assessment & Regulation – the PARC approach for toxicological data [@Lynch2024] |
| Rob Stierum | Compact IDs - identified challenges |
| Egon Willighagen | Introduction to hands-on session data FAIRification [@Willighagen_2024] |
| Penny Nymark | What is an Adverse Outcome Pathway? [@Nymark_2024] |
| Clemens Wittwehr | Why Adverse Outcome Pathways need to be FAIR [@Wittwehr2024] |
| Marvin Martens | FAIR AOPs - identified challenges [@martens_2024_14005454] |
| Ulrike Wittig | ELIXIR Data Platform |
| Marvin Martens | FAIRsharing Toxicology Collection [@martens_2024_14005493] |
| Iseult Lynch | Welcome to FIP.27.W.1 [@Lynch2024b] |
| Penny Nymark | Data vs. metadata in an Adverse Outcome Pathway |

The introductory presentations addressed the structure of ELIXIR and the ELIXIR Toxicology community, setting the stage of the workshop. To zoom in on the possible exploration of ELIXIR resources/tools/platforms as to the usefulness towards the toxicology research community, the first topic was the general FAIRification of research
output (a guiding definition is found in [@citesForInformation:Houweling2023]).
A main aspect of this part of the workshop was about making data FAIR, considering the ambitions, and identifying practical challenges,
as well as tools that are provided by ELIXIR to tackle these challenges such as RDMkit, FAIR Cookbook, Data Management Plan Wizard.
The main outcome of this session was a workshop
discussion that guided the creation of document on using compact identifiers to make project reports more interoperable.

This part was followed by an interactive, hands-on session around FAIRification recipes in
the ELIXIR FAIR Cookbook [@RoccaSerra2023]. The selection of data challenges and topics for this session was selected based upon topics identified from the research projects and communities mentioned above, as well as during the preparatory webinar.

The third and last topic of the first day was a session on the FAIRification of AOPs, expanding on earlier work by the CIAO project ([ciao-covid.net](https://www.ciao-covid.net)). Similar to the identified data challenges, the discussion during this session was also based on data challenges around the use and development of AOPs, identified by research projects and communities. This session fed directly into the continued development of the AOP-Wiki, highlighting efforts to make AOPs more findable and interoperable.

The second day started with a session on the ELIXIR Data Platform and the
FAIRsharing Toxicology Collection. This collection is an ongoing collaboration
between the ELIXIR Toxicology Community and the FAIRsharing project, recently
boosted by a FAIRsharing Community Champion project. An interactive questionnaire was used to gather information on the profiles of attendees, the types of data they typically seek, and the databases they commonly use. This allowed for insights into the specific resources and data sources valued by the toxicology community, which led to discussions, helped identify gaps in existing databases and opportunities for the ELIXIR Data Platform and FAIRsharing Toxicology Collection to better support toxicology researchers.  

The main focus of the second day was a hands-on session on developing FAIR Implementation Profiles (FIPs). The FIP is a socio-technical approach to drive FAIR convergence by encouraging communities to publicly declare the FAIR Enabling Resources (FERs) [@fer_def] they use to implement the FAIR principles.
Comparison of FIPs between communities can guide members of those communities to widely used FERs thereby avoiding duplicated efforts and improving interoperability [@Schultes2020].
A good way to start with FIPs is using the FIP mini questionnaire [@fip_mini], because it allows a quick(er) inventory of resources without having to formally describe those resources as FERs.
The formal way to create a FIP is with the FIP wizard ([fip-wizard.ds-wizard.org](https://fip-wizard.ds-wizard.org/)), a DSWizard-based tool was introduced
to the participants has been used by the WorldFAIR
project for ready-for-modelling datasets for nanoinformatics [@citesForInformation:WFFIP1] and
for datasets [@citesForInformation:WFFIP2; @Magagna2022].

# Results

This section gives an overview of the main outcomes of the sessions of this
workshop.

## Guidance for compact identifier use

One of the goals of the workshop was to promote the use of compact identifiers
in project reporting. Compact identifiers are short but meaningful references
to identifiers for entities like proteins, genes, metabolites, and nanomaterials.
A draft guidance document has been under development and is available at
[github.com/egonw/compact-ids-in-reports](https://github.com/egonw/compact-ids-in-reports).

## FAIR standards and challenges

With regards to FAIR standards and associated challenges, the participants discussed various aspects
on how to make research output more reused. While ELIXIR
already provides many solutions for FAIR, adoption in projects and communities
is not trivial. PARC is adopting various solutions, including FIPs and FAIR
Data Points (FDPs) [@citesAsRecommendedReading:Silva2022FAIR]. Community
standards like IUCLID6 and the Toxic Process Ontology (TXPO) were mentioned. <!-- [RS: THAT IS CORRECT, HOWEVER THESE ARE THEMSELVES NO FAIR STANDARDS YET AND AS SUCH ARE NO IMMEDIATE SOLUTIONS FOR FAIRIFICATION (OR ARE THEY?), IN THE END THESE RESOURCES MAY CONTRIBUTE TO FAIRNESS, AS IUCLID6 DEMANDS A STRUCTURED RECORING OF (META)DATA ACCORDING TO OECD HARMONZIED TEMPLATES) AND ONTOLOGIES ARE ALWAYS HELPFULL....] -->
Other toxicology projects adopted solutions including repositories like the
EMBL-EBI BioStudies, OpenAIRE, and Zenodo. <!-- [RS: IS IT POSSIBLE TO BE MORE SPECIFIC WHICH TOX PROJECTS HAVE ADOPTED WHICH TOOLS?] --> The role of global unique identifiers
was raised, including the Nano-InChI [@citesAsPotentialSolution:Lynch2020] and the European Registry of Materials
(ERM) identifier [@citesAsPotentialSolution:VanRijn2022] as metadata for datasets to unequivocally indicate which chemicals are
studied within these toxicology projects.

Challenges that the toxicology community faces include (1) incomplete interoperability,
(2) lack of adoption of unique identifiers, and (3) data that cannot be reused because
it does not meet community standards. The term "re-usefulness" of the data was brought up by Iseult Lynch. 

<!-- 
[RS NOT CLEAR HOW THE TEXT ABOVE RELATES TO BELOW. ABOVE YOU MENTION 3 CHALLENGES (1) INCOMPLETE INTEROPERABILITY; (2) LACK OF ADOPTION OF UNIQUE IDENTIFIERS; (2) DATA NOT MEETING COMMUNITY STANDARDS. BELOW YOU MENTION AGAIN 3 DATA CHALLENGES, FOR WHICH THE FIRST TWO ARE THE SAME AS ABOVE, I UNDERSTAND THIS. HOWEVER, THE THIRD CHALLENGE MENTIONED BELOW IS ABOUT ONTOLOGIES WHICH IS NOT NECESSARILY THE SAME AS MEETING COMMUNITY STANDARDS, OR IS THIS WHAT YOU MEAN: E.G. IUCLID IS AN ECHA STANDARD BUT NOT AN ONTOLOGY PER SE, CAN YOU CLARIFY?] 
-->

Below, three specific identified challenges, for which follow up is to be relevant for the toxicology community, are explained in more detail.


The first is the fact if the BioStudies web interface <!-- [RS THIS IS A VERY SPECIFIC CHALLENGE SPECIFICALLY FOR AN ELIXIR INFRASTRUCTURE COMPONENT, WHICH FITS THE WORKSHOP IDEA. IT FALLS UNDER THE MORE GENERIC CHALLENGE OF "INCOMPLETE INTEROPERABILITY" BUT SOMEHWERE WE NEED TO MENTION THE TRANSITION IN THE TEXT FROM THE  OBSERVATION THAT INTEROPERABILITY IS AN ISSUE IN GENERAL, TO THIS SPECIFIC ELIXIR EXAMPLE. OR AM I WRONG AND WAS THIS (BIOSTUDIES) IN FACT THE VERY SPECIFIC DATA CHALLENGE IDENTIFIED FROM ONE OF THE TOXICOLOGY PROJECTS?] --> 
is sufficiently interoperable. Although the website allows to work with plain text (e.g. to enable the querying of the biostudies within the "Search BioStudies" field), it does not provide an
easy (machine) interface for annotation with identifiers and ontologies. <!-- [RS POST MEETING REMARK: IF I LOOK AT https://www.ebi.ac.uk/biostudies/help#, THERE ARE SOME OPTIONS TO QUERY THE DATA IN MORE DETAIL USING AN API] -->


The second challenge specifically listed is the adoption of identifiers in
toxicology datasets. Better metadata of datasets with supporting unique identifiers is
essential. It could be solved with compact identifiers in descriptions or
identifiers as keywords. The NanoCommons community made progress with
this ([nanocommons.github.io/datasets/](https://nanocommons.github.io/datasets/)),
but annotating the data still needs to be done manually.

Regarding the community standards, reasons why data cannot be reused include
scientific aspect as lack of community-accepted standards for testing, which
should address experimental artifacts like batch effects and interlaboratory
effects.

The third challenge is the general incompleteness of ontologies. <!-- [RS: OR IS IT A BIT WIDER COMPARED TO ONTOLOGIES ONLY, THAT IS "DATA NOT MEETING COMMUNITY STANDARDS?" SEE ALSO MY REMARK ABOVE] -->
Finding ontology
terms to be used for annotation of research output is non-trivial while the
translation of ontology terms to identifiers is key to data consistency and 
interoperability. As examples of this challenge, some challenges around ontological annotation of
biological assays and composite nanomaterials were discussed. 

The discussion also covered the trade off between comprehensive ontological modeling, which allows reasoning to infer new links in data and achieve a more complete knowledge representation, and the complexity that setting up an ontology (or deciding on which ontologies to use) can introduce for certain projects. In many application-specific or short-term research efforts, representing knowledge in an ontology format can add unnecessary hurdles for researchers as opposed to simpler solutions like taxonomies or controlled vocabularies, especially if the reasoning capabilities of OWL ontologies can't be fully utilized within the project's scope and timeline. 

This problem statement led to a recap of some instances of spreadsheet template-based workflows for ontology reuse and expansion within past and present projects in the INTOXICOM environment<!-- PARC iirc -->. Leveraging tools like the OBO foundry's ontology toolkit, ROBOT [@citesAsRecommendedReading:Jackson_2019], allows for workflows that use adaptable templates to accommodate new data needs while building upon and remaining compatible with established ontologies. These workflows, with their emphasis on iterative refinement and community involvement, can help include technical and non-technical researchers, leading to more applicable ontologies and allowing ontology developers to focus on the technical aspects of ontology engineering and development.

<!-- based on my (Javier) understanding of Thomas's point about ontologies and what I can remember from our conversation-->For ontologies to become the cornerstone of FAIR metadata, there is a need to align perspectives between database-oriented thinking, which favors simpler relational models; metadata producers, who may find a lack of granularity in available terms if the ontology is too high-level; and ontology engineers, who must strike a balance between the precision of their logical models and their practical usability for metadata producers and consumers.


## FAIRification recipes

Following an introduction to the FAIR Cookbook concepts, the workshop participants collaborated to develop three new FAIRification recipes: "Adding KE Component annotations in AOP-Wiki", "Metadata for cell-based assays using BAO", and "Setting up imaging based confocal screening". These recipe drafts are designed to support the toxicology community in implementing FAIR principles in specific data contexts.

<!-- [RS CAN THE OWNERS OF THE RECEPIES PERHAPS PROVIDE SOME MORE DETAILS HERE, WITH SUGGESTION: TOGETHER WITH A REFLECTION ON HOW EASY IT WAS TO ADOPT THE FAIR COOKBOOK PRINCIPLE IN THEIR WORK?] -->

<!-- EW: one is currently private and could maybe be made public. Second, we need
         Tooba and the rest of the FAIR Cookbook team to help the authors move
         forward. 
     TAD: I would be happy to help and onboard other people from the FAIR cookbook side    -->

### Adding KE Component annotations in AOP-Wiki

One group, consisting of Clemens Wittwehr, Penny Nymark, Thomas Exner, and Marvin Martens, drafted an initial version of a recipe intended to guide AOP developers in annotating Key Event (KE) Components [@Ives2017] in line with the guidelines outlined on p.&nbsp;28 of [@OECD2018],
under "KE Components and Biological Context"
([hackmd.io/\@WBu-yMi5R62T6i7YA3RGVA/BJtnqIQVR](https://hackmd.io/\@WBu-yMi5R62T6i7YA3RGVA/BJtnqIQVR)).
This recipe provides step-by-step instructions on choosing appropriate ontology terms to improve KE Component annotation. Current experience indicates that AOP developers often found the process of KE annotation to be complex, which causes the lack of utilisation. This new recipe aims to streamline the process, making it easier to select and apply ontology terms. Proper KE Component annotation enhances AOP discoverability, and broader use of ontologies in AOP-Wiki could support the semi-automated generation of AOP networks and help identify redundant or overlapping KEs. 

The next steps include integrating the "Adding KE Compoonent Annotations in AOP-Wiki" recipe into the FAIR Cookbook, with plans to reference it in the AOP-Wiki's guidance. Further support from the FAIR Cookbook team will facilitate the adoption and refinement of these recipes, promoting their utility across the toxicology community.

### Metadata for cell-based assays

This recipe, though still a draft, provides a starting point for the consistent and FAIR-compliant metadata annotation of cell-based bioassay types ([hackmd.io/\@lusinke/rkXlvLXE0](https://hackmd.io/\@lusinke/rkXlvLXE0)). The starting point is a review of biomedical ontologies and controlled vocabularies and the metadata fields they cover, from the biological aspects of assay samples to assay specifications and analysis-level metadata. The different metadata fields to be annotated with these semantic resources are then divided into required and recommended depending on whether they occur at least in two of the metadata standards enumerated in the recipe.

### Setting up imaging based confocal screening

The third recipe is about standardized protocols for reproducible imaging of eGFP-tagged hiPSC reporter lines
([hackmd.io/MBKglLL3Ri6uiodo46VbJg?both](https://hackmd.io/MBKglLL3Ri6uiodo46VbJg?both)).
This recipe outlines the essential components required to create a **minimal imaging dataset** that enables
validation of functional reproducibility of fluorescent eGFP hiPSC reporter lines using confocal imaging
**across collaborative project partners**. It covers nine points, including a reference compound
set, metadata, imaging settings, raw data deposition, quality control, and more.

## FAIR Implementation Profiles

For the FAIR Implementation Profiles (FIPs), we first looked at the FIP mini questionnaire. During the workshop [@RAa-SA1rYr], two FIPs were
started: The first FIP was developed for AOPs and the second FIP was developed for 
toxicogenomics. Generally, filling out the FIP template was not found to be easy
and both FIPs left a lot of questions unanswered. The in-progress FIPs can be accessed at [@citesAsEvidence:Lynch2024c], to be picked up at a later point in time. As part of this FIP Introduction event, also the FIP wizard ([fip-wizard.ds-wizard.org](https://fip-wizard.ds-wizard.org/)) was briefly demonstrated, as it gives more context to the different FAIR principles and their corresponding FERs.

### Adverse Outcome Pathways FIP

The AOP FIP is based on the work done by AOP-Wiki [@AOPFIP]. For example, metadata used
by the AOP-Wiki include an identifier, a title, a contact point, and a license.
For the interoperability, ontologies like PROV-O [@Sahoo2013], Cell Ontology [@Diehl2016],
and UBERON ([obophenotype.github.io/uberon/](https://obophenotype.github.io/uberon/)) were discussed.

### Toxicogenomics FIP

The toxicogenomics FIP derived from experience from the participants. Some projects
have previously already used resources like BioStudies [@Sarkans2018], ArrayExpress, and 
the European Nucleotide Archive [@Burgin2023] and matching identifier like
the BioStudies Accession number, DOI, and ORCID. ISA-Tab [@RoccaSerra2009] is mentioned as
format, along with the more general CSV, TSV, and JSON. Datasets have already been
indexed by Google Dataset Search (although it is unclear if this is functional) and Wikidata. 
Ontologies that were mentioned include the Chemical Entities of Biological Interest [@deMatos2010], Gene Ontology, and Experimental Factor Ontology (EFO) [@Malone2010].

### FIP reflection

It is to be expected that when developing a FIP a lot of questions remain open initially. These are typically the more technically/legal oriented questions, especially for the A and R principles, that require more specialized knowledge. In case of the toxicogenomics FIP also other fields (e.g. metadata schema, structured vocabularies, provenance model) stayed relatively empty, this might be for example because templates are not well-defined, or structured vocabularies are not widely used, which in itself is also good to learn (but of course indicates a need to develop those resources). 

It is also helpful to clearly set the scope for the FIP, as it is possible to create a FIP for a community (e.g. the toxicogenomics community), but it's also possible to create a FIP for a resource itself (e.g., the AOP-Wiki, or BioStudies). A limited scope might be easier to get started with (provided you have the resource experts present), and is a great way to assess the FAIRness of that resource!

Finally, it should be noted that creating a FIP typically takes multiple sessions, as resources need to be identified and FERs need to be created, before a machine-readable FIP can be published. However, getting people to think about these choices is already a beneficial result of starting a FIP, even if the FIP is not (yet) finished.


<!--
  https://docs.google.com/spreadsheets/d/1Bc7sCERl7FIJxm8wp7wz3vzZdnNaf-6N_8pn_xFMQyM/edit?usp=drive_link
  
    -> moved to https://docs.google.com/spreadsheets/d/1nNxdR8cWhcQq-9xWnA1QRo9gWcTxqz8W/edit?gid=1113123974#gid=1113123974
  
  https://docs.google.com/spreadsheets/d/1yNEYzJRbx10RkuqJmLcO7RPOq-nrimUKQLQW6uWzfho/edit?usp=sharing
--> 

<!-- [RS: SOME ADDITIONAL TEXT NEEDED INCLUDING USER EXPERIENCES HOW TO USE THE CONCEPT OF ESTABLISHING A FIP] -->

# Discussion

The workshop had a stimulating discussion and resulted in new output that feeds
back into the ELIXIR Toxicology Community (e.g. via this report) and via the
two FIPs, three FAIR Cookbook recipes, and other outcomes back into the wider ELIXIR
and toxicology communities. Both the recipes and the cookbook need further work,
and, more importantly, adoption by toxicologists.
Of course, the workshop was relatively short to complete output as intended,
which is reflected in the nature of the cited results, and for the FIPs
there are not even tangible results that can be linked to, at the time of writing.

This limitation was anticipated and results will be picked up by the participants and
followed up in the second INTOXICOM workshop. This report will allow follow up
work to acknowledge the input from this workshop by citing this paper.

<!-- 

[RS SOME THOUGHTS FOR DISCUSSION, WITH THE NOTITION THAT IT HAS BEEN SOME TIME SINCE THE WORKSHOP AND MY MEMORY IS FADING HERE. 

DIFFICULT TO BALANCE BETWEEN DETAILED (META)DATA ANNOTATION OF STUDIES VERSUS PRACTICAL FEASABILITY WITHIN TOXICOLOGY PROJECTS. TOXICOLOGY IS AN INTERDISCIPLINARY BROAD FIELD, COMBINING CHEMISTRY, BIOLOGY, MOLECULAR SCIENCES (E.G. OMICS), RISK ASSESSMENT, AND ENVIRONMENTAL SCIENCES IF YOU WILL. WHICH MAY MAKE THIS EVEN MORE CHALLENGING. AS AN END USER (NON-ACADEMIC TOXICOLOGIST) I DO NOT KNOW BEFOREHAND WHICH DATATYPES I NEED TO INTEGRATE FOR A PARTICULAR TOXICOLOGICAL QUESTION: THEREFORE HOW TO PRIORITIZE THE FAIRIFICATION OF THE DIFFERENT DATA SUBDOMAINS.
THEREFORE, THE DEVELOPMENT OF/USE OF FAIR COOKBOOK AND/OR FIP CAN GO MANY WAYS, AS WE DID I THINK EVIDENCED DURING THE WORKSHOP: AND EVEN THOUGH THESE RESOURCES ARE A STEP FORWARD TO ULTIMATE FAIRIFICATION ONE SOLUTION (A FIP, A RECEPY) CREATED BY RESEARCHER X DOES NOT NECESSARILY ACCOMODATES THE NEED FOR RESEARCHER Z, HOW TO DEAL WITH THIS

IDEALLY WE WOULD LIKE TO HAVE ONE LARGE OVERARCHING FIP TO COVER THE WIDEST POSSIBLE DATA DOMAIN NEEDED (OR NEEDED IN FUTURE) FOR TOXICOLOGY. BUT IS THIS REALISTIC AND FEASIBLE?. WE WILL AT LEAST TRY THIS NOW WITHIN THE TOXICOLOGY COMMUNITY WITHIN PARC: TO BUILD A TOXICOLOGY REFERENCE FIP, SUPPORTIVE TO THE PARC TOXICOLOGY PROJECTS.

CAN WE LEARN FROM OTHER INTERDISCIPLINARY DISCIPLINES (TECHNOLOGY) IN WHICH STANDARDISATION HAS BEEN MORE ADVANCED,  ETC ETC? HOW WAS THIS, OR WAS THIS AT ALL, ULTIMATELY ENFORCED WITHIN LARGER COMMUNITIES? 
CAN WE ENFORCE FAIRIFICATION WITHIN THE TOX COMMUNITY, OR IS THIS OT THE WAY TO GO?

NON-ACADEMIC TOXICOLOGY/RISK ASSESSMENT IS CONSERVATIVE AND MATTERS WILL ONLY CHANGE SLOWLY: FOR TOXICOLOGY OBVIOUSLY OECD/ECHA ETC COULD PLAY A ROLE HERE. FROM RECENT WORK (STIERUM ET AL. 2024 IN PREP. )WE DID IN PARC (FREQUENCY ANALYSIS OF TERMS RELEVANT TO THE PARC FAIR DATA POLICY (E.G. "DATA SHARING AND COLLABORATION" AND "ETHICS AND FAIRNESS", ACCROSS DIFFERENT STAKEHOLDER DOCUMENTS A.O. FROM DECENTRALIZED RISK ASSESSMENT AGENCIES) IT WAS DEMONSTRATED THAT THE "PENETRATION" OF FAIR CONCEPTS WITHIN THESE REGULATORY COMMUNITIES IS MINIMAL. PROBABLY WITH A REASON AS CHEMICAL DOSIERS OFTEN CONTAIN WELL-DEFINED DATA SPACES, THAT ARE OFTEN (PARTIALLY) CONFIDENTIAL, WITH LESS NEED FOR INTEGRATION. THIS MAY CHANGE HOWEVER AS INCREASINGLY RESEARCH DATA MAY BE USED IN DOSIERS IN WEIGHT OF EVIDENCE APPROACHES, SUPPORTING GROUPING/READ ACCROSS BASED UPON NGRA (IN FACT ONE OF THE GOALS OF PARC!) 

-->

<!-- ## Acknowledgements

... -->

## Funding

This workshop was funded by the ELIXIR Europe INTOXICOM grant (Grant No. NL-2023-INTOXICOM).
Participants acknowledge funding from
CHIASMA (Grant agreement No. 101137613),
PARC (Grant agreement No. 101057014 and UKRI Grant No. 1752317),
WorldFAIR (Grant agreement No. 101058393 and UKRI Grant No. 1831977),
PINK (Grant agreement No. 101137809) and UKRI Grant No. 10097944),
RISKHUNT3R (Grant agreement No. 964537),
Swedish Fund for Research without Animals (Grant No. F2022-0003),
GACR (Grant Agreement No. 24-11986S),
Palacky University (Grant Aggreement ID: IGA\_PrF\_2024_017)
ELIXIR Data Platform, Stichting Health-RI, EFSA,
de.NBI (Grant agreement No. BMBF 031A540),
and SysBioTop-Moving grant from ZonMw (Grant agreement No. 20190702211652).
The VHP4Safety project is funded by the Netherlands Research Council (NWO) (Grant agreement No. NWA-ORC 1292.19.272).

## References
