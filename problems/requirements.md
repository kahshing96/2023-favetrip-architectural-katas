# Requirements
> full requirements are given from [here](https://on24static.akamaized.net/event/43/16/26/7/rt/1/documents/resourceList1694034742182/finalkatas1694034741100.pdf)

## Business Requirements

- Poll email looking for travel-related emails
- Filter and whitelist certain emails
- The system must interface with the agency’s
existing airline, hotel, and car rental interface system to update travel details (delays, cancellations, updates, gate changes, etc.). Updates must be in the app within 5 minutes of an update (better than the competition)
- Customers should be able to add, update, or delete existing reservations manually as well.
- Items in the dashboard should be able to be grouped by trip, and once the trip is complete, the items should automatically be removed from the dashboard.
- Users should also be able to share their trip information by interfacing with standard social media sites or allowing targeted people to view your trip.
- Richest user interface possible across all deployment platforms
- Provide end-of-year summary reports for users with a wide range of metrics about their travel usage
- Road Warrior gathers analytical data from users trips for various purposes - travel trends, locations, airline and hotel vendor preferences, cancellation and update frequency, and so on.

### Additional context
- must integrate seamlessly with existing travel systems (i.e, SABRE, APOLLO)
- Must integrate with preferred travel agency for quick problem resolution (help me!)
- must work internationally

## Technical Requirements

- Users must be able to access the system at all times (max 5 minutes per month of unplanned downtime)
- Travel updates must be presented in the app within 5 minutes of generation by the source
- Response time from web (800ms) and mobile (First-contentful paint of under 1.4 sec)
