# Naming Conventions

## GitHub

### Repository Names

#### Format
GitHub repository names will have the following format:

> lms-{servicetype}-{servicename}

> lms-{servicetype}-{subsystemname}-{servicename}

> lms-{servicetype}-{boundedcontextname}-{servicename}

##### Service Type
| Service Type | Description
| :---: | :---
| api | REST, SOAP, or other RPC based service
| svc | Service running in the background
| www | Web-based presentation services****

#### Rules
- Use all lowercase letters
- Every repository must have the "lms-" prefix
- Use hyphen as delimeter

#### Examples
| Service Name | Repository Name
| :--- | :---
| Admin Client | lms-www-administration
| Scheduler API | lms-api-scheduler
| Configuration API | lms-api-configuration
| Report Data Extraction Service | lms-svc-reporting-dataextraction
