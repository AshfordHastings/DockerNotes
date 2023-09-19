Notes About Docker!
Objective Achieved: Migration from S3 to Azure Blob Storage
Key Achievements:
1 Enhanced ARIEL User Experience and Capabilities within the Platform
-Solved the issue of users leveraging ARIEL on Azure not being able to see their files through the ARIEL user interface. ARIEL Users will now be able to utilize completed services such as Orchard, TXT_AFR, and any proposed Azure based services without sacrificing UI interactions.
-And, conversely, users who seek to leverage the Orchard service's orchestration capabilities will be able to utilize on-prem services, OCR/ADI specifically, in their document ingestion / proessing pipelines. This has directly enabled the EZOps project and the ISS project's AML document use-case.
2 Infrastructure and Code Base Improvement
Modularized and refactored ARIEL's document ingestion / processing controller layer, TXT_IDC, during the migration process, to pave the way for crucial planned future initiatives. These modifications will help pave the way for:
Making TXT_IDC OpenAPI compliant and utilizing State Street's Apegee gateway
Migrating workflow triggering via object - collection addition to Azure Event Hub triggers, to further embrace cloud nativity and powerful features offered by Azure and the public cloud as a whole
Upgrading our communication protocol architecture between document processing services in such a flexible way that allows engineers to deliver new services quickly, efficiently, and gracefully
Implemented improved code base improvements specifically by:
Standardizing interactions for methods invoking object storage procedures, object path generation, and input validation
Separated business logic into a standardized, layered approach to meet State Street commitment to high quality engineering solutions, further allowing ease of code extension and clarity
3 Integrated Arca Package into TXT_IDC Design
Successfully modified and integrated the recently developed Arca package into TXT_IDC, choosing to take on further ownership of this component in the enhancement of our software design
The development and integration not only improved the design of TXT_IDC, but ensured adaptability of Arca to the various use cases and requirements in ARIEL artifact management.
Through this modification and integration, our team can ensure that ensure that our design is thought through, holistic, and comprehensive.


Objective Achieved: Streamlined ISS Deployment and Infrastructure Development

Key Achievements:
1 Technical Expertise and Problem Solving in Moving the ISS Project to Production
	-Played a pivotal role in resolving challenges for the ISS's transition to production, especially in areas of DevOps, CI/CD, Azure deployment, and more.
	-Developed a deep understanding of the CI/CD pipeline, becoming proficient in tools and technologies such as Cloakware, Azure Key Vault, Helm, environment variables, Kafka, Ingress, Kubernetes, and more. This knowledge was crucial in deploying ISS to production.
	-Owned several aspects of creating, standardizing, and troubleshooting our Azure DevOps piplines and Helm-based deployments to our Kubernetes cluster
2 Collaborated with Different Teams and Provided Leadership to My Own Team in Infrastructure Operations to Move the ISS Project to Production
	-Directed and assisted in scripting and establishing deployment pipelines for various ARIEL components including TXT_CAO, TXT_ASI, TXT_AFR, and TXT_IDC.
	-Guided the team in comprehending these pipelines and infrastructure designs
	-Collaborated closely with various teams, including the Platform Team, Kafka Team, Azure Team, allowing them to understanding ARIEL and the ISS project's exact requirements in moving to Azure and production
3 Ensured Project Delivery Deadlines and Meeting of Standards for the ISS Project
	-Successfully utilized new technologies and structures to transition the ISS project to production, meeting critical UAT/PROD milestones and deadlines.
	-Managed client expectations and implemented ARIEL infrastructure solutions accordingly 



Objective Achieved: Migration from S3 to Azure Blob Storage 
Key Achievements:
1 Enhanced ARIEL User Experience and Capabilities within the Platform
	-Solved the issue of users leveraging ARIEL on Azure not being able to see their files through the ARIEL user interface. ARIEL Users will now be able to utilize completed services such as Orchard, TXT_AFR, and any proposed Azure based services without sacrificing UI interactions.
	-And, conversely, users who seek to leverage the Orchard service's orchestration capabilities will be able to utilize on-prem services, OCR/ADI specifically, in their document ingestion / proessing pipelines. This has directly enabled the EZOps project and the ISS project's AML document use-case.
