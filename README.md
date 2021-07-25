Product development is often complex; In OSH product development there are additional layers of tasks. OSH products and projects need to be documented so that it is accessible to and understood by a diverse group of interested community and its collaborators. The methodologies used to develop and document also vary depending on the product and the project community. To ease process of documentation a few documentation templates and guidelines were developed. These can be categorized into 4 main categories as shown the figure below: 
An image here as well perhaps with the 4 categories we worked on here
5.1	Project/Product overview template
It is often recommended to document continuously during product development, however when an interested community member wants to get an idea about the project itself, it can be hard to find an overview underneath the complete project documentation. Hence, an up to date project overview improves the visibility and readability of the project to the community. Hence, inspired by a project template  on Wikifactory, a new version of the same was developed to cater to OSH and C3. 
The new template is in the form of a markdown so that it can easily be copied/duplicated and uploaded onto any online platform. The template has the following sections: 
•	About your project
•	Current status
•	The problem
•	Product features/ functions
•	Project viability
•	The team
•	The Bill of materials
•	The manufacturing/production/assembly
•	About the design
•	Electronics and programming
•	About the prototype
•	Potential improvements
Each of the above sections, are presented with a set of questions, which helps in documenting essential information by answering them. A snippet of the same can be seen in the Figure 1. Further deep links are also provided to learn about certain topics such as about the licenses, technology readiness levels as shown in the figure under sections about your project and current status respectively. 




5.2	Technology-readiness levels for OSH
·	to enable a fast and intuitive assessment of the stage of an OSH product (as requested by u/xx/xx) technology readiness level specifically for the assessment of OSH will be developed. This assessment shall be executable for OSH developers skilled in the field of technology of the corresponding OSH without any additional information, but the short description of these levels. A corresponding data field has been integrated into the ontology of T3.3.
·	The current draft maps TRLs from EU-H2020 Annex G (ref) onto OSD processes. However, the team is currently working to simplify the category system in order to allow for intuitive and decentralised use of the approach. Furthermore, following DIN SPEC 3105-1, the approach was extended by readiness levels for the technical documentation of OSH since no OSH qualifies for design reuse or replication when the necessary information is not accessible.
5.2.1	Design Notes
For effective design reuse and practical application of locally produced open source hardware, prior maturity assessment of the technical solution is needed.
[This was also found in the user stories xxx and xxx.]
Technology-Readiness Levels (TRL) can provide users very quickly with this essential information so that time consuming study of the technical documentation will not be necessary in most cases.
Following the decentralised nature of open source product development, assessment of TRL shall be realisable for any developer skilled in the corresponding field of technology, without knowing much about the history of the development. Of course, this depends on the quality of documentation of projects; the team took requirements stated in DIN SPEC 3105-1 (Open Source Hardware - Requirements for technical documentation) for reference.
Likewise, TRL must be formulated in intuitive manner so that developers can use the model without further information but the short description of those levels.
The current draft is accessible under a free/open license in the GitHub repository of the metadata specification (ref). Based on EU-H2020 Annex G (ref), it maps TRLs onto open source development processes. This approach aims to foster a deeper understanding for the maturity of technological open source solutions among industrial players, research institutes and OSH Communities; contributing to the overall comparability of OSH products.
5.2.2	Usage
As technical solutions in OSH become accessible by their documentation (and its license) the current draft includes two scales: The Open Technology Readiness Levels (OTRL) and the Open Documentation Readiness Levels (ODRL). To follow the metadata specification (T3.3) OSH developers need to provide the ID of the assessed levels from both scales. The following tables from the specification would be the primary tool to use for OSH developers.
OTRL	Detail	Characteristic
OTRL1	basic principles observed	rough idea
OTRL2	technology concept formulated	concept ready
OTRL3	experimental proof of concept	concept is validated in tests
OTRL4	technology validated in lab	early prototype
OTRL5	technology validated in relevant environment	mature prototype
OTRL6	technology demonstrated in relevant environment	ready-to-use product
OTRL7	system prototype demonstration in operational environment	ready-to-use product (for critical or complex applications)
OTRL8	system complete and qualified	finished product (could be sold in the EU)
OTRL9	actual system proven in operational environment	established product
ODRL	Detail	Characteristic
ODRL0	no documentation available	or noncompliant license
ODRL1	basic information available	know that the OSH is, but not more
ODRL2	drafty documentation	documentation in progress, yet patchy
ODRL3	early release	lots of reconciliation required to build & operate the OSH
ODRL4	relevant realease	few reconciliation required to build & operate the OSH
ODRL5	mature realease	no reconciliation required to build & operate the OSH
The column “Detail” outlines the project or documentation stage of the corresponding level, the column “Characteristic” provides intuitive indicators for each level. Each level is described in more detail in the specification, in case more details are needed. The first column contains the ID of the level, which is equal to its key in the ontology (T3.3). Since the ontology is published under a free/open license on GitHub, the scales are freely exploitable, although specifically designed for Linked-Open-Data-driven approaches.
5.2.3	Outlook
In collaboration with the OSH community, the team continues optimising the classification system, primarily to facilitate its wide adoption.
WIF expressed interest to integrate the last release of the specification to provide users with better filter options when exploring OSH on the Wikifactory platform.
Since primarily developed for the Wikibase instance (T3.3), OTRL and ODRL are part of the ontology and form a crucial element of the metadata specification. By the release of D3.3 OSH developers will be able classify project stages after auditable criteria and make this classification available for others via the Wikibase intance.
The team collaborates with the community around DIN SPEC 3105-1 and the Open Know-How Specification. By the final release the team will contribute its findings to those standardisation efforts in order to support a wider dissemination of the specification.
