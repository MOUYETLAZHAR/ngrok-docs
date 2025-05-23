<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "tls_edges": [
    {
      "backend": null,
      "created_at": "2025-05-23T10:07:05Z",
      "description": "acme tls edge",
      "hostports": [
        "example.com:443"
      ],
      "id": "edgtls_2xUZtMN24xXScXTAZ8VzVbPM2iC",
      "ip_restriction": null,
      "metadata": "{\"environment\": \"staging\"}",
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2xUZtMN24xXScXTAZ8VzVbPM2iC"
    },
    {
      "backend": {
        "backend": {
          "id": "bkdhr_2xUZs27AAl2gpvdiZOBEjmpSD3W",
          "uri": "https://api.ngrok.com/backends/http_response/bkdhr_2xUZs27AAl2gpvdiZOBEjmpSD3W"
        },
        "enabled": true
      },
      "created_at": "2025-05-23T10:06:55Z",
      "description": "acme tls edge",
      "hostports": [
        "endpoint-example2.com:443"
      ],
      "id": "edgtls_2xUZs2GwqEVl2YQNw1a7ak8GnvB",
      "ip_restriction": null,
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2xUZs2GwqEVl2YQNw1a7ak8GnvB"
    }
  ],
  "uri": "https://api.ngrok.com/edges/tls"
}
```
