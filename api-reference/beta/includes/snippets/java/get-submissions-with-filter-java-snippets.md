---
description: "Automatically generated file. DO NOT MODIFY"
---

```java

GraphServiceClient graphClient = GraphServiceClient.builder().authenticationProvider( authProvider ).buildClient();

EducationSubmissionCollectionPage submissions = graphClient.education().classes("37d99af7-cfc5-4e3b-8566-f7d40e4a2070").assignments("a3cce0ba-2008-4c4d-bf62-079408562d96").submissions()
	.buildRequest()
	.filter("id eq 'ff2c7fe6-91cd-57a4-aa62-5b9c6b73222a'")
	.get();

```