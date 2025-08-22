<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "tls_edges": [
    {
      "backend": null,
      "created_at": "2025-08-22T10:07:48Z",
      "description": "acme tls edge",
      "hostports": [
        "example.com:443"
      ],
      "id": "edgtls_31dcDEaCP5RBu91WKBKQnp5zr3q",
      "ip_restriction": null,
      "metadata": "{\"environment\": \"staging\"}",
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_31dcDEaCP5RBu91WKBKQnp5zr3q"
    },
    {
      "backend": {
        "backend": {
          "id": "bkdhr_31dcBwU9TUqm3F67PtOdg9wu9d5",
          "uri": "https://api.ngrok.com/backends/http_response/bkdhr_31dcBwU9TUqm3F67PtOdg9wu9d5"
        },
        "enabled": true
      },
      "created_at": "2025-08-22T10:07:37Z",
      "description": "acme tls edge",
      "hostports": [
        "endpoint-example2.com:443"
      ],
      "id": "edgtls_31dcBrqfzW4Abl3NGFe6F3THF57",
      "ip_restriction": null,
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_31dcBrqfzW4Abl3NGFe6F3THF57"
    }
  ],
  "uri": "https://api.ngrok.com/edges/tls"
}
```
