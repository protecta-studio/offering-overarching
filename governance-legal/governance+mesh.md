# Governance (+ Mesh)

## Intro
Data governance is the process of defining and implementing rules, roles, responsibilities, processes, standards, policies etc. for managing the quality, security, privacy, ethics etc. of data within an organisation⁶. Data governance aims to ensure that data is accurate, consistent, reliable etc. for its intended use cases⁶.

Data governance can be associated with different architectures such as data mesh or data fabric². Data fabric is another paradigm for big analytical data management that provides an integrated layer of data services across different sources and platforms². Data fabric differs from data mesh in that it does not necessarily require domain-driven ownership or decentralisation of accountability for data².

Data governance can also be applied at different levels such as centralised (where a single authority oversees all aspects of data), decentralised (where each business unit or function has its own authority over its own subset of data), or federated (where there is a balance between centralised coordination and decentralised autonomy)¹⁵. Federated computational governance means that each domain follows a set of standards and policies that ensure interoperability, compliance, and trust across the data mesh⁴⁵.

Benefits of applying data governance in data mesh

- It enables cross-domain collaboration and discovery by providing common metadata standards,
- It ensures compliance with regulations and ethical principles by enforcing policies on access control,
- It enhances trust and confidence in the quality and reliability of the distributed data products by monitoring performance indicators,
- It fosters innovation and experimentation by enabling self-service capabilities and feedback loops.[1][5]

Challenges of applying data governance in data mesh

- It requires cultural change and alignment among different domains and stakeholders,
- It demands technical skills and expertise to implement and maintain complex systems and processes,
- It involves trade-offs between flexibility and consistency, between autonomy and accountability, between speed and quality.[1][5]

1. Data Mesh and Governance | Thoughtworks. https://www.thoughtworks.com/en-us/about-us/events/webinars/core-principles-of-data-mesh/data-mesh-and-governance Accessed 3/9/2023.
2. Data Federation and Governance in a Data Mesh - Confluent. https://developer.confluent.io/learn-kafka/data-mesh/data-governance/ Accessed 3/9/2023.
3. Data Governance for Data Mesh — Nicola Askham. https://www.nicolaaskham.com/blog/2022/10/27/data-governance-for-data-mesh Accessed 3/9/2023.
4. Associating Data Governance with Data Mesh and Data Fabric - Informatica. https://www.informatica.com/blogs/associating-data-governance-with-data-mesh-and-data-fabric.html Accessed 3/9/2023.
5. Data Mesh 101: Why Federated Data Governance Is the Secret ... - LinkedIn. https://www.linkedin.com/pulse/data-mesh-101-why-federated-governance-secret-sauce-seb-bulpin Accessed 3/9/2023.
6. Data Mesh 101: Why Federated Data Governance Is the Secret ... - LinkedIn. https://www.linkedin.com/pulse/data-mesh-101-why-federated-governance-secret-sauce-seb-bulpin Accessed 3/9/2023.

 

## Similar work

- Data mesh on Google Cloud: A solution that provides a set of architectural patterns and best practices for implementing a data mesh on Google Cloud Platform (GCP). It covers aspects such as data product design, data discovery, data access, data quality, data security etc.¹
- IBM Data Mesh: A solution that leverages IBM's cloud services and tools to enable a data mesh architecture. It offers capabilities such as data cataloging, data virtualization, data integration, data governance etc.²
- IEEE Data Mesh Implementation Guide: A guide that provides an overview of the concept and principles of data mesh, along with practical steps and recommendations for implementing it. It covers topics such as domain identification, data product definition, metadata management etc.³
- Google Dataplex
- Nextdata (Zhamak Dehghani startup)
- OvalEdge (india-based stratup)
- Informatica (data catalog, Data Governance)
- Collibra (Data Stewardship, ..)
- Alation
- Talend
- Atlan
- data.world
- MANTA
- Immuta
- Ataccama ONE
- Axon Data Governance
- Azure Data Catalog


