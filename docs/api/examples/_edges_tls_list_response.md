<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"tls_edges": [
		{
			"backend": null,
			"created_at": "2024-12-30T10:06:16Z",
			"description": "acme tls edge",
			"hostports": ["example.com:443"],
			"id": "edgtls_2qvq0wT0fIoXd6KSOLygT6mqMuv",
			"ip_restriction": null,
			"metadata": "{\"environment\": \"staging\"}",
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2qvq0wT0fIoXd6KSOLygT6mqMuv"
		},
		{
			"backend": {
				"backend": {
					"id": "bkdhr_2qvpzO06xyY8lYoZDpSK6dLwUJZ",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2qvpzO06xyY8lYoZDpSK6dLwUJZ"
				},
				"enabled": true
			},
			"created_at": "2024-12-30T10:06:04Z",
			"description": "acme tls edge",
			"hostports": ["endpoint-example2.com:443"],
			"id": "edgtls_2qvpzQePfH6EoYRyQsa5XolOWSv",
			"ip_restriction": null,
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2qvpzQePfH6EoYRyQsa5XolOWSv"
		}
	],
	"uri": "https://api.ngrok.com/edges/tls"
}
```
