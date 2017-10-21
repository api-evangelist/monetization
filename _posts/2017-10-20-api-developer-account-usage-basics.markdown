---
published: true
layout: post
title: API Developer Account Usage Basics
date: 2017-10-20T11:00:00.000Z
tags:
  - API Evangelist
  - Management
  - Logging
  - Plans
  - Monetization
image: >-
  https://s3.amazonaws.com/kinlane-productions/algo-rotoscope/stories/cargo-ship-on-sea_copper_circuit.jpg
---
<p><img src="https://s3.amazonaws.com/kinlane-productions/algo-rotoscope/stories/cargo-ship-on-sea_copper_circuit.jpg" align="right" width="45%" style="padding: 15px;" /></p>
I'm helping some clients think through their approach to API management. These projects have different needs, as well as different resources available to them, so I'm looking to distill things down to the essential components needed to get the job done. [I spent some time thinking through the developer account basics](http://apievangelist.com/2017/10/20/api-developer-account-basics/), and now I want to break down the aspects of API consumption and usage around these APIs and developer accounts. I want to to think about the moving parts of how we measure, quantify, communicate, and invoice as part of the API management process.

**Having A Plan**
We have developers signed up, with API keys that they'll be required to pass in with each API call they make. The next portion of API management I want to map out for my clients is the understanding and management of how API consumers are using resources. One important concept that I find many API providers, and would be API providers don't fully grasp, is service composition. Something that requires the presence of a variety of access tiers, or API plans, which define the business contract we are making with each API providers. API plans usually have these basic elements:

- **plan id** - A unique id for the plan.
- **plan name** - A name for the plan.
- **plan description** - A description for the plan.
- **plan limits** - Details about limits of the plan.
- **plan timeframe** - The timeframe for limits applied.

There can be more than one plan, and each plan can provide different types of access to different APIs. There might be plans for new users versus verified ones, as well as possibly partners. The why and how of each plan will vary from API provider to provider, but their are all essential to managing API usage. Something that needs to be well defined, in place, with APIs and consumers organized into their respective tiers. Once this is done, we can begin thinking about the next layer, logging.

**Everything Is Logged**
Each call made to the API contains API key which identify the consumer, who should always be operating within a specific plan. Each API call is being logged as part of the web server, and ideally the API management layer, providing timestamped entries for every drop of APIs consumed. These logs are used across API management operations, providing a history of all usage that will be evaluated on a per API, as well as per API consumer level. If a request and response isn't available in the API logs, then it didn't happen.

**Quantifying API Usage**
Every log entry recorded will have the keys for a specific API consumer, as well as the path of the API they are consuming. When this usage is viewed through the lens of the API plan an API consumer is operating within, you have the ability to quantify usage, and place a value on overall consumption by any time frame. This is the primary objective of API management, quantifying who is accessing API resources, and how much they are consuming. This is how valuable API resources are being secured, and in many situations monetized, using simple web APIs.

API usage begins with quantifying what consumers have used, but then there are other dimensions that should be considered as well. For example, usage across API users for a single path, or group of paths. Also possibly usage across APIs and consumers within a particular plan. Then you can begin to look across time periods, regions, and other relevant information, providing a more complete picture of how APIs are being put to use. This awareness is why API providers are employing API management techniques, beyond what can be extracted from database logs, or just website or application analytics--providing a more wholesale view of how APIs are consumed.

**Invoicing For Consumption**
Now that we have all API usage defined, and available through the lens of API plans, we have the option of invoicing for consumption. We know each call API consumers have made, and we have a rate specific for each API as part of the API plans each consumer is subscribed to. All we have to do is the math, and generate an invoice for the designated time period (ie. daily, weekly, monthly, quarterly). Invoicing doesn't have to always be settled with cash, as consumption may be internally, with partners, and with a variety of public consumers. I'd also warn against thinking of consumption always costing the consumer, and sometimes it might be relevant to pay API some consumers for some of their usage--incentivizing a particular type of behavior that benefits a platform.

Measuring, quantifying, and accounting for API consumption is the primary reason companies, organizations, institutions, and government agencies are implementing API management layers. It is how Amazon generates revenue from their Amazon Web Services. It is how Stripe, Twilio, Sendgrid, and other rockstar API providers generate the revenue behind their operations. It is how government agencies are understanding how the public is putting valuable public resources to work. API management is something that is baked into cloud platforms, with a variety of service providers available as well, providing a wealth of solutions for API providers to choose from.

Next I will be looking at the API account and usage layers of API management from the view of API provider, as well as the API consumer via their developer area. Ideally, API management solutions are providing the dashboards needed for both sides of this equation, but in some of the projects I'm working on this isn't available. There is no ready to go dashboard for API providers or consumers to look at when standing up an AWS API Gateway in front of an API, falling short when it comes to going the distance as an API management solution. You can define accounts, issue keys, establish plans and limit manage API consumption, but we need AWS CloudFront, and other services to deliver on API logging, authentication, and other common aspect of management--with API management dashboards being a custom thing when employing AWS for management. One consideration for why you might go with a more robust API management solution, beyond what an API gateway offers.