Some of the solutions, frameworks, or standards marketed as data governance are:

- Atlan Data Governance Framework: A framework that outlines a comprehensive approach to designing and implementing a data governance strategy. It covers aspects such as defining policies and principles, establishing roles and responsibilities, outlining processes and workflows, implementing tools and platforms, and measuring outcomes and value⁴.
- PwC Global and Industry Frameworks for Data Governance: A collection of frameworks that provide guidance on how to align data governance with global and industry-specific standards and regulations. It covers domains such as banking, insurance, healthcare, telecommunications etc.⁵
- McKinsey Data Governance Design: A framework that provides a pragmatic way to design a fit-for-purpose data governance structure. It covers components such as a central data management office (DMO), data domain leaders, and cross-functional teams⁶.

Source: Conversation with Bing, 3/9/2023
1. Architecture and functions in a data mesh | Data mesh on Google Cloud. https://cloud.google.com/architecture/data-mesh Accessed 3/9/2023.
2. What is a data mesh? | IBM. https://www.ibm.com/topics/data-mesh Accessed 3/9/2023.
3. Data Mesh Implementation Guide | IEEE Computer Society. https://www.computer.org/publications/tech-news/trends/guide-to-implement-data-mesh/ Accessed 3/9/2023.
4. Architecture and functions in a data mesh | Data mesh on Google Cloud. https://cloud.google.com/architecture/data-mesh Accessed 3/9/2023.
5. What is a data mesh? | IBM. https://www.ibm.com/topics/data-mesh Accessed 3/9/2023.
6. Data Mesh Implementation Guide | IEEE Computer Society. https://www.computer.org/publications/tech-news/trends/guide-to-implement-data-mesh/ Accessed 3/9/2023.

 


## Mesh solutions comparison


| Feature | Datakin⁶ | Zaloni¹ | Atlan¹ | Google Dataplex²³ |
| --- | --- | --- | --- | --- |
| Data lineage | Automatically traces data lineage and shows data relationships in a visual graph. | Provides end-to-end data lineage with impact analysis and data quality indicators. | Tracks data lineage across sources and shows data dependencies in a graph view. | Enables automated discovery and management of data lineage across distributed data sources. |
| Data catalog <br>  <br>  <br>  <br>  <br>  <br>| Allows users to search, browse and explore datasets with rich metadata and documentation. | Creates a unified data catalog with business glossary, metadata management and semantic search. | Builds a collaborative data catalog with rich context, annotations and ratings. | Offers an intelligent data fabric that unifies distributed data into a single logical view with consistent metadata and policies. |
| Data quality <br>  <br>  <br>  <br>  <br>  <br>| Monitors data quality metrics and alerts users of any anomalies or issues.<sup>[6]</sup>| Validates data quality rules and enforces data quality standards across the enterprise.<sup>[5]</sup>| Measures data quality scores and flags issues for remediation.<sup>[7]</sup>| Provides built-in tools for validating, profiling, cleansing, transforming, and enriching your datasets.<sup>[10]</sup>
| Offerings  <br>  <br>  <br>  <br>  <br>  <br>| A cloud-native platform that helps you manage your entire analytics lifecycle.| Managed services that include deployment services, support services, professional consulting,<sup>[4]</sup>| An active metadata platform that helps you discover,<sup>[8]</sup>| A fully managed service that helps you unify distributed<sup>[11]</sup>
| Metadata management<br><br><br><br><br><br>| Extracts technical metadata from various sources such as Hive Metastore or Spark Catalogs.<sup>[6]</sup>| Provides comprehensive metadata management capabilities such as ingestion,<sup>[5]</sup>| Automates metadata collection from various sources such as databases,<sup>[7]</sup>| Scans structured<sup>[10]</sup>

Source: Conversation with Bing, 09/03/2023

