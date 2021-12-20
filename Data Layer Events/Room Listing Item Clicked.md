# Room Listing Item Clicked

### 

## Javascript Code
```js
window.appEventData00000 = window.appEventData00000 || [];;;
appEventData00000.push({
  "event": "Room Listing Item Clicked",
    "listingItemClicked": {
        "listing": [
            {
                "itemPosition": <itemPosition>,
                "location": {
                    "fakeProductId": "<fakeProductId>"
                },
                "room": {
                    "typeCode": "<typeCode>"
                }
            }
        ]
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|fakeProductId|string|Helper node used by AA Product String Builder to set product to location. This field gets a static value of "location".  With updates to the AA PS extension, this will soon go away.|location|location||||||
|itemPosition|integer|Integer position of a property within a sorted result. The first returned is position 1. For map results, this value can be the rank by distance from POI.|1, 2, 3, 4, 5||||0|||
|typeCode|string|A code describing the room features. Often indicates number of beds, smoking or non-smoking, ADA accessibility and so on.|1-K-NS, 2-Q-S, S-K-NS-City|||||||




