---
title: "Office Doc Attachments Display Service for Early Mobile Web Devices"
date: 2002-01-08
featured: true
description: "This prototype service allowed users to forward email to a service that would email back a link where they could securely view the contents on an early mobile web or WAP device."
tags: ["C++","Office OLE Automation","WAP","HTML"]
image: "/img/WAPscreen.webp"
link: ""
fact: "This prototype service allowed users to forward email to a service that would email back a link to a location where they could view the attachment on an early mobile web or WAP device."
weight: 500
sitemap:
  priority : 0.8
---
In 2000, mobile data technology was just beginning to sprout in the business world.  Microsoft was working on Windows Mobile while Palm were the darling of keyboard warriors.  Before desktop VPN standards had made the jump to mobile devices, Infowave was ahead of its time creating connectors that gave mobile devices access to companies' resources with their firewalls - extending applications previously only available while on-site to the mobile workers of the world.

When the Gen2 project came to an end, I was asked to join a R&D team creating prototypes for future Infowave products focused on experimenting with mobile services that did not yet exist.  During this time, I created a prototype server which would allow mobile device users to view Microsoft Office documents they received in their email.  At the time, mobile devices could not view Office documents natively and this service allowed any device.  A user would forward the email to a predetermined email address and a server would extract the Office document, convert that document to HTML, and publish it on a web server.  The user would receive an email with a custom unique link, protected by their enterprise credentials, that they could navigate to with their mobile browser or WAP browser, allowing users to finally view Office documents on early mobile devices.  This prototype was created with Microsoft Server, Microsoft C++, Office OLE Automation.

_An AI generated picture of what a WAP -enabled phone may have displayed.  Remember, this was a time when there was no way to view a Microsoft Office document on a mobile device._

![A MS Office Doc on a WAP capable mobile device](/img/WAPscreen.webp)

-----

_A litte more about my time at Infowave..._

_The first team I joined was a partnership between Infowave and Intel (called Gen2) working on porting Infowave's Enterprise Connector on a prototype mobile device intended for future market release.  This incredible device was way ahead of its time.  Based on a Gentoo linux platform and bleeding-edge 800x600 screen equipped with a stylus in a form factor similar to a Game Boy Advance.  I was responsible for porting Infowave's Enterprise Connector components to that platform.  This involved many cross-company meetings with Intel and weekly travel from Vancouver to Hillsborough, Oregon for collaborative work._

_At one point during the project, Intel was dissatisfied with the effort level to build and install the product consistenly, threatening to end their relationship with Infowave.  In response, myself and another other developer took over those responsibilities working 72 hours straight, organizing and creating a repeatable and consistent build and install process.  Thus salvaging the relationship and contract for Infowave._

_And then began the early 2000s tech crash and Infowave began a long series of restructurings.  During this time and sadly only for a short time, i was transferred to a team where I was responsible for the Installshield based installer._