1. Data Unification with Zaloni: add new data sources and eliminate silos. https://www.zaloni.com/new-data-value-esg/ Accessed 09/03/2023.
2. Data Lineage Solution | Datakin. https://datakin.com/ Accessed 09/03/2023.
3. Datakin Features. https://datakin.com/features/ Accessed 09/03/2023.
4. Datakin (now part of Astronomer) | LinkedIn. https://www.linkedin.com/company/datakinhq Accessed 09/03/2023.
5. Zaloni Arena: Automated Data Governance and Observability. https://www.zaloni.com/ Accessed 09/03/2023.
6. Concourse Solution - Zaloni. https://www.zaloni.com/aws-governance-solution/ Accessed 09/03/2023.
7. Snowflake Data Governance: Discovery, Access Policies & More - atlan.com. https://atlan.com/snowflake-data-governance-explained/ Accessed 09/03/2023.
8. Atlan | Activate your Metadata. https://atlan.com/ Accessed 09/03/2023.
9. Data Discovery & Catalog | Atlan. https://atlan.com/data-discovery-catalog/ Accessed 09/03/2023.
10. Discover data | Dataplex | Google Cloud. https://cloud.google.com/dataplex/docs/discover-data Accessed 09/03/2023.
11. Dataplex | Google Cloud. https://cloud.google.com/dataplex Accessed 09/03/2023.
12. What is Dataplex? | Google Cloud. https://cloud.google.com/dataplex/docs/introduction Accessed 09/03/2023.




## Common issues in inter-organizational governance


Inter-organizational data governance (IODG) is the process of defining and implementing rules, roles, responsibilities, processes, standards etc. for managing the quality, security, privacy etc. of data that is shared among different organisations¹². IODG aims to ensure that data is accurate, consistent, reliable etc. for its intended use cases across organisational boundaries¹².

Common questions and approaches

