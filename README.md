# EMSE Open Science Initiative

___
**Notes on current version:**

To give feedback about this proposal, there are two possibilities:
* comment on the pull-request discussion tread
* comment a specific line by clicking in the left margin)

___

Openness in science is key to fostering progress via transparency, reproducibility, and replicability. Especially open data and open source are two fundamental pillars in open science as both build the core for excellence in evidence-based research. The Empirical Software Engineering journal (EMSE) has therefore decided to explicitly foster open science and reproducible research by encouraging and supporting authors to share their (anonymized and curated) empirical data and source code in form of replication packages.

The overall goals are:
* Increasing the transparency, reproducibility, and replicability of research endeavours. This not only supports the immediate credibility of authors' work, but it also provides a common basis for joint community efforts grounded on shared data.
* Building up an overall body of knowledge in the community leading to widely accepted and well-formed software engineering theories in the long run.

This repository describes the principles, the process, and the infrastructure that support this initiative.


## Open Science Board

Chairs: TBA

Board members: TBA


## Open Science Principles at EMSE

As for any initiative in a research community, the success of the Open Science Initiative, too, depends on the willingness and the possibilities of authors to disclose their data. Therefore, we strive to implement the Open Science Initiative at EMSE as a community effort with services that aim at encouraging and supporting authors of EMSE articles in opening up their research. The steering and motivating principle is that only openness in empirical research increases the transparency of research in a way such that the authors' empirical analyses can be reproduced, fully understood, and ideally replicated by others not involved in the research. To this end, we aim at promoting a data-sharing culture where authors publicly archive their data and related material required to understand and reproduce the claims and analyses presented by them in their manuscripts. Our hope is to move our community forward to the point where open science becomes the norm.

All submissions to EMSE will undergo the same known review process regardless of whether authors decide to disclose their data or not. Yet, as the leading journal in empirical research methodologies and their application to software engineering, we strongly encourage all authors to make an effort in supporting this initiative by making data available upon submission (either privately or publicly) and especially upon acceptance (publicly). Authors who cannot disclose non-public data (e.g. industrial data sets that fall under non-disclosure agreements), are asked to please provide an explicit and short statement in their manuscript.

To make research data sets and research software accessible and citable, we encourage authors to:
* archive data on preserved archives such as zenodo.org and figshare.com so that the data will receive a DOI and become citable, and
* use the CC0 dedication (or the CC-BY 4.0 license) when publishing the data (automatic when using, for instance, zenodo.org or figshare.com).

Those *replication packages* disclosed by the authors will then undergo an additional, short, review by the open science board as described next. When archiving data as part of a replication package, we ask authors to attend to the [FAIR](https://www.force11.org/group/fairgroup/fairprinciples), i.e. data should be:
* Findable,
* Accessible,
* Interoperable, and
* Reusable.

Authors should therefore use archived only repositories and avoid putting data and software on their own (institutional or private) websites or systems like Dropbox, version control systems (SVN, Git), or service like Academia.edu and ResearchGate. Personal websites are prone to changes and errors, and more than 30% of them will not work in a 4 years period. Moreover, nobody should have the ability to delete data once it is public.


## Process

1. Once a manuscript gets "Minor revision", the decision email contains the following text:
    * "EMSE encourages open science and reproducible research. Not only is this good for scientific progress and the community as a whole, it also leads to more impact (and citations). A revision is no guarantee of future acceptance, but if your manuscript is eventually accepted for publication in EMSE you will have the option to provide a replication package. We suggest to prepare for this already now. To get more information about the open science initiative, please visit https://github.com/emsejournal/openscience"
1. Once a manuscript is accepted, the authors are invited to submit a replication package
    * upon acceptance, one of the EiCs forwards the paper to the Open Science Chairs who selects a suitable Open Science board member.
    * the acceptance email explicitly asks to submit a URL to the replication package.
        * email text: "EMSE encourages open science and reproducible research and your paper can be badged as "open science". To do so, please send an email containing the URL to the replication package at emsejournal.openscience@chalmers.se. To get more information about the open science initiative, please visit https://github.com/emsejournal/openscience"
    * the authors are given 2 weeks to submit their replication package.
1. Once the Open Science Board receives the URL to the replication package, the Open Science Chairs asks one member of the Open Science board to review the package.
    * The review is made according to a review guideline
    * The open-sience reviewer is given two weeks to accept or consolidate a list of questions to the authors
    * The open-science review is blinded, the open-sience reviewer does not sign her review
1. If necessary, the open science reviewer asks for changes by sending an email to the authors
    * the authors are given another two weeks to make the changes.
1. The open science reviewer makes the final decision.
    * If the replication-package is rated as unsifficient, the manuscript is still accepted and the authors are given a list of constructive comments on how to improve their open science practices
	* If the replication package is considered to be of good or excellent quality, the authors can add in their final version. "Open-science Replication Package validated by the Open Science Board".


## Infrastructure

**This repository will provide**

* Frequently asked questions on preparing a replication package (joint work together with the open science editorial board)
* Points of contacts in case of questions are not adressed via the FAQ section
* Review guideline for Open Science board members

## Badges to Acknowledge Open Science

To acknowledge the authors' contribution to open science upon publication of their manuscript and provided successful recommendations by the open science board, we introduce [Open Science Framework badges](https://osf.io/tvyxz/wiki/home/) as a recognition associated with their publication and displayed on their manuscript. In particular, we reward two badges:
1. **Open Data:** The Open Data badge indicates the availability of data necessary to reproduce the reported results publicly available.
1. **Open Materials:** The Open Materials badge indicates the availability of the components of the research methodology necessary to reproduce the reported procedure and analysis.

___
**Notes:**

Please note that it is currently discussed with Springer how to potentially integrate open science metadata and badges in the publication platform and in the published PDFs. Updates on this and an exact procedures will follow here.
___
