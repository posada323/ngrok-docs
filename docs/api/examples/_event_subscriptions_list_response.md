<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"event_subscriptions": [
		{
			"created_at": "2024-12-30T10:06:12Z",
			"description": "ip policy creations",
			"destinations": [
				{
					"id": "ed_2qvq0NYoGMGWFaiAqJ4gJAPFaKP",
					"uri": "https://api.ngrok.com/event_destinations/ed_2qvq0NYoGMGWFaiAqJ4gJAPFaKP"
				}
			],
			"id": "esb_2qvq0MrPMROm7HXxj7DDhCe9HQ0",
			"metadata": "{\"environment\": \"staging\"}",
			"sources": [
				{
					"type": "ip_policy_created.v0",
					"uri": "https://api.ngrok.com/event_subscriptions/esb_2qvq0MrPMROm7HXxj7DDhCe9HQ0/sources/ip_policy_created.v0"
				}
			],
			"uri": "https://api.ngrok.com/event_subscriptions/esb_2qvq0MrPMROm7HXxj7DDhCe9HQ0"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/event_subscriptions"
}
```
