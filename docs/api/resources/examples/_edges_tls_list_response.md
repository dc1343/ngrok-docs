<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"tls_edges": [
		{
			"backend": null,
			"created_at": "2025-02-20T10:07:22Z",
			"description": "acme tls edge",
			"hostports": ["example.com:443"],
			"id": "edgtls_2tIiZGqCGAFT3D6836J79Z4cbQ7",
			"ip_restriction": null,
			"metadata": "{\"environment\": \"staging\"}",
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2tIiZGqCGAFT3D6836J79Z4cbQ7"
		},
		{
			"backend": {
				"backend": {
					"id": "bkdhr_2tIiXz0MfBgZrcfh1AwFHnhC0dR",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2tIiXz0MfBgZrcfh1AwFHnhC0dR"
				},
				"enabled": true
			},
			"created_at": "2025-02-20T10:07:12Z",
			"description": "acme tls edge",
			"hostports": ["endpoint-example2.com:443"],
			"id": "edgtls_2tIiY0k5zc4HwfQSWJcFjyyANvR",
			"ip_restriction": null,
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2tIiY0k5zc4HwfQSWJcFjyyANvR"
		}
	],
	"uri": "https://api.ngrok.com/edges/tls"
}
```
