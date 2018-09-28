# South Summit Hackathon Starter

Have you been in a Hackathon in the past? Time flies! We have prepared this quick reference document for you to get familiar with our APIs.

Happy Hacking!

# Table of Contents

- [Getting Started](#getting-started)
- [APIs](#apis)
- [SDKs](#sdks)
- [CheatSheets](#cheatsheets)
- [Examples](#examples)

## Getting Started

### Amadeus for Developers APIs

The best way to understand how to get started is by reading our [get started guide](https://github.com/amadeus4dev/developer-guides/blob/master/guides/getstarted.md)

#### tl;dr

1. Go to [our portal](https://developers.amadeus.com) and click on [register](https://developers.amadeus.com/create-account)
2. Complete the form, using a valid email address and click on `Create account` button. An automatic confirmation email is sent to the email address you registered.
3. In the confirmation email you receive, click on `Confirm my account`.

Once registered, you need to get your API keys. In order to understand how authentication works, please refer to our [authentication guide](https://github.com/amadeus4dev/developer-guides/blob/master/guides/authorization.md).

### AVUXI APIs

The API keys are distributed manually on demand. Feel free to request one!

Don't miss [this guide](https://admin.avuxi.com/api) to get started!

## APIs 

### Amadeus for Developers APIs

| Endpoint                                        | Answers to...                                                                |
| ----------------------------------------------- | ---------------------------------------------------------------------------- |
| [/v1/shopping/flight-offers](https://developers.amadeus.com/self-service/category/203/api-doc/4/api-docs-and-example/10002) | I know where when I want to fly. What are the best flight deals? |
| [/v1/shopping/flight-destinations](https://developers.amadeus.com/self-service/category/203/api-doc/3/api-docs-and-example/10001) | Where can I fly from/to Paris in the next months for 400 EUR? |
| /v1/shopping/flight-dates                       | When is the cheapest date to fly to Madrid from London?                      |
| /v1/travel/analytics/fare-searches              | Which were the most searched destinations from Nice in June 2017?            |
| /v1/travel/analytics/air-traffic/booked         | Where were the most number of bookings made to from Madrid last July?        |
| /v1/travel/analytics/air-traffic/traveled       | Where were people flying to the most from London in September 2017?          |
| /v1/travel/analytics/air-traffic/busiest-period | What was the busiest period for Nice based on either arrivals or departures? |
| /v2/reference-data/urls/checkin-links           | What is the URL to my online check-in?                                       |
| /v1/reference-data/locations/airports           | What relevant airports are there around a specific location?                 |
| /v1/reference-data/locations                    | Which cities and/or airports start with ‘PA’ characters?                     |
| /v1/reference-data/airlines                     | Which airline has IATA code BA?                                              |
| /v1/shopping/hotel-offers                       | What are the best hotel offers during my trip to London?                     |

### AVUXI APIs

| Endpoint                      | Description                                                                     |
| ----------------------------- | ------------------------------------------------------------------------------- |
| /v1/GetLocationScoresByRadius | Return the Location Scores for the selected location                            |
| /v1/GetHeatMapVectorial       | Return the polygons for the category and area (tile) selected.                  |
| /v1/GetLocationScore          | Return the Location Score (0 to 99) for each category for the selected location | 
| /v1/GetPointsOfInterestByBox  | Return Points of Interest (POIs) of selected areas                              |
| /v1/GetMetroLinesByCityCenter | Return Stops and Metro Lines for any coordinate of selected cities              |

## SDKs

Because there is life beyond `curl`.

- [Python](https://github.com/amadeus4dev/amadeus-python)
- [Ruby](https://github.com/amadeus4dev/amadeus-ruby)
- [Node](https://github.com/amadeus4dev/amadeus-node)
- [Java](https://github.com/amadeus4dev/amadeus-java)

We would be more than happy to receive your `pull requets` :-)

## Cheat Sheets

We normally bring some printed copies to the Hackathons. For your convenience, here you have the pdf version:

- [Amadeus for Developers Chet Sheet](https://github.com/amadeus4dev/hackathon-starter/blob/master/cheatsheets/amadeus4dev.pdf)
- [Avuxi Cheat Sheet](https://github.com/amadeus4dev/hackathon-starter/blob/master/cheatsheets/avuxi.pdf)

Let's save the planet!

## Examples

All SDKs `README` files contains sample codes. More Python snipets:
https://github.com/amadeus4dev/samples-python

An android application using the Flight APIs:
https://github.com/amadeus4dev/android-example

AVUXI demos in Python, Javascript, Node and C#:
https://github.com/avuxi/AVAPIDataExamples


