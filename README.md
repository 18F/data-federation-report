# Data Federation Project

The U.S. Data Federation project promotes government-wide capacity-building to support distributed data management challenges, data interoperability, and broader data standards activities. The project is an initiative of the GSA Technology Transformation Services (TTS) [10x](10x.gsa.gov) program, which funds technology-focused ideas from federal employees with an aim to improve the experience all people have with our government. 

## Overview

U.S. government policies, initiatives, and public-facing products and services depend on aggregating and harmonizing data from disparate government sources. **The goal of the U.S. Data Federation project is to document repeatable processes, develop reusable tooling, and curate resources to support federated data projects.** 

We define a federated data project as an effort in which a common type of data is collected or exchanged across complex, disparate organizational boundaries. For example, federal agencies often need to collect data from state and local governments, other federal agencies, and other data providers. These federated data may be used to support policy or budget decisions, operational efficiencies, or published in aggregate form for other data users. 

Federated data efforts are increasingly seen as an engine for transparency, economic growth, and accountability, yet collecting this kind of data remains a challenge. While this type of data management effort is growing increasingly common in our distributed style of government, each new effort is still improvising solutions in terms of processes, tooling, and compliance infrastructure. **Many of these federated data efforts face common requirements and common challenges, but lack common resources.** 

The U.S. Data Federation project was conceived in 2016 to address this gap. The project set out to identify common challenges and pain points in federated data efforts and address these needs by curating best practices and resources and developing reusable tooling. The best practices and resources were intended to include guides and repeatable processes around data governance, organizational coordination, and standards development in federated environments. The reusable tools were intended to include capabilities around data validation, automated aggregation, and the development and documentation of data specifications.   

Over the course of its first three phases of 10x funding, it began to deliver on this ambition by building and launching ReVal, a Reusable Validation Library, which has been used by the USDA Food & Nutrition Services and other agencies to streamline data collection and validation processes. 

During Phase 4, the team took advantage of a unique opportunity to unite government-wide efforts to support open data and federated data efforts. The team has supported Data.gov, OMB, and OGIS stakeholders in developing a vision and delivering increased functionality for resources.data.gov, a legislatively-mandated online repository of policies, tools, case studies and other resources to support data governance, management, and use throughout the federal government. 

After conducting research with the stakeholders and audience for resources.data.gov, the team saw an opportunity for a long-term practical manifestation of the Data Federation as the content strategy team underpinning resources.data.gov. The future funding and organization of this work is currently under negotiation.

## Project milestones

**Phase 1** (Fall 2017)

