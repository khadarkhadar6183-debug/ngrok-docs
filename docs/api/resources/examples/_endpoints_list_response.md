<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "endpoints": [
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-08-05T18:34:53Z",
      "description": "sample cloud endpoint",
      "domain": {
        "id": "rd_30salurBZtGS85C0iXOWLHWYVXg",
        "uri": "https://api.ngrok.com/reserved_domains/rd_30salurBZtGS85C0iXOWLHWYVXg"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_30samcSZZAGhZLDMGHtGkwjmyZj",
      "metadata": "{\"environment\": \"staging\"}",
      "pooling_enabled": false,
      "proto": "https",
      "public_url": "https://endpoint-example2.com",
      "traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
      "type": "cloud",
      "updated_at": "2025-08-05T18:34:53Z",
      "uri": "https://api.ngrok.com/endpoints/ep_30samcSZZAGhZLDMGHtGkwjmyZj",
      "url": "https://endpoint-example2.com"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-08-05T18:34:51Z",
      "hostport": "2df984f7835c.ngrok.paid:443",
      "id": "ep_30samLccUI6Dc4BriuV0hmgDp6o",
      "name": "command_line",
      "pooling_enabled": false,
      "principal": {
        "id": "usr_30safpvBLUgCRoHgGzTn33E5SU5",
        "uri": ""
      },
      "proto": "https",
      "public_url": "https://2df984f7835c.ngrok.paid",
      "tunnel": {
        "id": "tn_30samLccUI6Dc4BriuV0hmgDp6o",
        "uri": "https://api.ngrok.com/tunnels/tn_30samLccUI6Dc4BriuV0hmgDp6o"
      },
      "tunnel_session": {
        "id": "ts_30samLNLGgGSiI8j5WWHR1lYqUs",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_30samLNLGgGSiI8j5WWHR1lYqUs"
      },
      "type": "ephemeral",
      "updated_at": "2025-08-05T18:34:51Z",
      "upstream_url": "http://localhost:80",
      "url": "https://2df984f7835c.ngrok.paid"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-08-05T18:34:48Z",
      "domain": {
        "id": "rd_30salurBZtGS85C0iXOWLHWYVXg",
        "uri": "https://api.ngrok.com/reserved_domains/rd_30salurBZtGS85C0iXOWLHWYVXg"
      },
      "edge": {
        "id": "edgtls_30salwIgQM0pQnKUfLHdSwUKMdp",
        "uri": "https://api.ngrok.com/edges/tls/edgtls_30salwIgQM0pQnKUfLHdSwUKMdp"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_30salxKZmUwuhltHveBAsHoVdac",
      "pooling_enabled": false,
      "proto": "tls",
      "public_url": "tls://endpoint-example2.com",
      "type": "edge",
      "updated_at": "2025-08-05T18:34:48Z"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/endpoints"
}
```
