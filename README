### Delayed Carrier Service

Implements Shopify's CarrierService API (https://docs.shopify.com/api/carrierservice).

Each request will sleep randomly up to 7 seconds before responding with 2 shipping rates, such as:

```
{
    "rates": [
        {
            "service_name": "Standard rate",
            "service_code": "standard-rate-1",
            "total_price": 728,
            "currency": "USD"
        },
        {
            "service_name": "Expedited rate",
            "service_code": "expedited-rate-2",
            "total_price": 1274,
            "currency": "USD"
        }
    ]
}
```
