# Donation Completed

### 

## Javascript Code
```js
window.appEventData006 = window.appEventData006 || [];
appEventData006.push({
  "event": "Donation Completed",
    "donation": {
        "item": [
            {
                "donationID": "<donationID>"
            }
        ],
        "total": {
            "currency": "<currency>"
        }
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|currency|string|Currency of the donation payment. ISO 4217 \(3 character alpha\), uppercase |USD, CAD, GBP, CHF|^[A-Z]{3}$|3|3||||
|donationID|string|Unique identifier of the donation. Max Length 20. Used to prevent duplication.||^[a-zA-Z0-9]{6,20}$|6|20||||
