---
title: Main Page
permalink: /
layout: page
author: JHill
date: 2017-05-10T03:41:52Z
category: 
---
<div style="width=%100; background:#f9f9f9; border:1px solid #ddd; margin: 1.2em 0 6 px 0;">

<div style="text-align: center;">

<div style="font-family: Algerian; font-size:300%; margin:0; padding:.1em; color:#111;">

Welcome to the 29th Infantry Division Wiki.

</div>

<div style="font-size:150%; border:none; margin:0; padding:.1em; color:#000;">

The guide to your life in the 29th ID.

</div>

</div>

</div>

If you notice any errors or would like to contribute contact the
[Engineer Corps](http://personnel.29th.org/#units/Eng).

## Quick Links

| [Rank Structure](Rank_Structure "wikilink") | [Chain of Command](Chain_of_Command "wikilink")                   | [History of the 29th](History_of_the_29th "wikilink") |
| ------------------------------------------- | ----------------------------------------------------------------- | ----------------------------------------------------- |
| [Awards](Awards "wikilink")                 | [Weapon and Vehicle Guides](Weapon_and_Vehicle_Guides "wikilink") | [Support Staff](Battalion_Support_Staff "wikilink")   |

## FM 21-100 "Soldier's Handbook"

**Required Reading**

This will answer common questions of newly graduated members and help
prevent them from making common mistakes. 

{% assign fm21_100 = site.pages | where: "category", "FM 21-100" %}
{% for page in fm21_100 %}
  - [{{ page.title }}](wiki{{ page.url }})
{% endfor %}

## Policy Handbook

**Required Reading**

All members are required to read and abide by this handbook. Its
contents are very short and concise, so it should not take long to know
and understand the policies you are expected to follow. 

{% assign policy = site.pages | where: "category", "Policy" %}
{% for page in policy %}
  - [{{ page.title }}](wiki{{ page.url }})
{% endfor %}

## Game Specific Wikis

  - [Arma 3 Infobank](http://www.29th.org/wiki/Arma)
  - [Rising Storm Infobank](http://www.29th.org/rs/)
  - [Squad Infobank](http://www.29th.org/wiki/Squad)

## Other

  - [FM 21-20 "Cadet's
    Handbook"](FM_21-20_"Cadet's_Handbook" "wikilink")
  - [Medical Office Wiki](http://29th.org/medical)

