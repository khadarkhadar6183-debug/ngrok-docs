<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "tls_edges": [
    {
      "backend": null,
      "created_at": "2025-08-05T18:35:00Z",
      "description": "acme tls edge",
      "hostports": [
        "example.com:443"
      ],
      "id": "edgtls_30sanTWNjG42BpmblIgCndoovHm",
      "ip_restriction": null,
      "metadata": "{\"environment\": \"staging\"}",
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_30sanTWNjG42BpmblIgCndoovHm"
    },
    {
      "backend": {
        "backend": {
          "id": "bkdhr_30saltdjTxcXCKlbeTR49uQ64yn",
          "uri": "https://api.ngrok.com/backends/http_response/bkdhr_30saltdjTxcXCKlbeTR49uQ64yn"
        },
        "enabled": true
      },
      "created_at": "2025-08-05T18:34:48Z",
      "description": "acme tls edge",
      "hostports": [
        "endpoint-example2.com:443"
      ],
      "id": "edgtls_30salwIgQM0pQnKUfLHdSwUKMdp",
      "ip_restriction": null,
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_30salwIgQM0pQnKUfLHdSwUKMdp"
    }
  ],
  "uri": "https://api.ngrok.com/edges/tls"
}
```
