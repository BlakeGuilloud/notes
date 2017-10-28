## Lambda Notes

- You MUST set headers in your lambda response as well as API integration response:

```javascript
headers: {
  "Access-Control-Allow-Credentials": true,
  "Access-Control-Allow-Origin": "*",
  "Content-Type": "application/json",
},
```