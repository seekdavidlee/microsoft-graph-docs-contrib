---
description: "Automatically generated file. DO NOT MODIFY"
---

```python



graph_client = GraphServiceClient(credentials, scopes)

query_params = GroupItemRequestBuilder.GroupItemRequestBuilderGetQueryParameters(
		select = ["*","parentSiteId"],
)

request_configuration = GroupItemRequestBuilder.GroupItemRequestBuilderGetRequestConfiguration(
query_parameters = query_params,
)

result = await graph_client.sites.by_site_id('site-id').term_store.groups.by_group_id('group-id').get(request_configuration = request_configuration)


```