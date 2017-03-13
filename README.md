# Fusion Lifestyle Sessions Open Data

## Open Data Endpoint
https://fusionfunctions.azurewebsites.net/api/FusOpenFunction - a feed of session data from Fusion's sites

## Standards
The data is published to conform to [Openactive Realtime Paged Data Exchange 0.2.3](https://www.openactive.io/realtime-paged-data-exchange/0.2.3/).

## Issues, Questions and Comments
Please raise any issues, questions, comments and any feedback as a [new issue in this repository](https://github.com/fusion-lifestyle/opendata/issues).

## Data Fields

| Name | Example value | Description |
|---|---|---|
| `activityGroup` | `Group Exercise Classes` | Category of activity |
| `siteName` | `Southend LTC` | Name of leisure centre |
| `address` | `Garon Park` | Address, not including postcode |
| `postcode` | `SS2 4FA` | Site postcode |
| `telephone` | `01702 613 000` | Site phone number |
| `website` | `www.fusion-lifestyle.com/centres/Albany_Leisure_Centre/Contact#formTop` | Enquiry URL of site |
| `title` | `Deep Aqua Thurs 19:30` | Name of activity as shown in booking system |
| `startDateTime` | `2017-03-02T19:30:00` | UTC start date/time of activity |
| `endDateTime` | `2017-03-02T20:29:59` | UTC end date/time of activity |
| `gender` | `mixed` | one of `mixed`, `male` or `female` |
| `adultAllowed` | true | Activity bookable by 16+ |
| `juniorAllowed` | false | Activity bookable by 0-15 |
| `seniorAllowed` | true | Activity concession available for 60+ |
| `adultCost` | `£0.00` | Cost of non-member adult booking |
| `juniorCost` | `£10.00` | Cost of non-member junior booking |
| `seniorCost` | `£7.50` | Cost of non-member concession booking |
| `availability` | `available` | Number of available spaces; one of `available`, `limited` (less than 5 spaces) or `none` |
| `onSiteLocation` | [ `Diving Pool` ] | Location of the activity within the site |
| `description` | `` | Longer description of the session |
| `imageURL` | `` | Image relating to the session |
| `richTitle` | `` | User-friendly title |
