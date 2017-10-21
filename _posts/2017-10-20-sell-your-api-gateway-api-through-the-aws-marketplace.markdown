---
published: true
layout: post
title: Selling Your AWS API Gateway Driven API Through The AWS Marketplace
date: 2017-10-20T14:00:00.000Z
tags:
  - API Evangelist
  - Management
  - Monetization
  - Plans
image: >-
  https://s3.amazonaws.com/kinlane-productions/algo-rotoscope/stories/cargo-ship-on-sea_diego_rivera1.jpg
---
<p><img src="https://s3.amazonaws.com/kinlane-productions/algo-rotoscope/stories/cargo-ship-on-sea_diego_rivera1.jpg" align="right" width="45%" style="padding: 15px;" /></p>I am getting intimate with AWS API Gateway. Learning about what it does, and what it doesn't do. The gateway brings a number of essential API management elements to the table, like issuing keys, establishing plans, and enforcing rate limits. However, it also lacks many of the other active elements of API management like billing for usage, which is an important aspect of managing API consumption for API providers. With AWS, things tend to work like legos, meaning many of their services work together to deliver a larger picture, and I've been learning more about how AWS API Gateway works with the AWS Marketplace to deliver some of the business of API features I'm looking for. 

[Here is the blurb from the AWS API Gateway documentation regarding how you can setup AWS API Gateway to work with AWS Marketplace](http://docs.aws.amazon.com/apigateway/latest/developerguide/sell-api-as-saas-on-aws-marketplace.html), making your API available for sale as a SaaS service:

> After you build, test, and deploy your API, you can package it in an API Gateway usage plan and sell the plan as a Software as a Service (SaaS) product through AWS Marketplace. API buyers subscribing to your product offering are billed by AWS Marketplace based on the number of requests made to the usage plan.<br /<br />
> To sell your API on AWS Marketplace, you must set up the sales channel to integrate AWS Marketplace with API Gateway. Generally speaking, this involves listing your product on AWS Marketplace, setting up an IAM role with appropriate policies to allow API Gateway to send usage metrics to AWS Marketplace, associating an AWS Marketplace product with an API Gateway usage plan, and associating an AWS Marketplace buyer with an API Gateway API key. Details are discussed in the following sections.<br /<br />
> To enable your customers to buy your product on AWS Marketplace, you must register your developer portal (an external application) with AWS Marketplace. The developer portal must handle the subscription requests that are redirected from the AWS Marketplace console.

While it is not exactly the billing model I'm looking for in my API management layer currently, it provides a compelling look at selling your APIs in a marketplace setting. [There are a growing number of APIs available in the AWS marketplace](http://apievangelist.com/2017/09/08/cloud-marketplace-becoming-the-new-wholesale-api-discovery-platform/), but still less than a hundred from what I can tell. Smells like an opportunity for API providers to step up and publish their APIs. The linkage between AWS API Gateway usage plan and AWS Marketplace product makes a lot of sense when you think about having an APIs as a product focus for your organization. I will be writing more about this relationship in the future, as I think it reflects how we should be thinking about our API service composition, and how we craft our API usage plans. 

I'm going to setup one of my simple, more utility style APIs, like screen capture, or proper noun search, and deploy using AWS API Gateway, then publish as an AWS Marketplace product. I want to have a clear view of what it takes, and what the on-boarding process looks like for a consumer. Another thing I'm interested in doing, is how can I also offer a more wholesale version of these APIs. Meaning, I'm not metering their usage with AWS API Gateway and billing via AWS Marketplace. It will be a separate product that gets deployed in their AWS infrastructure as an EC2, RDS, and maybe AWS API Gateway, where they aren't billed by usage, and billed by the implementation. This is a model I've been watching, considering, and thinking about for some time, but only now getting to where the public cloud infrastructure is able to support this type of API deployment and management. It will be interesting to see what I can make work.