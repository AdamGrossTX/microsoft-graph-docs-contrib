---
description: "Automatically generated file. DO NOT MODIFY"
---

```python



graph_client = GraphServiceClient(credentials, scopes)


await graph_client.devices.by_device_id('device-id').registered_owners.by_directory_object_id('directoryObject-id').ref.delete()


```