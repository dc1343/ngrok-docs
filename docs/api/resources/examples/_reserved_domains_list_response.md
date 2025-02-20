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
					"started_at": "2025-02-20T10:06:56Z"
				},
				"renews_at": null
			},
			"cname_target": "4knqktdwka2umyjjc.5bhpiyhz3qt6l9rpg.local-ngrok-cname.com",
			"created_at": "2025-02-20T10:06:56Z",
			"description": "Device 0001 Dashboard",
			"domain": "manage-0002.app.example.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2tIiW0a2ptc5WBc4y64HCj1jO0q",
			"metadata": "{\"service\": \"dashboard\"}",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2tIiW0a2ptc5WBc4y64HCj1jO0q"
		},
		{
			"acme_challenge_cname_target": null,
			"certificate": {
				"id": "cert_2tIiVz248ypIHqP8mq4bFDSsIuQ",
				"uri": "https://api.ngrok.com/tls_certificates/cert_2tIiVz248ypIHqP8mq4bFDSsIuQ"
			},
			"certificate_management_policy": null,
			"certificate_management_status": null,
			"cname_target": "2udamkamcl8pjmrff.5bhpiyhz3qt6l9rpg.local-ngrok-cname.com",
			"created_at": "2025-02-20T10:06:56Z",
			"domain": "myapp.mydomain.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2tIiVuthn99sz5wEdBBA196IK0R",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2tIiVuthn99sz5wEdBBA196IK0R"
		}
	],
	"uri": "https://api.ngrok.com/reserved_domains"
}
```
