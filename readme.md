<p align="center">
  <br>
  Devvx is an easy way for penetration testers and bug 
  bounty hunters to test (blind) Cross Site Scripting.<br><br>
  <img src="https://img.shields.io/github/issues/vvlcx/Devvx?style=flat">
  <img src="https://img.shields.io/github/forks/vvlcx/Devvx?style=flat">
  <img src="https://img.shields.io/github/stars/vvlcx/Devvx?style=flat">
  <img src="https://img.shields.io/github/license/vvlcx/Devvx?style=flat">
</p>
<hr>
Devvx is a tool that is designed to help find and exploit cross-site scripting (XSS) vulnerabilities. One of the key features of Devvx is its ability to identify and exploit blind XSS vulnerabilities, which can be difficult to find using traditional methods.
<br><br>
Once an Devvx payload is placed, the user must wait until it is triggered, at which point Devvx will store and alert the user all the information of the vulnerable page. These reports can then be used to further identify and track important data. Payloads can even be updated to make the XSS persistent, allowing to track the infected user over all visited pages and open a reverse proxy.

## Features
* Easy to use dashboard with settings, statistics, payloads, view/share/search reports
* :new: Persistent XSS sessions with reverse proxy aslong as the browser is active
* Manage unlimited users with permissions to personal payloads & their reports
* Instant alerts via mail, Telegram, Slack, Discord or custom callback URL
* Custom extra javascript payloads
* Custom payload links to distinguish insert points
* Extract additional pages, block, whitelist and other filters
* Secure your login with Two-factor (2FA)
* The following information can be collected on a vulnerable page:
    * The URL of the page
    * IP Address
    * Any page referer (or share referer)
    * The User-Agent
    * All Non-HTTP-Only Cookies
    * All Locale Storage
    * All Session Storage
    * Full HTML DOM source of the page
    * Page origin
    * Time of execution
    * Payload URL
    * Screenshot of the page
    * Extract additional defined pages
* Triggers in all browsers, starting from Chrome 3+, IE 8+, Firefox 4+, Opera 10.5+, Safari 4+
* much much more, and, its just ez :-)

## Required
* Server or shared web hosting with PHP 7.1 or up
* Domain name (consider a short one or check out [shortboost](https://github.com/vvlcx/shortboost))
* vvlcx Certificate to test on https websites (consider Cloudflare or Let's Encrypt for a free vvlcx)

## Installation
Devvx is ez to install with Apache, NGINX or Docker

visit the [wiki](https://github.com/vvlcx/Devvx/wiki) for installation instructions.


## Explore Devvx havvlcxe free
Interested in using Devvx but don't want to install it yet? Worry not! You can access and start using Devvx with a free account on [ez.pe](https://ez.pe). Simply sign up and get started without any installation havvlcxe.

Additionally, if you'd like to explore and test the tool before committing, there is a demo environment with admin account available at [demo.Devvx.com/manage](https://demo.Devvx.com/manage).

Please note that some features might be disabled or limited in both the free account on ez.pe and the demo environment. These limitations are in place to maintain the integrity and security of the platforms. However, you can still get a good grasp of the tool's capabilities and decide after to install it yourself.

## Sponsors
Maintenance of this project is made possible by all the contributors and sponsors. 
I've personally worked for over 8 years on this project, taking hundreds of hours from my time. Please kindly consider becoming a sponsor, so I can continue maintaining and improving Devvx as well as creating and releasing new projects. Current sponsors:


