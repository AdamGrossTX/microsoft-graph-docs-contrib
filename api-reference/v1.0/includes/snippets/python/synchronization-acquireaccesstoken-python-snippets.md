---
description: "Automatically generated file. DO NOT MODIFY"
---

```python



graph_client = GraphServiceClient(credentials, scopes)

request_body = AcquireAccessTokenPostRequestBody(
	credentials = [
		SynchronizationSecretKeyStringValuePair(
			odata_type = "microsoft.graph.synchronizationSecretKeyStringValuePair",
		),
	],
)

await graph_client.applications.by_application_id('application-id').synchronization.acquire_access_token.post(request_body)


```