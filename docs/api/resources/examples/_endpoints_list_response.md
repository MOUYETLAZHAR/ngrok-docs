<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "endpoints": [
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-05-23T10:07:00Z",
      "description": "sample cloud endpoint",
      "domain": {
        "id": "rd_2xUZs3TKYN9Ufi8g7D5Zp5RUQog",
        "uri": "https://api.ngrok.com/reserved_domains/rd_2xUZs3TKYN9Ufi8g7D5Zp5RUQog"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_2xUZsetjYuERMxZzrTJ07YqPNDi",
      "metadata": "{\"environment\": \"staging\"}",
      "pooling_enabled": false,
      "proto": "https",
      "public_url": "https://endpoint-example2.com",
      "traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
      "type": "cloud",
      "updated_at": "2025-05-23T10:07:00Z",
      "uri": "https://api.ngrok.com/endpoints/ep_2xUZsetjYuERMxZzrTJ07YqPNDi",
      "url": "https://endpoint-example2.com"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-05-23T10:06:58Z",
      "hostport": "4cce66b8697b.ngrok.paid:443",
      "id": "ep_2xUZsOIV0nx3AxUV529GmDXJNvN",
      "name": "command_line",
      "pooling_enabled": false,
      "principal": {
        "id": "usr_2xUZpwjU8Gt8NEPAp78dNCkJcFM",
        "uri": ""
      },
      "proto": "https",
      "public_url": "https://4cce66b8697b.ngrok.paid",
      "tunnel": {
        "id": "tn_2xUZsOIV0nx3AxUV529GmDXJNvN",
        "uri": "https://api.ngrok.com/tunnels/tn_2xUZsOIV0nx3AxUV529GmDXJNvN"
      },
      "tunnel_session": {
        "id": "ts_2xUZsPYfI9nW28fwVstPkMQlQEQ",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_2xUZsPYfI9nW28fwVstPkMQlQEQ"
      },
      "type": "ephemeral",
      "updated_at": "2025-05-23T10:06:58Z",
      "upstream_url": "http://localhost:80",
      "url": "https://4cce66b8697b.ngrok.paid"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-05-23T10:06:55Z",
      "domain": {
        "id": "rd_2xUZs3TKYN9Ufi8g7D5Zp5RUQog",
        "uri": "https://api.ngrok.com/reserved_domains/rd_2xUZs3TKYN9Ufi8g7D5Zp5RUQog"
      },
      "edge": {
        "id": "edgtls_2xUZs2GwqEVl2YQNw1a7ak8GnvB",
        "uri": "https://api.ngrok.com/edges/tls/edgtls_2xUZs2GwqEVl2YQNw1a7ak8GnvB"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_2xUZs2m9DivUL7s0qK3vDRi9IIb",
      "pooling_enabled": false,
      "proto": "tls",
      "public_url": "tls://endpoint-example2.com",
      "type": "edge",
      "updated_at": "2025-05-23T10:06:55Z"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/endpoints"
}
```
