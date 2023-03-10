# Distributed Identity (Governance)

## Sub-problems
- How to enable users to create and manage their own digital identities that are portable, secure and privacy-preserving¹.
- How to verify and authenticate users' identities across different platforms, applications and services without relying on centralized authorities or intermediaries².
- How to link users' identities with their data assets and transactions, and provide them with control over how their data is accessed and used by others³.


Source: Conversation with Bing, 3/5/2023
1. Microsoft’s 5 guiding principles for decentralized identities. https://www.microsoft.com/en-us/security/blog/2021/10/06/microsofts-5-guiding-principles-for-decentralized-identities/ Accessed 3/5/2023.
2. 6 Identity and Access Management Trends to Plan for in 2022 - Gartner. https://www.gartner.com/en/articles/iam-leaders-plan-to-adopt-these-6-identity-and-access-management-trends Accessed 3/5/2023.
3. Decentralized Identity Solution | Microsoft Security. https://www.microsoft.com/en-us/security/business/solutions/decentralized-identity Accessed 3/5/2023.



## Distributed Identity solutions

- **Microsoft's decentralized identity solution**¹: This is an open-standards based identity framework that uses digital identifiers and verifiable credentials that are self-owned, independent and enable trusted data exchange. It aims to protect privacy and secure online interactions using blockchains, distributed ledger technology and other decentralized systems.
- **World Bank's interoperability frameworks**²: These are guidelines and recommendations for developing and implementing interoperability frameworks for digital identification systems across different sectors, domains and jurisdictions. They cover aspects such as governance, architecture, data standards, security and privacy.
- **Decentralized Identity Foundation (DIF)**³: This is a collaborative organization that aims to develop common specifications, protocols and tools for decentralized identity systems. It focuses on areas such as DID methods, verifiable credentials, universal resolver, identity hubs and agents.

- **Self-regulatory organizations (SROs)**[4]: These are non-governmental entities that create and enforce rules and standards for a specific industry or domain. They can provide a decentralized digital identity infrastructure that is aligned with government regulations and stakeholder interests.
- **International technical standards**[5]: These are specifications or guidelines that define how different systems, processes or data should interact or operate. They can ensure interoperability, security and quality of digital identity systems across different contexts and platforms.
- **Distributed computing**[6]: This is a field of computer science that studies how multiple computers can work together to achieve a common goal. It can offer techniques and principles for designing scalable, resilient and efficient distributed identity systems.



Source: Conversation with Bing, 3/5/2023

1. Decentralized Identity Solution | Microsoft Security. https://www.microsoft.com/en-us/security/business/solutions/decentralized-identity Accessed 3/5/2023.
2. Interoperability frameworks | Identification for Development - World Bank. https://id4d.worldbank.org/guide/interoperability-frameworks Accessed 3/5/2023.
3. DIF - Decentralized Identity Foundation. https://identity.foundation/ Accessed 3/5/2023.
4. Frontiers | A Decentralized Digital Identity Architecture. https://www.frontiersin.org/articles/10.3389/fbloc.2019.00017/full Accessed 3/5/2023.
5. Technical Standards for Digital Identity - World Bank. https://pubdocs.worldbank.org/en/579151515518705630/ID4D-Technical-Standards-for-Digital-Identity.pdf Accessed 3/5/2023.
6. Why Identity Needs A Distributed Computing Mindset - Forbes. https://www.forbes.com/sites/forbestechcouncil/2021/05/13/why-identity-needs-a-distributed-computing-mindset/ Accessed 3/5/2023.




## Digital object architecture framework (DOA)

  

The Digital Object Architecture (DOA) is a general architecture for a distributed information storage, location and retrieval system running over the Internet¹. It defines the concept of a **Digital Object**, which is a structured record containing data, state information about the data and metadata³. It also specifies two associated protocols: the **Digital Object Identifier Resolution Protocol (DO-IRP)**, which is used for creating, updating, deleting and resolving identifiers that are globally managed and allotted³, and the **Digital Object Interface Protocol (DO-IP)**, which is used for accessing services associated with digital objects⁴. The DOA also defines three core components: **Repositories**, which are systems where the information is stored; **Identifiers/Handles**, which are a set of identifiers for locating digital objects; and **Resolution Services**, which are systems that map identifiers to locations or services¹⁴.

The goal of DOA is to extend the current internet architecture to support information management more broadly than just conveying information in digital form from one location to another³. It allows for flexibility in how it is used to provide a service, especially in how data and metadata are represented¹.

Source: Conversation with Bing, 3/5/2023
1. Overview of the Digital Object Architecture (DOA). https://www.internetsociety.org/resources/doc/2016/overview-of-the-digital-object-architecture-doa/ Accessed 3/5/2023.
2. Digital Object Architecture | DONA Foundation. https://www.dona.net/digitalobjectarchitecture Accessed 3/5/2023.
3. Overview of the Digital Object Architecture (DOA) - Internet Society. https://www.internetsociety.org/wp-content/uploads/2017/08/ISOC-DOA-Overview-20161025-A4-3_0.pdf Accessed 3/5/2023.
4. Facilitating the Adoption of the FAIR Digital Object Framework in .... https://www.nist.gov/programs-projects/facilitating-adoption-fair-digital-object-framework-material-science Accessed 3/5/2023.

 

## Applications of DOA

