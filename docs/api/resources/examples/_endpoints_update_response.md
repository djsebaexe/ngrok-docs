<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"bindings": ["public"],
	"created_at": "2025-02-14T10:13:17Z",
	"description": "Sample Cloud Endpoint",
	"domain": {
		"id": "rd_2t1mXGLkEM6B5VKtDJhAKK8O3hC",
		"uri": "https://api.ngrok.com/reserved_domains/rd_2t1mXGLkEM6B5VKtDJhAKK8O3hC"
	},
	"hostport": "endpoint-example2.com:443",
	"id": "ep_2t1mXy2NAuSYDLZgQqv08qtSD4m",
	"metadata": "{\"environment\": \"staging\"}",
	"pooling_enabled": false,
	"proto": "https",
	"public_url": "https://endpoint-example2.com",
	"traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
	"type": "cloud",
	"updated_at": "2025-02-14T10:13:17Z",
	"uri": "https://api.ngrok.com/endpoints/ep_2t1mXy2NAuSYDLZgQqv08qtSD4m",
	"url": "https://endpoint-example2.com"
}
```
