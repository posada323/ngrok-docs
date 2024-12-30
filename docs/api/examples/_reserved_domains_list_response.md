<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"reserved_domains": [
		{
			"acme_challenge_cname_target": null,
			"certificate": {
				"id": "cert_2qvpxLRZbyTlY0Eou4nMkVJAkC0",
				"uri": "https://api.ngrok.com/tls_certificates/cert_2qvpxLRZbyTlY0Eou4nMkVJAkC0"
			},
			"certificate_management_policy": null,
			"certificate_management_status": null,
			"cname_target": "2udamkamcl8pjmrff.5awt2tvs3nvbr18cm.local-ngrok-cname.com",
			"created_at": "2024-12-30T10:05:48Z",
			"domain": "myapp.mydomain.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2qvpxXXmvKbTbD7srIIjjxruILk",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2qvpxXXmvKbTbD7srIIjjxruILk"
		},
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
					"started_at": "2024-12-30T10:05:49Z"
				},
				"renews_at": null
			},
			"cname_target": "4knqktdwka2umyjjc.5awt2tvs3nvbr18cm.local-ngrok-cname.com",
			"created_at": "2024-12-30T10:05:49Z",
			"description": "Device 0001 Dashboard",
			"domain": "manage-0002.app.example.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2qvpxXfLWibTynF5GMq8bLU5FIh",
			"metadata": "{\"service\": \"dashboard\"}",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2qvpxXfLWibTynF5GMq8bLU5FIh"
		}
	],
	"uri": "https://api.ngrok.com/reserved_domains"
}
```
