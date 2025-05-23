<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Request

```bash
curl \
-X PATCH \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"certificate_management_policy":{"authority":"letsencrypt"},"description":"point-of-sale new york #302","http_endpoint_configuration_id":"ec_2xUZpzRonkndx01UKR6dfn9oBl4","https_endpoint_configuration_id":"ec_2xUZq1WkUOs40g1neWYTvsz5STY","metadata":"{\"env\": \"staging\", \"connector_id\":\"64698fcc-5f5c-4b63-910e-8669d04bd943\"}"}' \
https://api.ngrok.com/reserved_domains/rd_2xUZpzj6wUR43tiHrJgBXpjHdcz
```
