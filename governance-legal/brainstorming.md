# Early Brainstorming
Initiated: 28.02.2023


## 1. Can we say that data exchange is a sub-set of the data governance problem? 
   - To answer this question, we need to provide functional definitions of the elements of each and compare to see if all the elements of data exchange are parts of the data governance problem. Below I will include the text I got from a paper about data governance (it is not a definition, but lists sub-points) and below it I will add the definition of interorganizational data sharing from my 

### Data Governance
* Elements of Data Governance (Abraham, et al., 2019)
	* Cross-functional data management (\checkmark)
	* Framework (policy / organizational process)
	* Data as strategice enterprise asset (\checkmark)
	* Decision rights and accountabilities (policy / organizational process)
	* Data policies, standards, and procedures (policy / organizational process)
	* Compliance monitoring (policy, but helped by the Basin Network structure \checkmark)
* Conceptual framework for data governance (Abraham, et al., 2019)
	* Data Scope: heterogenous data (\checkmark)
	* Domain Scope
		* Data quality (via meta-data \checkmark), Data security (not covered), Data architecture (\checkmark), Data lifecycle (\checkmark), Meta-data (\checkmark), Data Storage & infrastructure (not covered)
    * Organizational scope
	    * Intra- & inter-organizational scope (\checkmark)

### Data exchange 
Interorganizational Data Management and Exchange (IoDME) is when we have[^1]:
1. A variable set of participating organizations with disjoint legal/privacy scopes, with
2. Heterogeneous technologies, infrastructures, and data asset formats,
3. Varying conventions and declarative knowledge (know-what),
   - Ex., Data asset description, lineage, quality, schema, usage rights
4. Finely customizable data asset exchange configurations.

## 2. Data exchange scopes: what are the different scopes of data excahnge and how are they related, similar, or different?
   - Data exchange across territories with different laws and regulations.
   - Data exchange across two legal entities within on territory
   - Data exchange within two sub-divisions within and single legal entity

## 3. Subject access: what are its challenges?
"Simmons + Simmons" define it[^2] as: "advise on developing strategies for responding to subject access requests as well as assisting in dealing with the requests themselves, sometimes also in the context of litigation"

_TODO:_ Expand on this description and make it more precise.

## 4. Transactions: what are their challenges?
"Simmons + Simmons" define it[^2] as: "dealing with data protection issues associated with corporate transactions (eg in relation to due diligence disclosure or transfer of data as an asset) and outsourcing transaction"

_TODO:_ Expand on this description and make it more precise.

## 5. ChatGPT on the topic


**Prompt**: You are a researcher and a CTO with a phd in applied computer science studying the intersection between data management and the legal issues of data management and exchange, including topics such as governance, what are current promising applied research questions on the intersection between data exchange and law/governance

**ChatGPT Response:**

There are many promising applied research questions at the intersection between data exchange and law/governance. Here are some examples:

1. How can data governance frameworks be designed to ensure compliance with data protection laws such as GDPR, CCPA, and HIPAA? What are the key challenges in implementing these frameworks, and how can they be addressed?

2. How can data sharing agreements be designed to protect the rights of individuals and organizations while enabling the benefits of data sharing? What legal and technical mechanisms can be used to enforce these agreements?

3. What are the legal and ethical implications of using artificial intelligence (AI) and machine learning (ML) algorithms to make decisions about individuals or groups? How can these algorithms be made transparent and accountable to ensure fairness and avoid discrimination?

4. How can blockchain technology be used to enhance data security, privacy, and accountability in data exchange? What are the legal and regulatory challenges associated with blockchain-based data management systems?

5. How can data management practices be designed to support international data transfer while respecting national data sovereignty laws and other legal requirements? What are the implications of these practices for data privacy, security, and governance?

6. What are the ethical and legal implications of using personal data for research purposes? How can researchers balance the benefits of using personal data with the need to protect the privacy and confidentiality of individuals?

7. How can data management practices be designed to support open science and data sharing while protecting the intellectual property rights of researchers and organizations? What are the legal and technical mechanisms that can be used to achieve this balance?

8. How can data management practices be designed to support data-driven innovation while ensuring that the benefits of this innovation are distributed fairly across society? What legal and policy frameworks are needed to achieve this goal?

**Prompt:** One of the responses above about the intersection between data exchange and legal issues you mentioned the following point:

How can data management practices be designed to support international data transfer while respecting national data sovereignty laws and other legal requirements? What are the implications of these practices for data privacy, security, and governance?
Can you elaborate further with some 

There are several publications that discuss the intersection of science and law with a focus on data privacy. Here are a few examples:

Science and Technology Law Review: This peer-reviewed journal explores the intersection of science, technology, and the law. It covers a broad range of topics related to data privacy, including cybersecurity, data breaches, and privacy laws.

