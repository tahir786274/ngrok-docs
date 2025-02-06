<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"event_subscriptions": [
		{
			"created_at": "2025-02-06T10:07:36Z",
			"description": "ip policy creations",
			"destinations": [
				{
					"id": "ed_2sfArmu7MWUUajauMOoEVbscbii",
					"uri": "https://api.ngrok.com/event_destinations/ed_2sfArmu7MWUUajauMOoEVbscbii"
				}
			],
			"id": "esb_2sfArshChvq7lATpkrlEXtmp1t6",
			"metadata": "{\"environment\": \"staging\"}",
			"sources": [
				{
					"type": "ip_policy_created.v0",
					"uri": "https://api.ngrok.com/event_subscriptions/esb_2sfArshChvq7lATpkrlEXtmp1t6/sources/ip_policy_created.v0"
				}
			],
			"uri": "https://api.ngrok.com/event_subscriptions/esb_2sfArshChvq7lATpkrlEXtmp1t6"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/event_subscriptions"
}
```
