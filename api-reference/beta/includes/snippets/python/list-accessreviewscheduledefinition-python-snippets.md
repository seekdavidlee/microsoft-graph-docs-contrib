---
description: "Automatically generated file. DO NOT MODIFY"
---

```python



graph_client = GraphServiceClient(credentials, scopes)

query_params = DefinitionsRequestBuilder.DefinitionsRequestBuilderGetQueryParameters(
		top = 100,
		skip = 0,
)

request_configuration = DefinitionsRequestBuilder.DefinitionsRequestBuilderGetRequestConfiguration(
query_parameters = query_params,
)

result = await graph_client.identity_governance.access_reviews.definitions.get(request_configuration = request_configuration)


```