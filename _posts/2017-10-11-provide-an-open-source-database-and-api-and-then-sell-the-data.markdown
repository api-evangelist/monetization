---
published: true
layout: post
title: >-
  Provide An Open Source Threat Information Database And API Then Sell Premium
  Data Subscriptions
date: 2017-10-11T15:00:00.000Z
tags:
  - API Evangelist
  - Security
  - Monetization
  - Data
  - Database
  - Deployment
image: >-
  https://s3.amazonaws.com/kinlane-productions/algo-rotoscope/stories/old-door-lock_copper_circuit.jpg
---
<p><img src="https://s3.amazonaws.com/kinlane-productions/algo-rotoscope/stories/old-door-lock_copper_circuit.jpg" align="right" width="40%" style="padding: 15px;" /></p>I was doing some [API security research](http://security.apievangelist.com) and stumbled across [vFeed](https://github.com/toolswatch/vFeed), a "[Correlated Vulnerability and Threat Intelligence Database Wrapper](https://github.com/toolswatch/vFeed)", providing a JSON API of vulnerabilities from the vFeed database. The approach is a Python API, and not a web API, but I think provides an interesting blueprint for open source APIs. What I found interesting (somewhat) from the vFeed approach was the fact they provide an open source API, and database, but if you want a production version of the database with all the threat intelligence you have to pay for it.

I would say their technical and business approach needs a significant amount of work, but I think there is a workable version of it in there. First, I would create a Python, PHP, Node.js, Java, Go, Ruby version of the API, making sure it is a web API. Next, remove the production restriction on the database, allowing anyone to deploy a working edition, just minus all the threat data. There is a lot of value in there being an open source set of threat intelligence sharing databases and API. Then after that, get smarter about having a variety different free and paid data subscriptions, not just a single database--leverage the API presence.

You could also get smarter about how the database and API enables companies to share their threat data, plugging it into a larger network, making some of it free, and some of it paid--with revenue share all around. There should be a suite of open source threat information sharing databases and APIs, and a federated network of API implementations. Complete with a wealth of open data for folks to tap into and learn from, but also with some revenue generating opportunities throughout the long tail, helping companies fund aspects of their API security operations. Budget shortfalls are a big contributor to security incidents, and some revenue generating activity would be positive.

So, not a perfect model, but enough food for thought to warrant a half-assed blog post like this. Smells like an opportunity for someone out there. Threat information sharing is just one dimension of my API security research where I'm looking to evolve the narrative around how APIs can contribute to security in general. However, there is also an opportunity for enabling the sharing of API related security information, using APIs. Maybe also generating of revenue along the way, helping feed the development of tooling like this, maybe funding individual implementations and threat information nodes, or possibly even fund more storytelling around the concept of API security as well. ;-)
