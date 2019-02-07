# Hackathon Starter

Have you been in a hackathon in the past? Time flies! We have prepared this quick reference document for you to get familiar with our APIs.

Happy Hacking!

# Table of Contents

- [Getting Started](#getting-started)
- [APIs](#apis)
- [SDKs](#sdks)
- [Cheat Sheet](#cheatsheets)
- [Postman](#postman)
- [Examples](#examples)
- [Datasets](#datasets)

## Getting Started

1. Go to [our portal](https://developers.amadeus.com) and click on [register](https://developers.amadeus.com/create-account)
2. Fill in the form using a valid email address and click on the `Create account`button. A confirmation email will be sent to the email address you have just registered.
3. Open your mail and click on `Confirm my account`.

What´s next? Our [get started guide](https://github.com/amadeus4dev/developer-guides/blob/master/guides/getstarted.md) contains detailed information about how to get your API key and make your first API call.

## APIs 

| API | Answers to...                                                                |
| ----------------------------------------------- | ---------------------------------------------------------------------------- |
| [Flight Low-fare Search](https://developers.amadeus.com/self-service/category/203/api-doc/4/api-docs-and-example/10002) | I know where and when I want to fly. What are the best flight deals? |
| [Flight Inspiration Search](https://developers.amadeus.com/self-service/category/203/api-doc/3/api-docs-and-example/10001) | Where can I fly from Madrid in the next months for 400 EUR? |
| [Flight Cheapest Date Search](https://developers.amadeus.com/self-service/category/203/api-doc/5/api-docs-and-example/10003) | When is the cheapest date to fly to London from Boston? |
| [Fight Most Searched Destinations](https://developers.amadeus.com/self-service/category/203/api-doc/6/api-docs-and-example/10004) | Which were the most searched destinations from New York in June 2017?            |
| [Flight Most Booked Destinations](https://developers.amadeus.com/self-service/category/203/api-doc/27/api-docs-and-example/10011) | Where were the most number of bookings made to from Delhi last July?        |
| [Flight Most Traveled Destinations](https://developers.amadeus.com/self-service/category/203/api-doc/7/api-docs-and-example/10005) | Where were people flying to the most from San Francisco in September 2017?          |
| [Flight Busiest Traveling Period](https://developers.amadeus.com/self-service/category/203/api-doc/28/api-docs-and-example/10012) | What was the busiest period for Nice based on either arrivals or departures? |
| [Flight Check-in Links](https://developers.amadeus.com/self-service/category/203/api-doc/8/api-docs-and-example/10006) | What is the URL to my online check-in?                                       |
| [Airport Nearest Relevant](https://developers.amadeus.com/self-service/category/203/api-doc/9/api-docs-and-example/10007) | What relevant airports are there around a specific location?                 |
| [Airport & City Search](https://developers.amadeus.com/self-service/category/203/api-doc/10/api-docs-and-example/10008) | Which cities and/or airports start with ‘PA’ characters?                     |
| [Airline Code Lookup](https://developers.amadeus.com/self-service/category/203/api-doc/26/api-docs-and-example/10010) | Which airline has IATA code BA?                                              |
| [Hotel Search](https://developers.amadeus.com/self-service/category/207/api-doc/11/api-docs-and-example/10013) | What are the best hotel offers during my trip to London?   |

## SDKs

Because there is life beyond `curl`.

- [Python](https://github.com/amadeus4dev/amadeus-python)
- [Ruby](https://github.com/amadeus4dev/amadeus-ruby)
- [Node](https://github.com/amadeus4dev/amadeus-node)
- [Java](https://github.com/amadeus4dev/amadeus-java)

We would be more than happy to receive your `pull requets` :-)

## Cheat Sheet

We normally bring some printed copies to the hackathons, but for your convenience, [here](https://github.com/amadeus4dev/hackathon-starter/blob/master/cheatsheets/amadeus4dev.pdf) you have the pdf version.

Let's save the planet!

## Postman

If you love [Postman](https://www.getpostman.com/) as we do, you'll be glad to see [our public postman collection](https://documenter.getpostman.com/view/2672636/RWEcPfuJ).

## Examples

- All SDK `README` files contain sample codes.
- You can find [examples](https://developers.amadeus.com/self-service/apis-docs/code-samples) in our Portal

## Datasets

During the hackathon you'll use the `Test environment`, which means that our APIs are using mostly cache data:

- [List of Origin and Destinations](https://github.com/amadeus4dev/hackathon-starter/blob/master/datasets/flightsearch.md) for `Flight Inspiration Search` and `Flight Cheapest Date Search`.

- [List of Origin and Destinations](https://github.com/amadeus4dev/hackathon-starter/blob/master/datasets/ti.md) for `Flight Most [Searched|Booked|Traveled] Destinations` and `Flight Busiest Traveling Period`.

- The [following table](https://github.com/amadeus4dev/hackathon-starter/blob/master/datasets/checkinlinks.md) contains a list of valid airlines for `Flight Check-in Links`.

- `Airport Nearest Relevant` & `Airport & City Search` contain data from United States, Spain, United Kingdom, Germany and India.

- `Airline Code Lookup` contains almost all airlines.

- The content of `Hotel Search` comes directly from the hotel providers, so the content might change dynamically.

