---
description: "Automatically generated file. DO NOT MODIFY"
---

```python



graph_client = GraphServiceClient(credentials, scopes)

request_body = AuthorizationPolicy(
	allowed_to_use_s_s_p_r = True,
)

result = await graph_client.policies.authorization_policy.patch(request_body)


```