- What are the benefits and challenges of IODG? Some of the benefits of IODG are: enhancing collaboration and innovation among partners, improving efficiency and effectiveness of data sharing, increasing trust and transparency among stakeholders, and complying with regulations and ethical principles¹². Some of the challenges of IODG are: aligning different interests and objectives among partners, balancing centralisation and decentralisation of control, managing complexity and diversity of data sources and formats, and ensuring security and privacy of sensitive data¹².
- What are the key components or dimensions of IODG? According to a literature review by Jagals et al.³⁴, there are four main constructs or dimensions of IODG: structure (the formal arrangements that define how data is shared), processes (the activities that enable data sharing), participants (the actors that are involved in data sharing), and success (the outcomes or impacts of data sharing)³⁴.
- What are some examples or use cases of IODG? Some examples or use cases of IODG are: supply chain management (where multiple organisations share data on inventory, demand, logistics etc.), healthcare (where different providers share data on patients' medical records, treatments etc.), smart cities (where various entities share data on traffic, energy consumption etc.)¹ [^2 ^][ ^5 ^].
- What are some technologies or tools that support IODG? Some technologies or tools that support IODG are: blockchain (a distributed ledger system that enables secure and transparent data transactions), data catalogues (a metadata repository that provides information on available data sources), data virtualization (a technique that allows accessing data from different sources without moving it)[ ^1 ^][ ^2 ^][ ^5 ^].

Source: Conversation with Bing, 3/9/2023
1. AIS Electronic Library (AISeL) - ICIS 2021 Proceedings: Enhancing Inter .... https://aisel.aisnet.org/icis2021/governance/governance/7/ Accessed 3/9/2023.
2. (PDF) Enhancing Inter-Organizational Data Governance via Blockchain .... https://www.researchgate.net/publication/355206665_Enhancing_Inter-Organizational_Data_Governance_via_Blockchain_-_Shaping_Scopes_and_Research_Avenues Accessed 3/9/2023.
3. Inter-Organizational Data Governance: A Literature Review. https://www.researchgate.net/publication/352257536_Inter-Organizational_Data_Governance_A_Literature_Review Accessed 3/9/2023.
4. INTER-ORGANIZATIONAL DATA GOVERNANCE: A LITERATURE REVIEW. https://aisel.aisnet.org/ecis2021_rp/57/ Accessed 3/9/2023.
5. Inter-Organizational Data Governance: a literature Review. https://www.semanticscholar.org/paper/Inter-Organizational-Data-Governance%3A-a-literature-Jagals-Karger/55bc07752a96a0d67868ed8f5e23d9c5f871b10f Accessed 3/9/2023.

 

## IODG (Emerging trends / innovations)
 

- Data quality extended into customer journeys and insights delivery: This trend involves ensuring that data is accurate, consistent, reliable etc. not only for internal use cases but also for external ones such as delivering personalised experiences and insights to customers¹.
- Data governance for digital business: This trend involves scaling data governance to cope with the increasing volume, velocity, variety etc. of data generated by digital transformation initiatives such as cloud migration, artificial intelligence etc.².
- Data governance by machines: This trend involves leveraging automation and machine learning to perform data governance tasks such as data discovery, classification, quality assessment etc. more efficiently and effectively².
- Data governance for inter-organizational networks: This trend involves developing new models and mechanisms for data governance that can accommodate the complexity and diversity of data sharing among multiple organisations with different interests and objectives³.

Source: Conversation with Bing, 3/9/2023
1. Five Data Governance Trends for Organizational ... - DATAVERSITY. https://www.dataversity.net/five-data-governance-trends-for-organizational-transformation-in-2022/ Accessed 3/9/2023.
2. Responding to Innovations and Trends in Data Governance. https://www.dataversity.net/responding-to-innovations-and-trends-in-data-governance/ Accessed 3/9/2023.
3. Inter-Organizational Data Governance: A Literature Review. https://www.researchgate.net/publication/352257536_Inter-Organizational_Data_Governance_A_Literature_Review Accessed 3/9/2023.

 

## Technologies and standards that support IODG

 
- Data discovery and inventory tools: These tools help identify and catalogue data sources across organisational boundaries, track data lineage and movement, and provide metadata information such as data quality, ownership, usage etc.³.
- Data integration and virtualization tools: These tools help access and combine data from different sources without moving or copying it, enabling faster and easier data sharing among partners³.
- Blockchain technology: This technology helps create a distributed ledger system that enables secure and transparent data transactions among multiple parties, ensuring data integrity, provenance, and trust².
- Data governance frameworks and policies: These frameworks and policies help define the roles, responsibilities, rules, standards etc. for managing data quality, security, privacy etc. across organisational boundaries¹³.
- Data governance platforms: These platforms help automate and orchestrate data governance processes such as data discovery, classification, quality assessment, policy enforcement, issue resolution etc.[ ^3 ^].

Source: Conversation with Bing, 3/9/2023
1. Mastering Data Governance Best Practices & Common Challenges. https://www.informatica.com/resources/articles/data-governance-best-practices-and-challenges.html Accessed 3/9/2023.
2. Inter-Organizational Data Governance: A Literature Review. https://www.researchgate.net/publication/352257536_Inter-Organizational_Data_Governance_A_Literature_Review Accessed 3/9/2023.
3. Designing data governance that delivers value | McKinsey. https://www.mckinsey.com/capabilities/mckinsey-digital/our-insights/designing-data-governance-that-delivers-value Accessed 3/9/2023.

 

 
## Data virtualization & integration examples

 
- TIBCO Data Virtualization: This tool helps access and combine data from various sources using a unified interface and a common data model¹².
- Denodo: This tool helps create a logical data layer that abstracts data from different sources and provides a consistent view to users²³.
- Informatica Data Integration: This tool helps integrate data from different sources using a graphical interface and a codeless environment[^2 ^][ ^3 ^].
- IBM Cloud Pak for Data: This tool helps connect and query data from different sources using a cloud-based platform and an SQL engine[^2 ^][ ^3 ^].
- Red Hat JBoss Data Virtualization: This tool helps federate data from different sources using a middleware solution and an open source framework[^2 ^][ ^3 ^].

Source: Conversation with Bing, 3/9/2023
1. Top 10 Data Virtualization Tools in 2023 - Hevo Data. https://hevodata.com/learn/data-virtualization-tools/ Accessed 3/9/2023.
2. Top 20 Data Virtualization Tools of 2023: In-Depth Guide - AIMultiple. https://aimultiple.com/data-virtualization-tools Accessed 3/9/2023.
3. Data Virtualization Explained | AltexSoft. https://www.altexsoft.com/blog/data-virtualization/ Accessed 3/9/2023.

 


## Blockchain for  IODG (+ examples)


- Enabling secure and transparent data transactions among multiple parties, ensuring data integrity, provenance, and trust¹².
- Providing a decentralized and distributed data platform that reduces the need for intermediaries and central authorities[^1 ^][ ^2 ^][ ^3 ^].
- Supporting smart contracts that can automate data governance processes such as data access, quality, security, privacy etc.[^1 ^][ ^2 ^][ ^3 ^].

Examples

- HealthChain: This is a blockchain-based platform that enables secure and efficient data sharing among healthcare organisations such as hospitals, clinics, pharmacies etc.¹².
- TradeLens: This is a blockchain-based platform that enables transparent and traceable data exchange among supply chain partners such as shippers, carriers, customs etc.¹².
- Datarella: This is a blockchain-based platform that enables collaborative data analytics among different organisations such as banks, insurers, retailers etc.[^1 ^][ ^2 ^].

Source: Conversation with Bing, 3/9/2023
1. (PDF) Enhancing Inter-Organizational Data Governance via Blockchain .... https://www.researchgate.net/publication/355206665_Enhancing_Inter-Organizational_Data_Governance_via_Blockchain_-_Shaping_Scopes_and_Research_Avenues Accessed 3/9/2023.
2. AIS Electronic Library (AISeL) - ICIS 2021 Proceedings: Enhancing Inter .... https://aisel.aisnet.org/icis2021/governance/governance/7/ Accessed 3/9/2023.
3. Blockchain Governance—A New Way of Organizing Collaborations? - INFORMS. https://pubsonline.informs.org/doi/10.1287/orsc.2020.1379 Accessed 3/9/2023.

 
 ## Open blackchain offerings

- Hyperledger: This is an open source project that provides a variety of blockchain frameworks and tools for different use cases and industries¹².
- Ethereum: This is an open source platform that supports smart contracts and decentralized applications on a global blockchain network[^1 ^][ ^2 ^].
- ISO/TC 307: This is a technical committee that develops international standards for blockchain and distributed ledger technologies[^2 ^][ ^3 ^].
- IEEE P2418.5: This is a working group that develops standards for governance of blockchain systems[^2 ^][ ^3 ^].

Source: Conversation with Bing, 3/9/2023
1. (PDF) Enhancing Inter-Organizational Data Governance via Blockchain .... https://www.researchgate.net/publication/355206665_Enhancing_Inter-Organizational_Data_Governance_via_Blockchain_-_Shaping_Scopes_and_Research_Avenues Accessed 3/9/2023.
2. Blockchain standards | Shaping Europe’s digital future. https://digital-strategy.ec.europa.eu/en/policies/blockchain-standards Accessed 3/9/2023.
3. Enhancing Inter-Organizational Data Governance via Blockchain – Shaping .... https://www.researchgate.net/profile/Erik-Karger/publication/355206665_Enhancing_Inter-Organizational_Data_Governance_via_Blockchain_-_Shaping_Scopes_and_Research_Avenues/links/616835ec3851f9599403bd9b/Enhancing-Inter-Organizational-Data-Governance-via-Blockchain-Shaping-Scopes-and-Research-Avenues.pdf Accessed 3/9/2023.

