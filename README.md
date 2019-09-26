# Hackathon Starter

Have you been in a hackathon in the past? Time flies! We have prepared this quick reference document for you to get familiar with our APIs.

Happy Hacking!

# Table of Contents

- [Getting Started](#getting-started)
- [APIs](#apis)
- [SDKs](#sdks)
- [Cheat Sheet](#cheatsheet)
- [Postman](#postman)
- [Examples](#examples)
- [Data Collection](#data-collection)
- [Contributing](#contributing)


## Getting Started

First of all, you need to create an account:

1. Go to [our portal](https://developers.amadeus.com) and click on [register](https://developers.amadeus.com/create-account)
2. Fill in the form using a valid email address and click on the `Create account` button. A confirmation email will be sent to the email address you have just registered.
3. Open your mail and click on `Confirm my account`.

What's next? Our [get started guide](https://developers.amadeus.com/get-started/category?id=80&durl=335&parentId=NaN) contains detailed information about how to get your API key and make your first API call.

The APIs use [OAuth](https://en.wikipedia.org/wiki/OAuth) as authentication mechanism. The [authorization guide](https://github.com/amadeus4dev/developer-guides/blob/master/guides/authorization.md) provides deep technical information on how to get a token in order to perform API calls.

## APIs 

| API | Answers to...                                                                |
| ----------------------------------------------- | ---------------------------------------------------------------------------- |
| [Flight Low-fare Search](https://developers.amadeus.com/self-service/category/203/api-doc/4/api-docs-and-example/10002) | I know where and when I want to fly. What are the best flight deals? |
| [Flight Inspiration Search](https://developers.amadeus.com/self-service/category/203/api-doc/3/api-docs-and-example/10001) | Where can I fly from Madrid in the next months for 400 EUR? |
| [Flight Cheapest Date Search](https://developers.amadeus.com/self-service/category/203/api-doc/5/api-docs-and-example/10003) | When is the cheapest date to fly to London from Boston? |
| [Flight Offers Search](https://developers.amadeus.com/self-service/category/air/api-doc/flight-offers-search/api-reference) | I know where and when I want to fly. What are the best flight deals? |
| [Flight Offers Price](https://developers.amadeus.com/self-service/category/air/api-doc/flight-offers-price/api-reference) | I know the best flight deals for my travel criteria. Are those fares still available? What is the price of extra legroom seats? |
| [Flight Most Booked Destinations](https://developers.amadeus.com/self-service/category/203/api-doc/27/api-docs-and-example/10011) | Where were the most number of bookings made to from Delhi last July?        |
| [Flight Most Traveled Destinations](https://developers.amadeus.com/self-service/category/203/api-doc/7/api-docs-and-example/10005) | Where were people flying to the most from San Francisco in September 2017?          |
| [Flight Busiest Traveling Period](https://developers.amadeus.com/self-service/category/203/api-doc/28/api-docs-and-example/10012) | What was the busiest period for Nice based on either arrivals or departures? |
| [Flight Check-in Links](https://developers.amadeus.com/self-service/category/203/api-doc/8/api-docs-and-example/10006) | What is the URL to my online check-in?                                       |
| [Airport Nearest Relevant](https://developers.amadeus.com/self-service/category/203/api-doc/9/api-docs-and-example/10007) | What relevant airports are there around a specific location?                 |
| [Airport & City Search](https://developers.amadeus.com/self-service/category/203/api-doc/10/api-docs-and-example/10008) | Which cities and/or airports start with ‘PA’ characters?                     |
| [Airline Code Lookup](https://developers.amadeus.com/self-service/category/203/api-doc/26/api-docs-and-example/10010) | Which airline has IATA code BA?                                              |
| [Hotel Search](https://developers.amadeus.com/self-service/category/207/api-doc/11/api-docs-and-example/10013) | What are the best hotel offers during my trip to London?   |
| [Hotel Ratings](https://developers.amadeus.com/self-service/category/hotel/api-doc/hotel-ratings/api-reference) | What travelers think about this hotel?   |
| [Points of Interest](https://developers.amadeus.com/self-service/category/210/api-doc/55/api-docs-and-example/10014) | What are the coolest places to visit during my stay in Barcelona?  |
| [Flight Choice Prediction](https://developers.amadeus.com/self-service/category/air/api-doc/flight-choice-prediction/api-reference) | What is the probability that the traveler will choose one flight offer over the other?  |
| [Trip Parser](https://developers.amadeus.com/self-service/category/trip/api-doc/trip-parser/api-reference) | How do I make my trip information (flight, hotel, car rental, train) from different booking sources: consistent, standardized and consumable by other systems? |

## SDKs

Because there is life beyond `curl`.

- [Python](https://github.com/amadeus4dev/amadeus-python)
- [Ruby](https://github.com/amadeus4dev/amadeus-ruby)
- [Node](https://github.com/amadeus4dev/amadeus-node)
- [Java](https://github.com/amadeus4dev/amadeus-java)

`pull requests` are always welcome :-)

## Cheat Sheet

We normally bring some printed copies to the hackathons, but for your convenience, [here](https://github.com/amadeus4dev/hackathon-starter/blob/master/cheatsheets/amadeus4dev.pdf) you have the pdf version.

Let's save the planet!

## Postman

If you love [Postman](https://www.getpostman.com/) as we do, you'll be glad to see [our public postman collection](https://documenter.getpostman.com/view/2672636/RWEcPfuJ).

New to Postman? Don't miss our [How to play with Self-Service APIs with no code](https://developers.amadeus.com/blog/read?tab=0&category=Technical%20tips&id=573&dateId=4&year=2019) article in our blog.

## Examples

- All SDK `README` files contain sample codes.
- You can find [examples](https://developers.amadeus.com/self-service/apis-docs/code-samples) in our Portal

## Data-Collection

During the hackathon you'll use the `Test environment`, which means that our APIs are using mostly cache data. You can find which data is available on the [Data collection](http://github.com/amadeus4dev/data-collection) repository.

## Contributing

If something is wrong, confusing or you miss information, please let us know. Send your `pull request` or drop us an [email](mailto:developers@amadeus.com).
