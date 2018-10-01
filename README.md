# Hackathon Starter

Have you been in a Hackathon in the past? Time flies! We have prepared this quick reference document for you to get familiar with our APIs.

Happy Hacking!

# Table of Contents

- [Getting Started](#getting-started)
- [APIs](#apis)
- [SDKs](#sdks)
- [CheatSheets](#cheatsheets)
- [Postman](#postman)
- [Examples](#examples)
- [Datasets](#datasets)

## Getting Started

### Amadeus for Developers APIs

The best way to get started is by reading our [get started guide](https://github.com/amadeus4dev/developer-guides/blob/master/guides/getstarted.md)

#### tl;dr

1. Go to [our portal](https://developers.amadeus.com) and click on [register](https://developers.amadeus.com/create-account)
2. Complete the form, using a valid email address and click on `Create account` button. An automatic confirmation email is sent to the email address you registered.
3. In the confirmation email you receive, click on `Confirm my account`.

Once registered, you need to get your API keys. In order to understand how authentication works, please refer to our [authentication guide](https://github.com/amadeus4dev/developer-guides/blob/master/guides/authorization.md).

### AVUXI APIs

The API keys are distributed manually on demand. Feel free to request one!

Don't miss [this guide](https://admin.avuxi.com/api) to get started!

## APIs 

### Amadeus for Developers

| API | Answers to...                                                                |
| ----------------------------------------------- | ---------------------------------------------------------------------------- |
| [Flight Low-fare Search](https://developers.amadeus.com/self-service/category/203/api-doc/4/api-docs-and-example/10002) | I know where and when I want to fly. What are the best flight deals? |
| [Flight Inspiration Search](https://developers.amadeus.com/self-service/category/203/api-doc/3/api-docs-and-example/10001) | Where can I fly from/to Paris in the next months for 400 EUR? |
| [Flight Cheapest Date Search](https://developers.amadeus.com/self-service/category/203/api-doc/5/api-docs-and-example/10003) | When is the cheapest date to fly to Madrid from London? |
| [Fight Most Searched Destinations](https://developers.amadeus.com/self-service/category/203/api-doc/6/api-docs-and-example/10004) | Which were the most searched destinations from Nice in June 2017?            |
| [Flight Most Booked Destinations](https://developers.amadeus.com/self-service/category/203/api-doc/27/api-docs-and-example/10011) | Where were the most number of bookings made to from Madrid last July?        |
| [Flight Most Traveled Destinations](https://developers.amadeus.com/self-service/category/203/api-doc/7/api-docs-and-example/10005) | Where were people flying to the most from London in September 2017?          |
| [Flight Busiest Traveling Period](https://developers.amadeus.com/self-service/category/203/api-doc/28/api-docs-and-example/10012) | What was the busiest period for Nice based on either arrivals or departures? |
| [Flight Check-in Links](https://developers.amadeus.com/self-service/category/203/api-doc/8/api-docs-and-example/10006) | What is the URL to my online check-in?                                       |
| [Airport Nearest Relevant](https://developers.amadeus.com/self-service/category/203/api-doc/9/api-docs-and-example/10007) | What relevant airports are there around a specific location?                 |
| [Airport & City Search](https://developers.amadeus.com/self-service/category/203/api-doc/10/api-docs-and-example/10008) | Which cities and/or airports start with ‘PA’ characters?                     |
| [Airline Code Lookup](https://developers.amadeus.com/self-service/category/203/api-doc/26/api-docs-and-example/10010) | Which airline has IATA code BA?                                              |
| [Hotel Search](https://developers.amadeus.com/self-service/category/207/api-doc/11/api-docs-and-example/10009) | What are the best hotel offers during my trip to London?   |

### AVUXI

| API | Description                                                                     |
| ----------------------------- | ------------------------------------------------------------------------------- |
| [Get Location Scores By Radius](https://admin.avuxi.com/api) | Return the Location Scores for the selected location                            |
| [Heat Map Vectors](https://admin.avuxi.com/api)      | Return the polygons for the category and area (tile) selected.                  |
| [Nearby Info](https://admin.avuxi.com/api) | Return the Location Score (0 to 99) for each category for the selected location | 
| [Points Of Interest](https://admin.avuxi.com/api)  | Return Points of Interest (POIs) of selected areas                              |
| [Transport](https://admin.avuxi.com/api) | Return Stops and Metro Lines for any coordinate of selected cities              |

## SDKs

### Amadeus for Developers

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

## Postman

### Amadeus for Developers

If you love [Postman](https://www.getpostman.com/) as we do, you'll be glad to see [our public postman collection](https://documenter.getpostman.com/view/2672636/RWEcPfuJ).

## Examples

- All SDK `README` files contain sample codes. We have uploaded more [Python snipets](https://github.com/amadeus4dev/samples-python) to Github.
- An [android application](https://github.com/amadeus4dev/android-example) using the Flight APIs.
- Useful [AVUXI demos](https://github.com/avuxi/AVAPIDataExamples) written in Python, Javascript, Node and C#.

## Datasets

### Amadeus for Developers

During the Hackathon you'll use the `Testing environment`, which means that our APIs are using mostly cache data:

- [List of Origin and Destinations](https://github.com/amadeus4dev/hackathon-starter/blob/master/datasets/flightsearch.md) for Flight Inspiration Search and Flight Cheapest Date Search

- [List of Origin and Destinations](https://github.com/amadeus4dev/hackathon-starter/blob/master/datasets/ti.md) for Fight Most [Searched|Booked|Traveled] Destinations and Flight Busiest Traveling Period.

- The [following table](https://github.com/amadeus4dev/hackathon-starter/blob/master/datasets/checkinlinks.md) contains a list of valid Airlines for Flight Check-in Links.

- Airport Nearest Relevant: United States, Canada, Spain, United Kingdom, Germany, India.

- Airline Code Lookup contains almost all airlines.

- The content of Hotel Search comes directly from the Hotel providers, so the content might change dynamically.

