---
description: "Automatically generated file. DO NOT MODIFY"
---

```python



graph_client = GraphServiceClient(credentials, scopes)

request_body = MailFolder(
	display_name = "displayName-value",
	is_hidden = True,
)

result = await graph_client.me.mail_folders.by_mail_folder_id('mailFolder-id').child_folders.post(request_body)


```