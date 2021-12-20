# Flight Extras Displayed

### 

## Javascript Code
```js
window.appEventData00000 = window.appEventData00000 || [];;;
appEventData00000.push({
  "event": "Flight Extras Displayed",
    "airTravel": {
        "flightList": [
            {
                "flightSegmentDesignator": "<flightSegmentDesignator>",
                "flightSegmentDuration": <flightSegmentDuration>,
                "tripId": "<tripId>"
            }
        ]
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|flightSegmentDesignator|string|A combination of a two character airline code and a numeric flight number. \(e.g. WJ1521\)|WJ1515, WJ501, DL2745, AA55|^[A-Z]{2}[1-9][0-9]{0,3}$||||||
|flightSegmentDuration|integer|The total duration of the flight segment \(in minutes\). |35, 55, 90, 122|||||||
|tripId|string|A unique representation of the main departure and arrival points for all primary trip legs \(not including connections\). |SFO&gt;YYC:YYC&gt;SFO, SFO&gt;YYC, SFO&gt;YYC:YYC&gt;YXC:YKA&gt;SFO|^([A-Z]{3}>[A-Z]{3}:?)+$||||||




