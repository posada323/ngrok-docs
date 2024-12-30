<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"endpoints": [
		{
			"bindings": ["public"],
			"created_at": "2024-12-30T10:06:08Z",
			"hostport": "9e0dcb45ed57.ngrok.paid:443",
			"id": "ep_2qvpzrUzx10tpVXqwTurkEbaQqI",
			"name": "command_line",
			"principal": {
				"id": "usr_2qvpxPWNke9CzTvwI31umbNNmqG",
				"uri": ""
			},
			"proto": "https",
			"public_url": "https://9e0dcb45ed57.ngrok.paid",
			"tunnel": {
				"id": "tn_2qvpzrUzx10tpVXqwTurkEbaQqI",
				"uri": "https://api.ngrok.com/tunnels/tn_2qvpzrUzx10tpVXqwTurkEbaQqI"
			},
			"tunnel_session": {
				"id": "ts_2qvpzx2MwsRusF9Rrm4u9Slhnqm",
				"uri": "https://api.ngrok.com/tunnel_sessions/ts_2qvpzx2MwsRusF9Rrm4u9Slhnqm"
			},
			"type": "ephemeral",
			"updated_at": "2024-12-30T10:06:08Z",
			"upstream_url": "http://localhost:80",
			"url": "https://9e0dcb45ed57.ngrok.paid"
		},
		{
			"bindings": ["public"],
			"created_at": "2024-12-30T10:06:05Z",
			"domain": {
				"id": "rd_2qvpzRt5mmNnoUMWs6icGZh1aG6",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2qvpzRt5mmNnoUMWs6icGZh1aG6"
			},
			"edge": {
				"id": "edgtls_2qvpzQePfH6EoYRyQsa5XolOWSv",
				"uri": "https://api.ngrok.com/edges/tls/edgtls_2qvpzQePfH6EoYRyQsa5XolOWSv"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2qvpzRtYuMbN3xc36Few6rJQZQO",
			"proto": "tls",
			"public_url": "tls://endpoint-example2.com",
			"type": "edge",
			"updated_at": "2024-12-30T10:06:05Z"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/endpoints"
}
```
