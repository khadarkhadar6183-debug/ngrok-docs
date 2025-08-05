<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "reserved_domains": [
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
          "started_at": "2025-08-05T18:34:32Z"
        },
        "renews_at": null
      },
      "cname_target": "4knqktdwka2umyjjc.5oyebe41amx2bndzx.local-ngrok-cname.com",
      "created_at": "2025-08-05T18:34:32Z",
      "description": "Device 0001 Dashboard",
      "domain": "manage-0002.app.example.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_30sajzj0z7rjDeSAsrDxG9RcGWn",
      "is_dev": false,
      "metadata": "{\"service\": \"dashboard\"}",
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_30sajzj0z7rjDeSAsrDxG9RcGWn"
    },
    {
      "acme_challenge_cname_target": null,
      "certificate": {
        "id": "cert_30sajyJ62EOXkLwxg49XyqpAoV2",
        "uri": "https://api.ngrok.com/tls_certificates/cert_30sajyJ62EOXkLwxg49XyqpAoV2"
      },
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": "2udamkamcl8pjmrff.5oyebe41amx2bndzx.local-ngrok-cname.com",
      "created_at": "2025-08-05T18:34:32Z",
      "domain": "myapp.mydomain.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_30sajua90YGsCH2xDjIGo5xeTOT",
      "is_dev": false,
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_30sajua90YGsCH2xDjIGo5xeTOT"
    },
    {
      "acme_challenge_cname_target": null,
      "certificate": null,
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": null,
      "created_at": "2025-08-05T18:34:01Z",
      "description": "Your dev domain",
      "domain": "neatly-game-turkey.ngrok-free.dev",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_30sag5Lfj4JRHmv8F1V0Iu8rdsI",
      "is_dev": true,
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_30sag5Lfj4JRHmv8F1V0Iu8rdsI"
    }
  ],
  "uri": "https://api.ngrok.com/reserved_domains"
}
```
