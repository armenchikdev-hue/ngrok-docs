<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "reserved_domains": [
    {
      "acme_challenge_cname_target": null,
      "certificate": {
        "id": "cert_31dc9sEU4JMTjqu93Hm3HIBPFTS",
        "uri": "https://api.ngrok.com/tls_certificates/cert_31dc9sEU4JMTjqu93Hm3HIBPFTS"
      },
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": "2udamkamcl8pjmrff.4xuvnjsemuzxeuw9y.local-ngrok-cname.com",
      "created_at": "2025-08-22T10:07:21Z",
      "domain": "myapp.mydomain.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_31dc9ujWs6iQgo9aCVlb3D4W7ae",
      "is_dev": false,
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_31dc9ujWs6iQgo9aCVlb3D4W7ae"
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
          "started_at": "2025-08-22T10:07:21Z"
        },
        "renews_at": null
      },
      "cname_target": "4knqktdwka2umyjjc.4xuvnjsemuzxeuw9y.local-ngrok-cname.com",
      "created_at": "2025-08-22T10:07:21Z",
      "description": "Device 0001 Dashboard",
      "domain": "manage-0002.app.example.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_31dc9pvh41IhF1diNjgaSMTilM4",
      "is_dev": false,
      "metadata": "{\"service\": \"dashboard\"}",
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_31dc9pvh41IhF1diNjgaSMTilM4"
    },
    {
      "acme_challenge_cname_target": null,
      "certificate": null,
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": null,
      "created_at": "2025-08-22T10:06:51Z",
      "description": "Your dev domain",
      "domain": "popular-warthog-regular.ngrok-free.dev",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_31dc66lWbj2YF22C9eWTtCb54c3",
      "is_dev": true,
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_31dc66lWbj2YF22C9eWTtCb54c3"
    }
  ],
  "uri": "https://api.ngrok.com/reserved_domains"
}
```
