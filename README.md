# Hackathon Starter

Have you been in a hackathon in the past? Time flies! We have prepared this quick reference document for you to get familiar with our APIs.

Happy Hacking!

# Table of Contents

- [Getting Started](#getting-started)
- [APIs](#apis)
- [SDKs](#sdks)
- [Cheat Sheet](#cheatsheet)
- [Guides](#guides)
- [Postman](#postman)
- [Examples](#examples)
- [Data Collection](#data-collection)
- [FAQ](#faq)
- [Contributing](#contributing)


## Getting Started

First of all, you need to create an account:

1. Go to [our portal](https://developers.amadeus.com) and click on [register](https://developers.amadeus.com/create-account)
2. Fill in the form using a valid email address and click on the `Create account` button. A confirmation email will be sent to the email address you have just registered.
3. Open your mail and click on `Confirm my account`.

What's next? Our [get started guide](https://developers.amadeus.com/get-started/category?id=80&durl=335&parentId=NaN) contains detailed information about how to get your API key and make your first API call.

The APIs use [OAuth2](https://en.wikipedia.org/wiki/OAuth) as authentication mechanism. The [authorization guide](https://developers.amadeus.com/self-service/apis-docs/guides/authorization) provides deep technical information on how to get a token in order to perform API calls.

You can take a look at our introduction videos helping you to get started:
- [Introduction to Amadeus for Developers](https://www.youtube.com/watch?v=O-WWriCnRco&list=PLBehidtj-OipoBNqwOIGVJ1L_pSnJADXi&index=2&t=0s)
- [Amadeus for Developers Self-Service API Catalog](https://www.youtube.com/watch?v=U9vhUg7G2_4&list=PLBehidtj-OipoBNqwOIGVJ1L_pSnJADXi&index=3&t=0s)
- [Getting Started with Amadeus for Developers Self-Service APIs](https://www.youtube.com/watch?v=NhRcl_Howus&list=PLBehidtj-OipoBNqwOIGVJ1L_pSnJADXi&index=4&t=0s)
- [Amadeus for Developers Hackathon Resources](https://www.youtube.com/watch?v=GE5qk9ksMtQ&list=PLBehidtj-OipoBNqwOIGVJ1L_pSnJADXi&index=5&t=0s)

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
- [iOS](https://github.com/amadeus4dev/amadeus-ios) (Swift)
- [Android](https://github.com/amadeus4dev/amadeus-android) (Kotlin)

## CheatSheet

We normally bring some printed copies to the hackathons, but for your convenience, [here](https://github.com/amadeus4dev/hackathon-starter/blob/master/cheatsheets/amadeus4dev.pdf) you have the pdf version.

Let's save the planet!

## Guides
- [Build a Hotel Booking Engine](https://developers.amadeus.com/blog/build-hotel-booking-engine-amadeus-api)
- [Build a Flight Booking Engine](https://developers.amadeus.com/blog/tutorial-booking-engine-amadeus-flight-booking-api)
- [Build a Travel iOS app](https://developers.amadeus.com/blog/build-ios-app-with-amadeus-apis-swift-sdk)
- [Build a Travel PHP app](https://developers.amadeus.com/blog/how-to-integrate-amadeus-api-in-php)
- [Build a Travel Python/Django app](https://developers.amadeus.com/blog/amadues-api-django-python-sdk)
- [Airport & City Search MERN stack](https://developers.amadeus.com/blog/airport-autocomplete-app-with-the-mern-stack)
- [Airport & City Search with Django + JQuery](https://developers.amadeus.com/blog/django-jquery-ajax-airport-search-autocomplete)
- [Performing multi-city search with Flight Offers Search](https://developers.amadeus.com/blog/multi-city-flight-search-amadeus-api)
- [Fake PNR dataset for machine learning](https://developers.amadeus.com/blog/free-fake-pnr-sample-data)

## Postman

If you love [Postman](https://www.getpostman.com/) as we do, you'll be glad to see [our public postman collection](https://documenter.getpostman.com/view/2672636/RWEcPfuJ).

New to Postman? Don't miss our [How to play with Self-Service APIs with no code](https://developers.amadeus.com/blog/how-to-play-with-self-service-apis-with-no-code-using-postman) article in our blog.

## Examples

- All SDK `README` files contain API calls samples .
- You can find all the endpoints in self-contained [code examples](https://github.com/amadeus4dev/amadeus-code-examples), ready to be used.
- The following table contains some showcases/prototypes which integrate some of the [Self-Service APIs](https://developers.amadeus.com/self-service/):

| Repository | APIs used | Technologies |
| ----------------------------------------------- | ---------------------------------------------------------------------------- | ------------------------------------------------------|
| [amadeus-flight-booking-node](https://github.com/amadeus4dev/amadeus-flight-booking-node) | Flight Offers Search, Flight Offers Price, Flight Create Order, Airport & City Search | Node, Vue.js |
| [amadeus-flight-booking-django](https://github.com/amadeus4dev/amadeus-flight-booking-django) | Flight Offers Search, Flight Offers Price, Flight Create Order, Airport & City Search | Python, django |
| [amadeus-smart-flight-search-django](https://github.com/amadeus4dev/amadeus-smart-flight-search-django) | Flight Offers Search, Flight Choice Prediction, Trip Purpose Prediction and Airport & City Search | Python, django |
| [amadeus-flight-search-wordpress-plugin](https://github.com/amadeus4dev/amadeus-flight-search-wordpress-plugin) | Flight Offers Search| PHP, wordpress |
| [amadeus-airport-city-search-mern](https://github.com/amadeus4dev/amadeus-airport-city-search-mern) | Airport & City Search | Node, express, React |
| [amadeus-trip-purpose-django](https://github.com/amadeus4dev/amadeus-trip-purpose-django) | Trip Purpose Prediction | Python, django |
| [amadeus-hotel-search-swift](https://github.com/amadeus4dev/amadeus-hotel-search-swift) | Hotel Search | Swift |
| [amadeus-hotel-booking-django](https://github.com/amadeus4dev/amadeus-hotel-booking-django) | Hotel Search, Hotel Booking| Python, django |
| [amadeus-hotel-area-safety-pois-django](https://github.com/amadeus4dev/amadeus-hotel-area-safety-pois-django) | Hotel Search, Points of Interest, Safe Place| Python, django |


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
