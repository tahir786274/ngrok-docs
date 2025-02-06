<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"endpoints": [
		{
			"bindings": ["public"],
			"created_at": "2025-02-06T10:07:34Z",
			"description": "sample cloud endpoint",
			"domain": {
				"id": "rd_2sfAqwbPEDGDDfuTRrMPyb2JGbt",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2sfAqwbPEDGDDfuTRrMPyb2JGbt"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2sfArVxwfsLasGipbVjgMCf2UTK",
			"metadata": "{\"environment\": \"staging\"}",
			"pooling_enabled": false,
			"proto": "https",
			"public_url": "https://endpoint-example2.com",
			"traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
			"type": "cloud",
			"updated_at": "2025-02-06T10:07:34Z",
			"uri": "https://api.ngrok.com/endpoints/ep_2sfArVxwfsLasGipbVjgMCf2UTK",
			"url": "https://endpoint-example2.com"
		},
		{
			"bindings": ["public"],
			"created_at": "2025-02-06T10:07:33Z",
			"hostport": "610d81879532.ngrok.paid:443",
			"id": "ep_2sfArTCvyysec90nGHUnSshT3Hi",
			"name": "command_line",
			"pooling_enabled": false,
			"principal": {
				"id": "usr_2sfAosWukcyJficDYGPcBjNryeD",
				"uri": ""
			},
			"proto": "https",
			"public_url": "https://610d81879532.ngrok.paid",
			"tunnel": {
				"id": "tn_2sfArTCvyysec90nGHUnSshT3Hi",
				"uri": "https://api.ngrok.com/tunnels/tn_2sfArTCvyysec90nGHUnSshT3Hi"
			},
			"tunnel_session": {
				"id": "ts_2sfArVaGBn7b7PYJ3zMr3QZtKhG",
				"uri": "https://api.ngrok.com/tunnel_sessions/ts_2sfArVaGBn7b7PYJ3zMr3QZtKhG"
			},
			"type": "ephemeral",
			"updated_at": "2025-02-06T10:07:33Z",
			"upstream_url": "http://localhost:80",
			"url": "https://610d81879532.ngrok.paid"
		},
		{
			"bindings": ["public"],
			"created_at": "2025-02-06T10:07:30Z",
			"domain": {
				"id": "rd_2sfAqwbPEDGDDfuTRrMPyb2JGbt",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2sfAqwbPEDGDDfuTRrMPyb2JGbt"
			},
			"edge": {
				"id": "edgtls_2sfAqwfNdAy0LpCJat7BtI7objS",
				"uri": "https://api.ngrok.com/edges/tls/edgtls_2sfAqwfNdAy0LpCJat7BtI7objS"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2sfAqt7vuAnLr9VH6Ks6W0vebwJ",
			"pooling_enabled": false,
			"proto": "tls",
			"public_url": "tls://endpoint-example2.com",
			"type": "edge",
			"updated_at": "2025-02-06T10:07:30Z"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/endpoints"
}
```