2 Infrastructure and Code Base Improvement
	Modularized and refactored ARIEL's document ingestion / processing controller layer, TXT_IDC, during the migration process, to pave the way for crucial planned future initiatives. These modifications will help pave the way for:
		Making TXT_IDC OpenAPI compliant and utilizing State Street's Apegee gateway
		Migrating workflow triggering via object - collection addition to Azure Event Hub triggers, to further embrace cloud nativity and powerful features offered by Azure and the public cloud as a whole
		Upgrading our communication protocol architecture between document processing services in such a flexible way that allows engineers to deliver new services quickly, efficiently, and gracefully 
	Implemented improved code base improvements specifically by:
		Standardizing interactions for methods invoking object storage procedures, object path generation, and input validation
		Separated business logic into a standardized, layered approach to meet State Street commitment to high quality engineering solutions, further allowing ease of code extension and clarity 
3 Integrated Arca Package into TXT_IDC Design
	Successfully modified and integrated the recently developed Arca package into TXT_IDC, choosing to take on further ownership of this component in the enhancement of our software design
	The development and integration not only improved the design of TXT_IDC, but ensured adaptability of Arca to the various use cases and requirements in ARIEL artifact management.
	Through this modification and integration, our team can ensure that ensure that our design is thought through, holistic, and comprehensive. 

Objective Achieved: Operationalized Azure Form Recognizer (AFR) Capability into ARIEL Document Processing Design
1 Enabled an Innovative Solution in ARIEL's Document Processing Offerings
	Integrated Azure Form Recognizer into ARIEL's design, capitalizing on one of the most cutting edge solutions offered by the technology market at this time
	Enabled opportunities for intelligent form-based data extraction and, importantly, handwritten document extraction in ARIEL, delivering exciting new capabilities for the platform 
	Opened the door for flexible, powerful combinations with other ARIEL offerings such as Advanced Spreadsheet Intelligence 
2 Equipped the Platform to Provide ISS Client with a Solution for Extraction and Transformation of FATCA Documents
	Introduced and implemented an ARIEL offering able tailored for the ISS client, enabling to extract handwritten data from FATCA documents, which was previously unattainable with past ARIEL offerings. 
	Demonstrated ownership of the ARIEL's Azure Form Recognizer capability in interacting with the ISS team in building them a tailored solution for their use-case
	Enabled ARIEL's Orchard offering to harness TXT_AFR in providing custom orchestration workflows for the ISS client, combining Ariel Spreadsheet Intelligence, and customizing the approach based on FATCA document type 
3 Adapted ARIEL Service Design for Public Cloud 
	Designed and deployed TXT_AFR with a modern, isolated service design leveraging Kubernetes and Docker, as opposed to the single deployment approach used in our private cloud services
	
	
Objective Achieved: Development and Deployment of Workflow Endpoints Essential for ISS Project Completion
1 Designed and Implemented User-Friendly Workflow Configuration Endpoints 
	Designed and developed secure workflow endpoints, empowering team members to efficiently modify, update, and manage configurations for various workflows.
	Endpoints were implemented with the user in mind - with schemed validations, pagination, error responses, and RESTful practices.
	These newly developed endpoints were instrumental in meeting the ISS project's deployment objectives.
2 Provided Critical Role in ISS Project's Success
	These endpoints were critical in assisting the team in meeting the requirements for the ISS project, ensuring that team members could update recipes, mapping files, and more post-production deployment and assuring their use in data pipelines. Their flexibility played a decisive role in meeting the ISS project's demanding requirements and deadlines.
3 Paved Way for Future Improvements to Orchestration Services
	In implementing these endpoints, I took further ownership of the Orchard orchestration component, by expanding Orchard's capabilities and design.
	The endpoints were conceptualized and implemented with a future-aligned approach, setting the foundation for an eventual transition to an OpenAPI compliant framework.
Initiated the development of features that would permit users to possess and alter configurations of their own workflows, a crucial step in furthering the design of a user-friendly workflow and workflow configuration editor in the UI, something very valuable for serving ARIEL users. ![image](https://github.com/AshfordHastings/DockerNotes/assets/33183721/f6b1b4d0-128b-4150-9580-12c8b72088f3)
