# Flight Booking Confirmed

### 

## Javascript Code
```js
window.appEventData00000 = window.appEventData00000 || [];;;
appEventData00000.push({
  "event": "Flight Booking Confirmed",
    "airTravel": {
        "flightList": [
            {
                "tripId": "<tripId>"
            }
        ]
    },
    "booking": {
        "reservationId": "<reservationId>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|reservationId|string|A unique identifier of a booking used for communication between customer and booking company|ADFIG986958, IUFO89699, XDF-875008767|||||||
|tripId|string|A unique representation of the main departure and arrival points for all primary trip legs \(not including connections\). |SFO&gt;YYC:YYC&gt;SFO, SFO&gt;YYC, SFO&gt;YYC:YYC&gt;YXC:YKA&gt;SFO|^([A-Z]{3}>[A-Z]{3}:?)+$||||||




