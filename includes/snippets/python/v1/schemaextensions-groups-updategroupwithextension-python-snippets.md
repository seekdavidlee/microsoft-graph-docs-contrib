---
description: "Automatically generated file. DO NOT MODIFY"
---

```python



graph_client = GraphServiceClient(credentials, scopes)

request_body = Group(
	additional_data = {
			"graphlearn_courses" : {
					"course_id" : "123",
					"course_name" : "New Managers",
					"course_type" : "Online",
			},
	}
)

result = await graph_client.groups.by_group_id('group-id').patch(request_body)


```