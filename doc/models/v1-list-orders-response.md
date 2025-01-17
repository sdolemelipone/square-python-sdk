
# V1 List Orders Response

## Structure

`V1 List Orders Response`

## Fields

| Name | Type | Tags | Description |
|  --- | --- | --- | --- |
| `items` | [`List of V1 Order`](/doc/models/v1-order.md) | Optional | - |

## Example (as JSON)

```json
{
  "items": [
    {
      "errors": [
        {
          "category": "PAYMENT_METHOD_ERROR",
          "code": "REFUND_DECLINED",
          "detail": "detail8",
          "field": "field6"
        },
        {
          "category": "REFUND_ERROR",
          "code": "INVALID_CARD_DATA",
          "detail": "detail9",
          "field": "field7"
        },
        {
          "category": "API_ERROR",
          "code": "SOURCE_USED",
          "detail": "detail0",
          "field": "field8"
        }
      ],
      "id": "id7",
      "buyer_email": "buyer_email1",
      "recipient_name": "recipient_name5",
      "recipient_phone_number": "recipient_phone_number7"
    },
    {
      "errors": [
        {
          "category": "REFUND_ERROR",
          "code": "INVALID_CARD_DATA",
          "detail": "detail9",
          "field": "field7"
        }
      ],
      "id": "id8",
      "buyer_email": "buyer_email0",
      "recipient_name": "recipient_name6",
      "recipient_phone_number": "recipient_phone_number6"
    }
  ]
}
```

