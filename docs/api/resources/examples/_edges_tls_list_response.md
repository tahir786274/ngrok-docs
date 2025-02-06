<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"tls_edges": [
		{
			"backend": null,
			"created_at": "2025-02-06T10:07:40Z",
			"description": "acme tls edge",
			"hostports": ["example.com:443"],
			"id": "edgtls_2sfAsJErUQL0D3X2VbhwOeXdc50",
			"ip_restriction": null,
			"metadata": "{\"environment\": \"staging\"}",
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2sfAsJErUQL0D3X2VbhwOeXdc50"
		},
		{
			"backend": {
				"backend": {
					"id": "bkdhr_2sfAqu51WYAF6QaHKouRAtOcrqE",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2sfAqu51WYAF6QaHKouRAtOcrqE"
				},
				"enabled": true
			},
			"created_at": "2025-02-06T10:07:29Z",
			"description": "acme tls edge",
			"hostports": ["endpoint-example2.com:443"],
			"id": "edgtls_2sfAqwfNdAy0LpCJat7BtI7objS",
			"ip_restriction": null,
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2sfAqwfNdAy0LpCJat7BtI7objS"
		}
	],
	"uri": "https://api.ngrok.com/edges/tls"
}
```
