---
title: "How to get the latest updated pages on Gigya online documentation "
date:   2021-01-11T19:20:00+01:00
categories:
  - blog
tags:
  - Gigya
  - documentation

---

After 5 years defining strategy and deploying Gigya/SAP Customer Data Cloud for clients in the context of very large deployments on many different front-end technologies, B2C and B2B scenario with various backend systems, I decided it was time to share my experience.

The first tips I will share with you, is about the online documentation of Gigya : https://developers.gigya.com/

## Latest pages created or modified
Gigya online documentation is constantly updated and it is not obvious to retrieve the pages that have been modified.

The online documentation is based on Confluence from Atlassian. Therefore CQL queries can be executed to get the latest modified pages using the search functionality. 

As an example, the following link is used to retrieve the pages modified one month from now :

[https://developers.gigya.com/dosearchsite.action?cql=lastmodified+%3E%3D+now(%27-1M%27)+and+type+%3D+%22page%22+order+by+lastmodified+desc](https://developers.gigya.com/dosearchsite.action?cql=lastmodified+%3E%3D+now(%27-1M%27)+and+type+%3D+%22page%22+order+by+lastmodified+desc)

## New Features Released
The home page provides an interesting link to follow the new features released : [Latest Releases] [gigya-release]

## Important platform information or changes 
Some other important information requires digging the site. 

You will find important information on the left navigation menu under release notes :

![2021-01-11-gigya-release-menu](/assets/images/2021-01-11-Latest%20Gigya%20doc%20update/2021-01-11-gigya-release-menu.png)

[gigya-release]: https://developers.gigya.com/display/GD/Release+Notes	"Gigya release notes"
