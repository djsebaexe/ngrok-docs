<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"tls_edges": [
		{
			"backend": null,
			"created_at": "2025-02-14T10:13:23Z",
			"description": "acme tls edge",
			"hostports": ["example.com:443"],
			"id": "edgtls_2t1mYfwBRypNbcBKJGR2nhBI4LL",
			"ip_restriction": null,
			"metadata": "{\"environment\": \"staging\"}",
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2t1mYfwBRypNbcBKJGR2nhBI4LL"
		},
		{
			"backend": {
				"backend": {
					"id": "bkdhr_2t1mXJpyIx40XNS3rbprUAIdfWz",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2t1mXJpyIx40XNS3rbprUAIdfWz"
				},
				"enabled": true
			},
			"created_at": "2025-02-14T10:13:12Z",
			"description": "acme tls edge",
			"hostports": ["endpoint-example2.com:443"],
			"id": "edgtls_2t1mXG2tnQ50hpWGBAkt5YWggl0",
			"ip_restriction": null,
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2t1mXG2tnQ50hpWGBAkt5YWggl0"
		}
	],
	"uri": "https://api.ngrok.com/edges/tls"
}
```
