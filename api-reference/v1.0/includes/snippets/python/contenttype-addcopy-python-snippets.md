---
description: "Automatically generated file. DO NOT MODIFY"
---

```python



graph_client = GraphServiceClient(credentials, scopes)

request_body = AddCopyPostRequestBody(
	content_type = "https://graph.microsoft.com/v1.0/sites/{site-id}/contentTypes/0x0101",
)

result = await graph_client.sites.by_site_id('site-id').lists.by_list_id('list-id').content_types.add_copy.post(request_body)


```