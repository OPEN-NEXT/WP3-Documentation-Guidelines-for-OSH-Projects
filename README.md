# WP3-Documentation-Guidelines-for-OSH-Projects
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
 
5.3	License documentation guide (TL;DR)
·	the work package teamed up with open source communities to a) gather intuitive guidelines for needs addressed in the interviews of T3.1, b) identify important gaps for which guidelines are still needed and c) learn from the format open source communities use to spread their knowledge.
·	it was found that so called “tl;dr” (to long; didn’t read) documents and sections are used to communicate most essential points of a certain matter to users and contributors as fast and effortlessly (for them) as possible.
·	Since accurate licensing of OSH was also a major concern among pilots in WP4/5, the team collaborated with the legal issues working group of Open Source Ecology Germany e.V. (non-profit) to draft a tl;dr document explaining basics of IP law and licensing for OSH. The knowledge was primarily taken from the “OSH Guideline | Legal Issues” (ref) distributed by their legal issues working group. Feedback from the OPEN!NEXT consortium has been collected and will be integrated. Once done, the final document will be integrated into Open Source Ecology Germany’s GitLab repository to be further distributed and maintained by their community.
5.3.1	Design notes
Without a free/open license technical documentation of a project is legally not available for others. Despite CERN’s efforts of developing and distributing well maintained licenses in comprehensive licensing schemes, the OSH community struggles with projects using no or inappropriate licenses.
[Guidance for licensing hardware was requested by user story XXX.]
Since accurate licensing of OSH was also a major concern among pilots in WP4/5, the team reached out to the OSH community to find reliable material and experts willing to contribute. A cooperation was started with the legal issues working group of Open Source Ecology Germany e.V. (non-profit), which is one of the biggest community-driven organisation for open source hardware in Europe. In reconciliation with their working group, the team created a compact, intuitive guideline about how IP law works for open source hardware and how licensing is done. The knowledge was primarily derived from the extensive “OSH Guideline | Legal Issues” (ref) distributed by their legal issues working group. The OSH community gave feedback to shape the form of the document so that other community members would read and understand it. The final document aims to provide essential legal knowledge at a very low threshold within a short amount of time.
All material for the document (including pictograms) is used under a free/open license. The document itself has been released under a free/open license on GitHub (ref). Hence, the full content is freely exploitable for anyone and any use.
5.3.2	Usage
The document consists of two parts:
•	page 1 for IP law essentials,
•	page 2 for licensing OSH.
Page 1 aims to provide recipients with the minimum necessary overview in IP law and outlines the necessity and usefulness of an appropriate open source license. Page 2 builds upon that knowledge, explains the most relevant licensing schemes and gives concrete recommendations.
The document is primarily distributed in digital form via the GitHub repository with PDF exports for each release, which makes unambiguous referencing in online discussions easy. The design is also feasible for print e.g. as posters in makerspaces.
5.3.3	Outlook
The document received overall positive feedback from the OPEN!NEXT consortium; however room for improvement has been pointed out – this has been documented and will be integrated by the team. Once done, the final document will be integrated into Open Source Ecology Germany’s GitLab repository in order to contribute back to their efforts and so the document will be further distributed and maintained by their community.
For WP4/5 workshops with the pilots on legal issues have been planned; this document will serve as essential material for them. For the workshop series, it is also considered to create more documents of this style for other fields of interest of pilots and makerspaces so that modular material can circulate beyond the OPEN!NEXT project.
The collaboration the legal issues working group also led to a rework of license recommendations on the Wikifactory platform. The new recommendations have been worked out but are still to be implemented by WIF developers.

 
5.4	Contribution guidelines - WIF
The main objective of this section is to provide the users with an easy way to integrate templates in their open-source hardware projects. Those templates may be focused on different topics and present different structures. Thus, the users will be able to choose the one that better suits their project. 
As a use case, we propose the integration of this documentation and guidelines in the Wikifactory platform. Besides that, the documentation guidelines used to illustrate the process are those ones designed by the Grenoble INP, which can be found in this GitHub repository: https://github.com/OPEN-NEXT/wp2.3_Guideline-for-documentation-of-OSH-design-reuse. 
5.1	Installation
As a first iteration of this deliverable, there is no specific installation required. Instead of that, it is only required to clone the source guidelines repository, which will serve as the initial step for the user. In Section 5.4 we present an example of how those templates can be integrated within the Wikifactory platform.
5.2	Usage
Please, check Section 5.4 for the details on how to use the guidelines and templates within the Wikifactory platform.
5.3	Design notes
The Documentation folder defined within the repository gathers all the different categories to be considered when documenting the project. In particular, the categories are shown in Figure 17.
 
Figure 24 Documentation categories
As can be seen in Figure 17, the guidelines for the documentation go through all the stages of the project. Starting from a general introduction to the project, passing through the specification and design stages. After that, there are guidelines with regards to the process of manufacturing the project, as well as for the assembly stages. Finally, there are guidelines to illustrate how to use the project as well as how to maintain it. There is a last step, associated to the disposal step once the project is no longer used. This categorization is still a work in progress, so the order and content of the shown ones may be altered. 
5.4	Result
In order to integrate the guidelines in a new project in the Wikifactory platform, there are two possibilities. On the first one, the user would import the GitHub repository using the import-export functionalities presented in Section 2 and by following the instructions listed in Section 2.4. 
Once imported, the templates and guidelines will be available for the user in the Wikifactory platform, as Figure X depicts:
 
Figure 25 Screenshot of the documentation and guidelines imported in a Wikifactory project
As shown in Figure 16, there is number of pre-defined folders and documents that the user can follow to document the project. In particular, the most important one is the Documentation folder, which contains the templates themselves.
The other possibility for integrating the documentation and guidelines in a new project, consists of forking a template project already existing in Wikifactory. The only required step facing the user, consists of going to templates project, and click on the fork button, as Figure X depicts.
By doing that, the user will have its own copy of the template project, which she can start updating and tailoring to her own purposes.
Facing the future, there are plans to facilitate even more the integration of the documentation and guidelines in the projects. Thus, when the user is creating a new project (note that this is a different option that importing the GitHub repository or forking the templates project), she will be able to select the desired templates from a set of possible ones. Not only that, but she will be able to adapt them according to the context of the project. Thus, unnecessary guidelines components could be removed in this selection step, so the will not be present later in the project.
