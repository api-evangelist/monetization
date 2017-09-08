---
published: true
layout: post
title: Decoupling The Business Of My Human Services Microservice
date: 2017-08-14T12:00:00.000Z
tags:
  - API Evangelist
  - Monetization
  - Plans
  - Microservices
image: >-
  https://s3.amazonaws.com/kinlane-productions/algo-rotoscope/stories/containership_dali_three.jpg
---
<p><img src="https://s3.amazonaws.com/kinlane-productions/algo-rotoscope/stories/containership_dali_three.jpg" align="right" width="40%" style="padding: 15px;" /></p>[I've been looking at my human services API work through a microservices lens, triggered by the deployment of a reduced functionality version of the human services implementation I was working on this week](https://apievangelist.com/2017/08/14/some-microservice-thoughts-around-my-human-services-api-work/). I'm thinking a lot about the technical side of decoupling services using APIs, but I want to also take a moment and think about the business side of decomposing services, while also making sure they are deployed in a way that meets both the provider and consumer side of the business equation. My human services microservice implementation is in the public service, which is a space where the business conversation often seems to disappear behind closed doors, but in reality needs to be front and center with each investment (commit) made into any service.

Let's take a moment to look at the monetization strategy and operational plan for my human service microservice. Yes, a public data microservice should have a monetization strategy and plan for operating and remaining sustainable. The goals for this type of microservice will be radically different than it would be for a commercial microservice, but it should have one all the same.

- Monetization - How am I evaluating the investment into this project alongside any value that is generated, which I can potentially capture or exchange some value for some money to keep going.
	- Acquisition - What did it take for me to acquire the data and skills necessary to make the deployment possible.
    - Development - What time was invested in setting up the platform, developing the schema, data, definitions, code, and visual elements.
    - Operations - What does it take to operate the service? Maintain it, answer questions, provide support, and other realities of providing an online service today.
    - Direct Value - What are the direct benefits of having this service available to people looking for human services, or organizations looking to provide human services.
    - Indirect Value - What are the indirect benefits of having this service available, like increased conversation around human services, or maybe traffic and awareness of the Open Referral organization.    
    - Partners - What partnership opportunities are actively being sought out, or will be opened up by having this service available.
    - Reporting - What type of reporting is necessary to operate and monetize this service, from tracking page views to understanding who is integrated with the data, and consuming data via APIs, or possibly through continuous integration of the Github repository.
- Plan - What is my plan for making this service available to the public, partners, or maybe internally use across my own projects.
	- Elements - My human services location API is designed to be publicly available, forkable, and reusable by anyone.
    - Limits - There are no limits on how each human services microservice can be used, or forked and reused. Ideally, any implementation provides attribution, and acknowledges the source of framework or data, but there really are no rules.
	- Metrics - I am measuring unique page views on each page, including of the machine readable YAML, JSON, and other formats. I'm also tracking on stars, forks, and commits for each service.
    - Commercial - Providing a clear track for commercial vendors to understand that the project needs their support, and can be improved upon, and evolved through their underwriting and support.

I need to have a coherent snapshot of what I've invested into each of my service. I need to have a base plan for how I will be executing the business side of this service--even if it just making something available for free. There are two dimensions to this conversation: 1) My view as the creator of this service 2) The view of folks who fork and implement as a service. Both dimensions should have a monetization snapshot, and a plan for executing within this business snapshot. I need all of this decoupled from any other service I am offering, but ideally they all use a common set of reusable patterns, just like the technical aspects of my microservices effort.

Just like needing the compute, database, DNS, and other technical layers to be stable and scalable across my microservices, I need the costs associated with these elements predictable and affordable. I need to know what it costs to define, design, deploy, manage, and deprecate my services. I need to know the best path forward for making them public, keeping them private, and being honest with commercial partners about the value that is being generated, both directly and indirectly. I need a way to report my costs, and revenue across hundreds or thousands of these services. I need to be able to scale this both horizontally across many services, but also vertically for single services which get deployed over and over, reused and continuously integrate wherever they are needed using Github.

I'll keep applying this model across my human services project. I'm thinking that I'm going to be developing a whole buffet of human service microservices that run a 100% on Github like this, but I am also playing around with other varietals that run on other popular cloud platforms as well. I'm not one to subscribe to any particular API dogma, I'm just looking to explore what is possible, and do all of it as cheaply as I possibly scan, growing the number of projects I'm able to tackle. Of course, none of this would be possible without my partners funding my work, and helping me connect the technical and business aspects of doing API Evangelist.
