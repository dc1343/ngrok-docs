<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"event_subscriptions": [
		{
			"created_at": "2025-02-20T10:07:18Z",
			"description": "ip policy creations",
			"destinations": [
				{
					"id": "ed_2tIiYgbC9TRcHx0yG5nXEjue8AB",
					"uri": "https://api.ngrok.com/event_destinations/ed_2tIiYgbC9TRcHx0yG5nXEjue8AB"
				}
			],
			"id": "esb_2tIiYk3X9q9Ixv5ZtqXfSoHbtAc",
			"metadata": "{\"environment\": \"staging\"}",
			"sources": [
				{
					"type": "ip_policy_created.v0",
					"uri": "https://api.ngrok.com/event_subscriptions/esb_2tIiYk3X9q9Ixv5ZtqXfSoHbtAc/sources/ip_policy_created.v0"
				}
			],
			"uri": "https://api.ngrok.com/event_subscriptions/esb_2tIiYk3X9q9Ixv5ZtqXfSoHbtAc"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/event_subscriptions"
}
```
