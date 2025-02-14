<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"endpoints": [
		{
			"bindings": ["public"],
			"created_at": "2025-02-14T10:13:17Z",
			"description": "sample cloud endpoint",
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
		},
		{
			"bindings": ["public"],
			"created_at": "2025-02-14T10:13:16Z",
			"hostport": "b1605ab8cad4.ngrok.paid:443",
			"id": "ep_2t1mXn5YUpnmtJ5OWpOaJweEPJW",
			"name": "command_line",
			"pooling_enabled": false,
			"principal": {
				"id": "usr_2t1mVEEEJU0qVKeQe77vt4yNqaq",
				"uri": ""
			},
			"proto": "https",
			"public_url": "https://b1605ab8cad4.ngrok.paid",
			"tunnel": {
				"id": "tn_2t1mXn5YUpnmtJ5OWpOaJweEPJW",
				"uri": "https://api.ngrok.com/tunnels/tn_2t1mXn5YUpnmtJ5OWpOaJweEPJW"
			},
			"tunnel_session": {
				"id": "ts_2t1mXoYkhiVg5ZhhIqQKZiHtsI6",
				"uri": "https://api.ngrok.com/tunnel_sessions/ts_2t1mXoYkhiVg5ZhhIqQKZiHtsI6"
			},
			"type": "ephemeral",
			"updated_at": "2025-02-14T10:13:16Z",
			"upstream_url": "http://localhost:80",
			"url": "https://b1605ab8cad4.ngrok.paid"
		},
		{
			"bindings": ["public"],
			"created_at": "2025-02-14T10:13:13Z",
			"domain": {
				"id": "rd_2t1mXGLkEM6B5VKtDJhAKK8O3hC",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2t1mXGLkEM6B5VKtDJhAKK8O3hC"
			},
			"edge": {
				"id": "edgtls_2t1mXG2tnQ50hpWGBAkt5YWggl0",
				"uri": "https://api.ngrok.com/edges/tls/edgtls_2t1mXG2tnQ50hpWGBAkt5YWggl0"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2t1mXKbpqR2rErq6eGTO7O1Hllr",
			"pooling_enabled": false,
			"proto": "tls",
			"public_url": "tls://endpoint-example2.com",
			"type": "edge",
			"updated_at": "2025-02-14T10:13:13Z"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/endpoints"
}
```
