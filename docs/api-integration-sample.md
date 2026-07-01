# API Integration Sample

## Example Request

```json
{
  "customerMessage": "How much is the shipping fee?",
  "contextType": "faq_support"
}
```

## Example Response

```json
{
  "intent": "shipping_fee",
  "answer": "Shipping fee depends on your delivery location and order value. Could you provide your district or address so I can help estimate it?",
  "confidence": 0.86
}
```

## Notes

This sample is used to demonstrate chatbot response format and API integration planning. It can be connected to a Python backend or a web chatbot UI in future versions.
