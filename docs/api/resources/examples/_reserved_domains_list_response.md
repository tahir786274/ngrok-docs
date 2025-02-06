<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"reserved_domains": [
		{
			"acme_challenge_cname_target": null,
			"certificate": {
				"id": "cert_2sfAovh4mqr3THjYlrp8jr1yciL",
				"uri": "https://api.ngrok.com/tls_certificates/cert_2sfAovh4mqr3THjYlrp8jr1yciL"
			},
			"certificate_management_policy": null,
			"certificate_management_status": null,
			"cname_target": "2udamkamcl8pjmrff.3pfypz5hngf8mumtk.local-ngrok-cname.com",
			"created_at": "2025-02-06T10:07:13Z",
			"domain": "myapp.mydomain.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2sfAp5GsJfDYt3SM4SYAKuVQd6M",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2sfAp5GsJfDYt3SM4SYAKuVQd6M"
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
					"started_at": "2025-02-06T10:07:14Z"
				},
				"renews_at": null
			},
			"cname_target": "4knqktdwka2umyjjc.3pfypz5hngf8mumtk.local-ngrok-cname.com",
			"created_at": "2025-02-06T10:07:14Z",
			"description": "Device 0001 Dashboard",
			"domain": "manage-0002.app.example.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2sfAp26WIcfHfFCxkOspBNja0mC",
			"metadata": "{\"service\": \"dashboard\"}",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2sfAp26WIcfHfFCxkOspBNja0mC"
		}
	],
	"uri": "https://api.ngrok.com/reserved_domains"
}
```
