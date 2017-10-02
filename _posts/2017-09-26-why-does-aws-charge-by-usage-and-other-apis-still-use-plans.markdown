---
published: true
layout: post
title: Why Does AWS Charge By Usage And Other APIs Still Use Plans?
date: 2017-09-26T13:00:00.000Z
tags:
  - API Evangelist
  - Monetization
  - Plans
  - Politics of APIs
  - Investment
image: >-
  https://s3.amazonaws.com/kinlane-productions/algo-rotoscope/stories/adam-smith_feed_people.jpg
---
<p><img src="https://s3.amazonaws.com/kinlane-productions/algo-rotoscope/stories/adam-smith_feed_people.jpg" align="right" width="40%" style="padding: 15px;" /></p>[Amazon Web Services recently updated their billing for EC2 instances to be by the second](https://aws.amazon.com/blogs/aws/new-per-second-billing-for-ec2-instances-and-ebs-volumes/), which I really like, because I'll fire up an instance and run for minutes, then shut things down. I'm just looking to process patent downloads, or other intensive workload projects. Beyond just EC2, the rest of Amazon's platform is still very usage based. Meaning, you get charged for whatever you use, with unit pricing for each resource designed to compliment how it gets put to use. You get charged for the hard costs of compute, storage, and bandwidth, but you also see per message, job, entry, and other types of billing depending on the type of resource being delivered via API.

With this model for doing APIs, I'm wondering why so many API providers still have access plans and tiers. I've vented several times that I think service tiers are a legacy of a SaaS way of thinking and does not scale for API consumers. Maybe back when we used a handful of APIs, but the number of APIs I'm using is pushing 50 these days, and I can't alway justify a monthly subscription to get what I need. I'm looking to just get access to valuable API resources, and get billed for whatever I use. If I don't use anything for 6 months, I don't get billed for anything. Also, I want to be able to run large jobs which consume intense amounts of resources without hitting tier and other limits--just charge me for what I use. If I have a $1,000.00 to spend today, let me spend it. Don't make me jump through hoops.

I know the answer to my question regarding why so many API startups do this. It is because the resources being provided via the API isn't the product, us API consumers are. They are looking to ensure a certain level of headcount, monthly, and annual subscribers, so that they can sell us to their investors, and ultimately whoever purchases us like cattle in the end. I'm sure there are other reasons for having pricing tiers, but this is still the primary reason we see SaaS based pricing continue to be so pervasive in an API driven world. For me, if an API provider has tiered pricing, I'll almost always go look elsewhere. I just can't manage 40 or 50 subscriptions, and if the number of APIs keep growing, I can't handle 100-200 subscriptions. I just need to pay for the resources my business needs, and nothing more. I sure don't have time to be a product in your startup cattle auction.

Pay as you go, usage based pricing is one way the cloud giants will suffocate out the small startups in the future. While startups are trying to court investors, and their acquirers, the cloud giants will just offer a competing service, drop the price to run competitors off, then once the coast is clear, raise prices back up to an profitable state. To compete, more API providers will have to go with a utility based pricing strategy, while also offering wholesale versions of their APIs in the marketplaces for AWS, Azure, and Google. I can't help think that things might have been different if the scales didn't tip so hard towards all of us API consumers being the product, and API providers focused more on running businesses, and catering to our real world business needs. Oh well, we got the world we have, I'll just keep plowing forward.