Journal of Law and the Biosciences: This interdisciplinary journal explores the ethical, legal, and social implications of advances in the life sciences and related fields, including data privacy. It covers a range of topics, including genetic privacy, health information privacy, and data protection.

Harvard Journal of Law & Technology: This student-run journal focuses on the intersection of law, technology, and society. It covers a range of topics related to data privacy, including cybersecurity, data protection, and privacy laws.

International Data Privacy Law: This journal focuses specifically on data privacy and the legal implications of data protection. It covers a broad range of topics related to data privacy, including the regulation of personal data, data protection laws, and privacy by design.

Communications of the ACM: This magazine covers the latest developments in computer science, information technology, and their applications. It often features articles related to data privacy, including data breaches, cybersecurity, and privacy laws.

IEEE Security & Privacy Magazine: This magazine focuses on the latest developments in computer security and privacy. It covers a range of topics related to data privacy, including data breaches, encryption, and privacy laws.

Data Protection Leader: This publication focuses on data protection and data privacy. It covers a range of topics related to data privacy, including the General Data Protection Regulation (GDPR), data breaches, and privacy laws.

**Response:**

cited examples?

Sure! Here are some examples of how data management practices can be designed to support international data transfer while respecting national data sovereignty laws and other legal requirements:

1. Data localization: Some countries require that data be stored and processed within their borders to ensure compliance with their data sovereignty laws. Data localization can be achieved by setting up data centers within the country's borders or using cloud providers that have data centers located within the country. For example, Russia has a law that requires companies to store personal data of Russian citizens within Russia, and Amazon Web Services (AWS) has set up a data center in Moscow to comply with this law.

2. Cross-border data transfer agreements: To transfer data across borders, companies can enter into agreements with the countries involved to ensure compliance with local laws and regulations. For example, the European Union's General Data Protection Regulation (GDPR) allows for the transfer of personal data to countries outside the EU if those countries have adequate data protection laws in place. The EU has also entered into adequacy agreements with certain countries, such as Canada and Japan, to facilitate data transfers between those countries and the EU.

3. Data anonymization: Anonymizing data can help to protect data privacy while still allowing for the transfer of data across borders. By removing personally identifiable information from the data, companies can ensure that the data does not fall under the jurisdiction of local data sovereignty laws. For example, the International Cancer Genome Consortium (ICGC) anonymizes genetic and clinical data from cancer patients to enable global data sharing while protecting patient privacy.

4. Encryption: Encryption can be used to protect data security during cross-border data transfers. By encrypting the data, companies can ensure that it remains secure even if it is intercepted during transmission. For example, some companies use end-to-end encryption to secure communication between their data centers located in different countries.

These data management practices have implications for data privacy, security, and governance. For example, data localization can help to ensure compliance with local data sovereignty laws but may limit the ability of companies to leverage global data centers and cloud providers. Anonymization and encryption can help to protect data privacy and security but may limit the usefulness of the data for certain purposes. Cross-border data transfer agreements can facilitate data sharing but may be subject to changing political and legal landscapes. Therefore, it is important to carefully consider the implications of these practices for data privacy, security, and governance when designing data management strategies for international data transfer.



**Prompt:** Another point that was mentioned above was the following:

How can data sharing agreements be designed to protect the rights of individuals and organizations while enabling the benefits of data sharing? What legal and technical mechanisms can be used to enforce these agreements?

Can you elaborate further on this point with giving some examples of technical or legal approaches for this problem?

**Response:**

Sure, here are some examples of technical and legal mechanisms that can be used to protect the rights of individuals and organizations while enabling the benefits of data sharing:

- Data use agreements: Data use agreements are legal documents that outline the terms and conditions under which data can be accessed and used. These agreements typically include provisions for data privacy and security, restrictions on data use and sharing, and procedures for resolving disputes. By specifying the conditions under which data can be used and shared, data use agreements can help to protect the rights of individuals and organizations. For example, the National Institutes of Health (NIH) requires data use agreements for access to its genomic data repository.

- Data access controls: Data access controls are technical mechanisms that restrict access to data based on the user's identity, role, or other criteria. Access controls can be used to enforce data use agreements by ensuring that only authorized users are able to access the data. For example, electronic health record systems use access controls to restrict access to patient health information to authorized healthcare providers.

- Data masking and de-identification: Data masking and de-identification are technical mechanisms that can be used to protect the privacy of individuals in shared data sets. Data masking involves replacing sensitive data with fictional data, while de-identification involves removing identifying information from the data set. By masking or de-identifying sensitive data, organizations can protect the privacy of individuals while still enabling the benefits of data sharing. For example, the Centers for Medicare and Medicaid Services (CMS) use de-identification techniques to protect the privacy of beneficiaries in publicly available Medicare claims data.