- **Facilitating interoperability** between or among different systems, processes and other information resources, including different identity management systems¹². For example, DOA can enable different repositories to exchange and access digital objects using common protocols and identifiers².
- **Providing long-term persistence** of information in a network environment over potentially very long time frames². For example, DOA can ensure that digital objects remain accessible and identifiable even if their locations or formats change over time³.
- **Facilitating secure sharing** of information that may be public, private or some combination thereof². For example, DOA can support integrated public key management within the same infrastructure used to manage other information².

Source: Conversation with Bing, 3/5/2023 
1. Overview of the Digital Object Architecture - Corporation for National .... http://www.cnri.reston.va.us/papers/OverviewDigitalObjectArchitecture.pdf Accessed 3/5/2023.
2. A Brief Overview of the Digital Object Architecture and its Application .... http://www.cnri.reston.va.us/papers/Digital_Object_Architecture_Brief_Overview.pdf Accessed 3/5/2023.
3. Overview of the Digital Object Architecture (DOA). https://www.internetsociety.org/resources/doc/2016/overview-of-the-digital-object-architecture-doa/ Accessed 3/5/2023.
4. Overview of the Digital Object Architecture - Corporation for National .... http://www.cnri.reston.va.us/papers/OverviewDigitalObjectArchitecture.pdf Accessed 3/5/2023.
5. Digital Object Architecture | DONA Foundation. https://www.dona.net/digitalobjectarchitecture Accessed 3/5/2023.

 

## Public key management in DOA

 
Public key management in DOA is a mechanism for ensuring the authenticity and integrity of digital objects and their associated services. It involves using public key cryptography to sign and verify digital objects and their identifiers¹. Public keys are also used to encrypt and decrypt information that may be sensitive or confidential⁴.

Public keys are stored as part of the identifier records that are associated with digital objects⁵. These records can be resolved using the **Digital Object Identifier Resolution Protocol (DO-IRP)**, which is one of the core protocols of DOA⁵. Public keys for handle services, which are systems that provide resolution services for identifiers, are currently stored in the **Global Handle Registry (GHR)**, which is a central repository for managing identifiers⁴. However, this may change as the global management of DOA evolves⁴.

Source: Conversation with Bing, 3/5/2023
1. Digital Object Architecture - DocsLib. https://docslib.org/doc/12192704/digital-object-architecture Accessed 3/5/2023.
2. Overview of the Digital Object Architecture - Corporation for National .... http://www.cnri.reston.va.us/papers/OverviewDigitalObjectArchitecture.pdf Accessed 3/5/2023.
3. Digital Object Architecture | DONA Foundation. https://www.dona.net/digitalobjectarchitecture Accessed 3/5/2023.
4. Digital Object Architecture - DocsLib. https://docslib.org/doc/12192704/digital-object-architecture Accessed 3/5/2023.
5. Overview of the Digital Object Architecture (DOA). https://www.internetsociety.org/resources/doc/2016/overview-of-the-digital-object-architecture-doa/ Accessed 3/5/2023.

 


## DOA Adoptions

- **The Research Data Alliance (RDA)**, which is an international organization that aims to build social and technical bridges to enable open sharing of data. RDA has developed a set of recommendations and outputs based on DOA, such as the **Data Type Registry** and the **PID Kernel Information**¹.
- **The DONA Foundation**, which is a non-profit organization that promotes the use of DOA for global information management. DONA has established a network of **Multi-Primary Administrators (MPAs)**, which are entities that can assign identifiers and manage resolution services for digital objects².
- **The IBM Cloud Pak for Data**, which is a platform that integrates data and AI services to help organizations accelerate their digital transformation. IBM Cloud Pak for Data leverages DOA to provide a unified metadata layer that enables data discovery, governance and lineage across multiple sources³.

Source: Conversation with Bing, 3/5/2023
1. Overview of the Digital Object Architecture (DOA). https://www.internetsociety.org/resources/doc/2016/overview-of-the-digital-object-architecture-doa/ Accessed 3/5/2023.
2. Overview of the Digital Object Architecture (DOA) - Internet Society. https://www.internetsociety.org/wp-content/uploads/2017/08/ISOC-DOA-Overview-20161025-A4-3_0.pdf Accessed 3/5/2023.
3. Four Architecture Choices for Application Development in the Digital .... https://www.ibm.com/cloud/blog/four-architecture-choices-for-application-development Accessed 3/5/2023.



## DOA implementations (besides DOI)
 

- **The Handle System**, which is a distributed system for assigning, managing and resolving persistent identifiers for digital objects. The Handle System is based on DOA and implements the **Digital Object Identifier Resolution Protocol (DO-IRP)**¹.
- **The Internet of Things (IoT) with DOA**, which is an approach that integrates IoT devices and data with DOA. This approach uses digital objects to represent IoT devices and their associated information, and provides a unified framework for discovery, access and management of IoT resources².
- **The Global Digital Object Cloud (GDOC)**, which is a platform that enables the creation, storage and retrieval of digital objects using DOA. GDOC provides a set of services and tools for managing digital objects across different domains and applications³.

Source: Conversation with Bing, 3/5/2023
1. Overview of the Digital Object Architecture (DOA). https://www.internetsociety.org/resources/doc/2016/overview-of-the-digital-object-architecture-doa/ Accessed 3/5/2023.
2. Integrating Internet of Things with the Digital Object Architecture. https://link.springer.com/chapter/10.1007/978-3-030-30859-9_47 Accessed 3/5/2023.
3. Overview of the Digital Object Architecture (DOA) - Internet Society. https://www.internetsociety.org/wp-content/uploads/2017/08/ISOC-DOA-Overview-20161025-A4-3_0.pdf Accessed 3/5/2023.