*Team: Phil Ashlock, Anthony Garvan*
-   Interviewed a variety of distributed data management projects and synthesized findings in a [Data Federation Framework](<https://github.com/18F/data-federation-report/blob/master/DataFederationFramework.md>). 
-   Created a placeholder for future web content at federation.data.gov
-   Pitched for Phase 2 funding based on finding that reusable tooling and processes would benefit future federated data efforts

**Phase 2** (Spring 2018)

*Team: Phil Ashlock, Catherine Devlin, Anthony Garvan, Chris Goranson, Joe Krzystan*
-   Prototyped a reusable data validation tool that allows users to submit data via a web interface or API to be validated against a set of customizable rules in real time
-   Partnered with the USDA Food & Nutrition Service (FNS) to adapt this tool for the FNS-742, a form that collects verification data for the National School Lunch Program 
-   Pitched for Phase 3 funding to further develop the tool, implement it with FNS, and conduct outreach to identify other partners and other opportunities for reusable tools  (Phase 2 Final Presentation)

**Phase 3** (December 2018-June 2019)

*Team: Phil Ashlock, Mike Gintz, Mark Headd, Ethan Heppner, Julia Lindpaintner, Amy Mok*
-   Developed Phase 2 prototype into Reusable Validation Library ([ReVal](https://github.com/18F/ReVAL)) with a focus on API-based usage
-   Worked with FNS to develop ReVal's first custom manifestation for FNS-742 as the [FNS Data Validation Service](https://github.com/18F/usda-fns-ingest)
-   Validated demand for ReVal and identified future partners 
-   Continued to identify common needs and useful reusable resources for data efforts through outreach and presentations to the Data Exchange Community of Practice, Interagency Working Group on Open Data, VA Open Data Working Group, and others
-   Began building a community around a shared need for knowledge-sharing across data efforts in government
-   Protect against redundancy by aligning the efforts of the U.S. Data Federation with other efforts across government, such as the work of the Federal Data Strategy and the mandates of the Evidence Act and Open Government Data Act 
-   Pitched for Phase 4 funding to leverage the completion of ReVal and the momentum of the U.S. Data Federation work to support a long-term vision and strategic plan for a user-centered, maximally-effective resources.data.gov

**Phase 4** (October 2019-April 2020)

*Team: Phil Ashlock, Mike Gintz, Julia Lindpaintner, Amy Mok, Princess Ojiaku, James Tranovich*
-   Collaborated with resources.data.gov stakeholders (GSA, OMB, OGIS) to identify likely audience and begin to define a long-term vision of success for the resource repository
-   Conducted interviews with over 30 people across 14 agencies, including 5 Chief Data Officers, data scientists, organizers of internal open data working groups, Federal Data Strategy detailees, and many others involved in their agency’s data governance or data management efforts 
-   Outlined a long-term vision for the U.S. Data Federation as the content strategy team underpinning resources.data.gov and plans to prototype this approach during Phase 4
-   Reviewed all content and implemented new information architecture, navigation, and functionality in response to user research in order to make resources in the repository maximally discoverable
-   Prototyped the process of abstracting agency-specific resources to make them more broadly useful to other agencies

## References and deliverables

**Phase 1**

- [Interview notes](https://github.com/18F/data-federation-report/issues?utf8=%E2%9C%93&q=is%3Aissue+interview)
- [Preliminary Findings](https://github.com/18F/data-federation-report/blob/master/PreliminaryFindings.md)
- [US Data Federation Framework](https://github.com/18F/data-federation-report/blob/master/DataFederationFramework.md) (includes [Data Federation Maturity Model](https://github.com/18F/data-federation-report/blob/master/DataFederationFramework.md#the-data-federation-maturity-model) and [Data Federation Playbook](https://github.com/18F/data-federation-report/blob/master/DataFederationFramework.md#the-data-federation-playbook))

**Phase 2**

- [Final presentation (PDF)](assets/US-Data-Federation-Phase-II-Final.pdf)
- Prototype [Django Data Ingest Tool](https://github.com/18F/ReVAL) 

**Phase 3**

- [Project overview (PDF)](assets/Project-Overview-for-Partners-Stakeholders.pdf)
- [Project overview with FNS case study (PDF)](assets/Project-Overview-with-FNS-Case-Study.pdf)
- [Project overview presentation (PDF)](assets/US-Data-Federation-Project-Intro.pdf)
- [Webinar via Digital.gov on April 17, 2019](https://youtu.be/r4XUu2MLrDo) // [Slides (PDF)](assets/Digital.gov%20Presentation%20%E2%80%94%20US%20Data%20Federation.pdf)
- [18F blog post](https://18f.gsa.gov/2019/03/05/the-us-data-federation/) on U.S. Data Federation project
- [Federal Data Strategy Proof Point](https://strategy.data.gov/proof-points/2019/05/17/supercharging-data-through-validation-as-a-service/) on the USDA FNS Data Validation Service
- [Phase 4 pitch presentation (PDF)](https://github.com/18F/data-federation-project/blob/master/assets/10x%20Data%20Federation%20Phase%204%20pitch.pdf)

**Phase 4**  
*Forthcoming*

**Biweekly updates**  
Starting in Phase 3, the team began publishing updates on its activities and progress roughly bi-weekly. All past updates can be found [here](https://github.com/18F/data-federation-project/tree/master/updates).

### Related repositories

There are several repositories that contain code that is a part of this project.

* Github repo for the US Data Federation website: https://github.com/GSA/us-data-federation
* Github repo for ReVal, the US Data Federation's first reusable tool for data validation and aggregation: https://github.com/18F/ReVAL
* Github repo for the FNS Data Validation Service, which uses ReVal to check submitted FNS-742 data against a set of centralized validation rules via API: https://github.com/18F/usda-fns-ingest
* Github repo for the Workzone Data Exchange (WZDx) Validator, which uses ReVal to perform JSON Schema validation against the WZDx v1.1 specification: https://github.com/18F/usdot-jpo-ode-workzone-data-exchange

*Other repos referenced:*

* https://github.com/18F/couch-rules-engine
* https://github.com/18F/goodtables-gov
* https://github.com/18F/cx-cap-goal
