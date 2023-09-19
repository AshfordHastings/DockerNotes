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
