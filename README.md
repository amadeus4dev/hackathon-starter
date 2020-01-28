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
- [FAQ](#FAQ)
- [Contributing](#contributing)


## Getting Started

First of all, you need to create an account:

1. Go to [our portal](https://developers.amadeus.com) and click on [register](https://developers.amadeus.com/create-account)
2. Fill in the form using a valid email address and click on the `Create account` button. A confirmation email will be sent to the email address you have just registered.
3. Open your mail and click on `Confirm my account`.

What's next? Our [get started guide](https://developers.amadeus.com/get-started/category?id=80&durl=335&parentId=NaN) contains detailed information about how to get your API key and make your first API call.

The APIs use [OAuth](https://en.wikipedia.org/wiki/OAuth) as authentication mechanism. The [authorization guide](https://github.com/amadeus4dev/developer-guides/blob/master/guides/authorization.md) provides deep technical information on how to get a token in order to perform API calls.

## APIs 

| Category | Subcategories |
| ----------------------------------------------- | ---------------------------------------------------------------------------- |
| [Air](https://developers.amadeus.com/self-service/category/air) | Search, Booking, Artificial Intelligence, Travel Insights and Utils |
| [Hotel](https://developers.amadeus.com/self-service/category/hotel) | Search, Booking, Travel Insights |
| [Destination Content](https://developers.amadeus.com/self-service/category/destination-content) | Location |
| [Trip](https://developers.amadeus.com/self-service/category/trip) | Artificial Intelligence and Utils |

## SDKs

Because there is life beyond `curl`.

- [Python](https://github.com/amadeus4dev/amadeus-python)
- [Ruby](https://github.com/amadeus4dev/amadeus-ruby)
- [Node](https://github.com/amadeus4dev/amadeus-node)
- [Java](https://github.com/amadeus4dev/amadeus-java)
- [Swift](https://github.com/amadeus4dev/amadeus-swift)

`pull requests` are always welcome :-)

## Cheat Sheet

We normally bring some printed copies to the hackathons, but for your convenience, [here](https://github.com/amadeus4dev/hackathon-starter/blob/master/cheatsheets/amadeus4dev.pdf) you have the pdf version.

Let's save the planet!

## Postman

If you love [Postman](https://www.getpostman.com/) as we do, you'll be glad to see [our public postman collection](https://documenter.getpostman.com/view/2672636/RWEcPfuJ).

New to Postman? Don't miss our [How to play with Self-Service APIs with no code](https://developers.amadeus.com/blog/read?tab=0&category=Technical%20tips&id=573&dateId=4&year=2019) article in our blog.

## Examples

- All SDK `README` files contain sample codes.
- The following table contains some showcases which integrate some of the [Self-Service APIs](https://developers.amadeus.com/self-service/):

| Repository | APIs used | Technologies |
| ----------------------------------------------- | ---------------------------------------------------------------------------- | ------------------------------------------------------|
| [amadeus-flight-booking-node](https://github.com/amadeus4dev/amadeus-flight-booking-node) | Flight Offers Search, Flight Offers Price, Flight Create Order, Airport & City Search | Node, Vue.js |
| [amadeus-flight-booking-django](https://github.com/amadeus4dev/amadeus-flight-booking-django) | Flight Offers Search, Flight Offers Price, Flight Create Order, Airport & City Search | Python, django |
| [smart-flight-search](https://github.com/amadeus4dev/smart-flight-search) | Flight Low-fare Search, Flight Choice Prediction, Trip Purpose Prediction and Airport & City Search | Python, django |


## Data-Collection

During the hackathon you'll use the `Test environment`, which means that our APIs are using mostly cache data. You can find which data is available on the [Data collection](http://github.com/amadeus4dev/data-collection) repository.

## FAQ

* **When I go to the portal I see two API catalogs: Self-Service and Enterprise. Which one should I use during the Hackathon?**

Amadeus for Developers includes two different offers: Self-Service and
Enterprise, each meeting different customer needs. During the Hackathon you
will use [Self-Service APIs](https://developers.amadeus.com/self-service/) as
Enterprise is tailored to companies with scale needs and leading brands in the
travel industry.

* **When I create an *application* on the portal I see two environments: Testing and Production. What's that?**

Testing environment is the default environment for all new applications. This
is where you will enjoy a fixed free number of free API call quota per month.
When you reach the limit, you will receive an error message. No worries because
you have enough calls for the Hackathon!

Once you feel that your application is ready to be deployed to the Real World™,
you will want to move it to Production Environment. There is no need to move to
Production in a Hackathon unless you are willing to pay!

## Contributing

If something is wrong, confusing or you miss information, please let us know. Send your `pull request` or drop us an [email](mailto:developers@amadeus.com).
