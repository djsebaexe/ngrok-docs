<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"reserved_domains": [
		{
			"acme_challenge_cname_target": null,
			"certificate": null,
			"certificate_management_policy": {
				"authority": "letsencrypt",
				"private_key_type": "ecdsa"
			},
			"certificate_management_status": {
				"provisioning_job": {
					"error_code": null,
					"msg": "Managed certificate provisioning in progress.",
					"retries_at": null,
					"started_at": "2025-02-14T10:12:57Z"
				},
				"renews_at": null
			},
			"cname_target": "4knqktdwka2umyjjc.5pkjd647j7w7zury2.local-ngrok-cname.com",
			"created_at": "2025-02-14T10:12:57Z",
			"description": "Device 0001 Dashboard",
			"domain": "manage-0002.app.example.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2t1mVLyV4z3OehaeixspnQZ3Ntz",
			"metadata": "{\"service\": \"dashboard\"}",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2t1mVLyV4z3OehaeixspnQZ3Ntz"
		},
		{
			"acme_challenge_cname_target": null,
			"certificate": {
				"id": "cert_2t1mVJNG1QyzbdLTGyuhmt0grf4",
				"uri": "https://api.ngrok.com/tls_certificates/cert_2t1mVJNG1QyzbdLTGyuhmt0grf4"
			},
			"certificate_management_policy": null,
			"certificate_management_status": null,
			"cname_target": "2udamkamcl8pjmrff.5pkjd647j7w7zury2.local-ngrok-cname.com",
			"created_at": "2025-02-14T10:12:56Z",
			"domain": "myapp.mydomain.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2t1mVLh9k0o9PSs1jjz3KblfbNM",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2t1mVLh9k0o9PSs1jjz3KblfbNM"
		}
	],
	"uri": "https://api.ngrok.com/reserved_domains"
}
```
