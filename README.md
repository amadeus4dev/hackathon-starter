# Hackathon Starter

Have you been in a hackathon in the past? Time flies! We have prepared this quick reference document for you to get familiar with our APIs.

Happy Hacking!

# Table of Contents

- [Getting Started](#getting-started)
- [APIs](#apis)
- [SDKs](#sdks)
- [Cheat sheet](#cheat-sheet)
- [Guides](#tutorials-and-guides)
- [Postman](#postman)
- [Examples](#examples)
- [Data Collection](#data-collection)
- [FAQ](#faq)
- [Contributing](#contributing)


## Getting Started

First of all, you need to create an account:

1. Go to [our portal](https://developers.amadeus.com) and click on [register](https://developers.amadeus.com/create-account).
2. Fill in the form using a valid email address and click on the `Create account` button. A confirmation email will be sent to the email address you have just registered.
3. Open your mail and click on `Activate your account`.

What's next? Our [get started guide](https://developers.amadeus.com/get-started/get-started-with-self-service-apis-335) contains detailed information about how to get your API key and make your first API call.

The APIs use [OAuth2](https://en.wikipedia.org/wiki/OAuth) as authentication mechanism. The [authorization guide](https://amadeus4dev.github.io/developer-guides/API-Keys/authorization/) provides deep technical information on how to get a token in order to perform API calls.

## APIs

| Category
| ----------------------------------------------- 
| [Covid-19 & Travel Safety](https://developers.amadeus.com/self-service/category/covid-19-and-travel-safety)
| [Flights](https://developers.amadeus.com/self-service/category/flights)
| [Hotels](https://developers.amadeus.com/self-service/category/hotels) 
| [Cars and Transfers](https://developers.amadeus.com/self-service/category/cars-and-transfers) 
| [Itinerary management](https://developers.amadeus.com/self-service/category/itinerary-management)
| [Market insights](https://developers.amadeus.com/self-service/category/market-insights)

## SDKs

Because there is life beyond `curl`.

- [Python](https://github.com/amadeus4dev/amadeus-python)
- [Java](https://github.com/amadeus4dev/amadeus-java)
- [Node](https://github.com/amadeus4dev/amadeus-node)

## Cheat sheet

We normally bring some printed copies to the hackathons, but for your convenience check out the [web version](https://possible-quilt-2ff.notion.site/Cheat-sheet-e059caf4fcd342b78705f9f3d6f88f1d). 

Let's save the planet!

## Tutorials and guides

In the [Developer Guides](https://amadeus4dev.github.io/developer-guides/examples/prototypes/) you can find tutorials to help you make the most of our APIs. 

You can also find a list of [blog articles](https://developers.amadeus.com/blog/category/tutorials?page=1&count=5) and [videos](https://www.youtube.com/channel/UCwI48vMwtiE-hra2RAtk1PQ) to help you build travel apps with several Amadeus APIs and technologies.

## Postman

If you love [Postman](https://www.getpostman.com/) as we do, you'll be glad to see [our public Postman workspace](https://www.postman.com/amadeus4dev/workspace/amadeus-for-developers-s-public-workspace/collection/2672636-27471449-d2ca-a8c4-1399-6b0cfbddd079).

New to Postman? Don't miss the [How to play with Self-Service APIs with no code](https://developers.amadeus.com/blog/how-to-play-with-self-service-apis-with-no-code-using-postman) article in our blog.

## Examples

Explore all the self-contained [code examples](https://amadeus4dev.github.io/developer-guides/examples/code-example/) as well as [prototypes](https://amadeus4dev.github.io/developer-guides/examples/prototypes/). 

## Data collection

During the hackathon you'll use the `Test environment`, which means that our APIs are using cached data. You can find which data is available on the [data collection](http://github.com/amadeus4dev/data-collection) repository.

## FAQ

* **When I go to the portal I see two API catalogs: Self-Service and Enterprise. Which one should I use during the Hackathon?**

Amadeus for Developers includes two different offers: Self-Service and
Enterprise, each meeting different customer needs. During the Hackathon you
will use [Self-Service APIs](https://developers.amadeus.com/self-service/) as
Enterprise is tailored to companies with scale needs and leading brands in the
travel industry.

* **When I create an *application* on the portal I see two environments: Test and Production. What's that?**

The Test environment is the default environment for all new applications. This
is where you will enjoy a fixed free number of free API call quota per month.
When you reach the limit, you will receive an error message. No worries because
you have enough calls for the Hackathon!

Once you feel that your application is ready to be deployed to the Real World™,
you will want to move it to the Production environment. There is no need to move to
production in a Hackathon unless you are willing to pay!

## Contributing

If something is wrong, confusing or you miss information, please let us know. Send your `pull request` or create an `issue` in the repository. 
