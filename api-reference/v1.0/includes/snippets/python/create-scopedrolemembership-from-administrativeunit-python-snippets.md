---
description: "Automatically generated file. DO NOT MODIFY"
---

```python



graph_client = GraphServiceClient(credentials, scopes)

request_body = ScopedRoleMembership(
	role_id = "roleId-value",
	role_member_info = Identity(
		id = "id-value",
	),
)

result = await graph_client.directory.administrative_units.by_administrative_unit_id('administrativeUnit-id').scoped_role_members.post(request_body)


```