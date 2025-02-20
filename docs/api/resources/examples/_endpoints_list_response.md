<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"endpoints": [
		{
			"bindings": ["public"],
			"created_at": "2025-02-20T10:07:17Z",
			"description": "sample cloud endpoint",
			"domain": {
				"id": "rd_2tIiY1v9qE6aXPBSLi5xCAG5n9s",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2tIiY1v9qE6aXPBSLi5xCAG5n9s"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2tIiYdVhnrs5a8RP35IndytO6iy",
			"metadata": "{\"environment\": \"staging\"}",
			"pooling_enabled": false,
			"proto": "https",
			"public_url": "https://endpoint-example2.com",
			"traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
			"type": "cloud",
			"updated_at": "2025-02-20T10:07:17Z",
			"uri": "https://api.ngrok.com/endpoints/ep_2tIiYdVhnrs5a8RP35IndytO6iy",
			"url": "https://endpoint-example2.com"
		},
		{
			"bindings": ["public"],
			"created_at": "2025-02-20T10:07:15Z",
			"hostport": "0c053cb881f4.ngrok.paid:443",
			"id": "ep_2tIiYMgP5Whf4fT35JzriUAm6iy",
			"name": "command_line",
			"pooling_enabled": false,
			"principal": {
				"id": "usr_2tIiVuwSsN7nOu6ectHFwVWpGaA",
				"uri": ""
			},
			"proto": "https",
			"public_url": "https://0c053cb881f4.ngrok.paid",
			"tunnel": {
				"id": "tn_2tIiYMgP5Whf4fT35JzriUAm6iy",
				"uri": "https://api.ngrok.com/tunnels/tn_2tIiYMgP5Whf4fT35JzriUAm6iy"
			},
			"tunnel_session": {
				"id": "ts_2tIiYJ6EJsIJdletnwvS50ikw7I",
				"uri": "https://api.ngrok.com/tunnel_sessions/ts_2tIiYJ6EJsIJdletnwvS50ikw7I"
			},
			"type": "ephemeral",
			"updated_at": "2025-02-20T10:07:15Z",
			"upstream_url": "http://localhost:80",
			"url": "https://0c053cb881f4.ngrok.paid"
		},
		{
			"bindings": ["public"],
			"created_at": "2025-02-20T10:07:12Z",
			"domain": {
				"id": "rd_2tIiY1v9qE6aXPBSLi5xCAG5n9s",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2tIiY1v9qE6aXPBSLi5xCAG5n9s"
			},
			"edge": {
				"id": "edgtls_2tIiY0k5zc4HwfQSWJcFjyyANvR",
				"uri": "https://api.ngrok.com/edges/tls/edgtls_2tIiY0k5zc4HwfQSWJcFjyyANvR"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2tIiY0siNNZWh4wcqtD8CkfjgIx",
			"pooling_enabled": false,
			"proto": "tls",
			"public_url": "tls://endpoint-example2.com",
			"type": "edge",
			"updated_at": "2025-02-20T10:07:12Z"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/endpoints"
}
```