- Legal sanctions: Legal sanctions can be used to enforce data use agreements and protect the rights of individuals and organizations. For example, the GDPR includes provisions for fines and penalties for organizations that violate its data protection requirements. Similarly, the Health Insurance Portability and Accountability Act (HIPAA) includes provisions for fines and penalties for healthcare providers that violate its privacy and security requirements.

These mechanisms can be used in combination to protect the rights of individuals and organizations while enabling the benefits of data sharing. For example, data use agreements can be used to specify the terms and conditions of data sharing, while access controls and data masking can be used to enforce those agreements and protect the privacy of individuals. Legal sanctions can be used as a last resort to enforce data use agreements and protect the rights of individuals and organizations.



## 6. What usage licenses are out there for data/datasets? 

Some seem to borrow from software licenses and produce derivative ones. See for example the definition of open data (http://opendefinition.org/od/2.1/en/) produced by the open knowledge foundation, which is influenced by open-source software licenses.

ChatGPT on the topic:

[Following up in the same session as the prompt shown above] **Prompt**:  What usage licenses are out there for data. as opposed to software?

**Response:**

There are several types of usage licenses for data that are used to govern the use, distribution, and sharing of data. Here are some examples:

1. Creative Commons licenses: Creative Commons licenses are a set of standardized licenses that allow content creators to easily share and manage their work. There are six main types of Creative Commons licenses, each of which allows different levels of use and sharing. The licenses are used for all types of content, including data.

2. Open Data Commons licenses: The Open Data Commons provides a set of legal tools for sharing and using open data. These tools include a set of licenses that are designed specifically for data, such as the Open Database License (ODbL) and the Public Domain Dedication and License (PDDL).

3. Database-specific licenses: Some databases have their own licenses that govern the use and distribution of their data. For example, the OpenStreetMap project has its own license that governs the use of its geographic data.

4. Vendor-specific licenses: Some vendors or providers of data may have their own licensing agreements that govern the use and distribution of their data. These licenses may be proprietary and restrict the use of the data to certain applications or industries.

5. Government-specific licenses: Many governments have their own open data policies and licenses that govern the use and distribution of government data. For example, the US government has its own set of open data policies and licenses that apply to federal government data.

6. Custom licenses: Organizations or individuals may choose to create their own custom licenses that govern the use and distribution of their data. These licenses may be tailored to specific use cases or industries.



**Prompt:** Can you give me a list of examples of such data usage licenses 

**Response:**

Sure, here are some examples of data usage licenses:

1. Creative Commons licenses: CC0, CC-BY, CC-BY-SA, CC-BY-ND, CC-BY-NC, CC-BY-NC-SA, CC-BY-NC-ND.
2.  Open Data Commons licenses: ODbL, PDDL.

3. Database-specific licenses: OpenStreetMap License, Open Database License (ODbL), Open Government License.
4. Vendor-specific licenses: Google Maps Platform License, Amazon Web Services License, Microsoft Azure Data Share License.

5. Government-specific licenses: Open Government License (UK), Public Sector Information License (EU), United States Government Open Data License.

6. Custom licenses: Research Data Alliance (RDA) Sharing and Reuse Principles, Data Use Agreement (DUA), Data Sharing Agreement (DSA).

It is important to note that this is not an exhaustive list, and there may be other licenses available depending on the specific use case and industry. It is also worth noting that some licenses, such as the OpenStreetMap License and the ODbL, have been specifically designed for databases and data, while others, such as the Creative Commons licenses, are more general and can be used for various types of content.


**Prompt:** What software licenses have been used as data usage licenses

**Response:** 

While software licenses are not specifically designed for data usage, some software licenses have been used for data as well. Here are a few examples:

1. GNU General Public License (GPL): The GPL is a popular open source software license that has also been used for data. For example, the OpenStreetMap project uses the GPL to license its data.

2. Apache License: The Apache License is another open source software license that has been used for data. For example, the Open Data Kit project uses the Apache License to license its mobile data collection tools and associated data formats.

3. MIT License: The MIT License is a permissive software license that allows for the use, modification, and distribution of software. It has also been used for data. For example, the DataONE project uses the MIT License to license its data management tools and associated metadata standards.

It is worth noting that using a software license for data is not ideal, as software licenses are designed for code and may not be well-suited to the complexities of data usage and sharing. Therefore, it is recommended to use a license that is specifically designed for data, such as those mentioned in my previous response.



## References
* R. Abraham, et al. (2019). Data governance: A conceptual framework, structured review, and research agenda. International Journal of Information Management, 49, 424-438.

[^1]: From the Phd thesis of @nskss (_in press_, 2023).
[^2]: The firm "Simmons + Simmons" [identifies](https://www.simmons-simmons.com/en/expertise/service/data-protection-and-privacy) several sub-problems related to data protection and privacy: data security, employees, freedom of information, interception of communications
advising businesses on compliant monitoring and recording of communications, **subject access**, **transactions**, marketing. We focus on the bolded ones here.
