<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "endpoints": [
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-08-22T10:07:42Z",
      "description": "sample cloud endpoint",
      "domain": {
        "id": "rd_31dcBt3xEFWm6A8ExD7lZHwcf3l",
        "uri": "https://api.ngrok.com/reserved_domains/rd_31dcBt3xEFWm6A8ExD7lZHwcf3l"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_31dcCXKkoN6qTzSWbGLXECYi2IJ",
      "metadata": "{\"environment\": \"staging\"}",
      "pooling_enabled": false,
      "proto": "https",
      "public_url": "https://endpoint-example2.com",
      "traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
      "type": "cloud",
      "updated_at": "2025-08-22T10:07:42Z",
      "uri": "https://api.ngrok.com/endpoints/ep_31dcCXKkoN6qTzSWbGLXECYi2IJ",
      "url": "https://endpoint-example2.com"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-08-22T10:07:40Z",
      "hostport": "10f2c170264a.ngrok.paid:443",
      "id": "ep_31dcCHu70vWvQICuIGpvXsw4UmX",
      "name": "command_line",
      "pooling_enabled": false,
      "principal": {
        "id": "usr_31dc5md6XF2LJn4nNlfhePlGQX6",
        "uri": ""
      },
      "proto": "https",
      "public_url": "https://10f2c170264a.ngrok.paid",
      "tunnel": {
        "id": "tn_31dcCHu70vWvQICuIGpvXsw4UmX",
        "uri": "https://api.ngrok.com/tunnels/tn_31dcCHu70vWvQICuIGpvXsw4UmX"
      },
      "tunnel_session": {
        "id": "ts_31dcCGEAE2W8TnKvUWVtqAOEOjL",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_31dcCGEAE2W8TnKvUWVtqAOEOjL"
      },
      "type": "ephemeral",
      "updated_at": "2025-08-22T10:07:40Z",
      "upstream_url": "http://localhost:80",
      "url": "https://10f2c170264a.ngrok.paid"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-08-22T10:07:37Z",
      "domain": {
        "id": "rd_31dcBt3xEFWm6A8ExD7lZHwcf3l",
        "uri": "https://api.ngrok.com/reserved_domains/rd_31dcBt3xEFWm6A8ExD7lZHwcf3l"
      },
      "edge": {
        "id": "edgtls_31dcBrqfzW4Abl3NGFe6F3THF57",
        "uri": "https://api.ngrok.com/edges/tls/edgtls_31dcBrqfzW4Abl3NGFe6F3THF57"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_31dcBuPx8xx6FWX1tkJoXE3rN6K",
      "pooling_enabled": false,
      "proto": "tls",
      "public_url": "tls://endpoint-example2.com",
      "type": "edge",
      "updated_at": "2025-08-22T10:07:37Z"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/endpoints"
}
```
