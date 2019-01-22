## Delivery Date
Period during which the item should be delivered

# Overview
The field introduced by this extension is `items/deliveryDate`. 
It can be represented as Period value.
## Example
The following extract illustrates this property in use within the items block.
```
{
    "items": [
        {
          "id": "item1",
          "description": "Ceremonial Trumpets for Oxford Town Hall",
          "classification": {
            "description": "Trumpets",
            "scheme": "CPV",
            "id": "37312100",
            "uri": "http://purl.org/cpv/2008/code-37312100"
          },
          "deliveryLocation": {
            "geometry": {
              "type": "Point",
              "coordinates": [
                51.751944,
                -1.257778
              ]
            },
            "gazetteer": {
              "scheme": "GEONAMES",
              "identifiers": [
                "2640729"
              ]
            },
            "description": "Central Oxford",
            "uri": "http://www.geonames.org/2640729/oxford.html"
          },
          "deliveryAddress": {
            "postalCode": "OX1 1BX",
            "countryName": "United Kingdom",
            "streetAddress": "Town Hall, St Aldate's",
            "region": "Oxfordshire",
            "locality": "Oxford"
          },
          "deliveryDate": {
            "startDate": "2016-04-20T00:00:00+03:00",
            "endDate": "2016-04-30T00:00:00+03:00"
          },
          "unit": {
            "name": "Items",
            "value": {
              "currency": "GBP",
              "amount": 10000
            }
          },
          "quantity": 10
        }
    ],
}
```