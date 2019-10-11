---
layout: default
title: "Theo Lebrun - Blog"
---

## Welcome

I am a Data Engineer with 5+ years of experience and an open-source lover. Besides IT, I am a sports fan and traveler.

Currently living life in the Big Apple, I enjoy resolving daily challenges at my work while enjoying the New-York active life.

My skills are primarily focused on Data because I have good expertise in technologies like Kafka, EMR and Spark. I also have a big Java and Spring background since I have been using those technologies for more than five years. Cloud technologies are part of my main skills, especially AWS since I have two certifications.

I have a very good knowledge of [JHipster](https://www.jhipster.tech/) and I can provide expertise about it. I have been using JHipster for more than 3 years and [contributed](https://github.com/jhipster/generator-jhipster/commits?author=Falydoor) to the project.

## Blog posts

{% for post in site.posts %}
- {{ post.date | date: "%Y-%m-%d" }} - [{{ post.title }}]({{ post.url }})
{% endfor %}

## Talks

- JHipster NYC
	- 2019-02-22 - [Workshop - Introduction to Vue.js with JHipster](https://www.meetup.com/JHipster-NYC/events/258529587/)
	- 2018-08-21 - [Brace yourself, JHipster 5 is out](https://www.meetup.com/JHipster-NYC/events/251106398/)

## Cool projects I maintain

- [Hipslacker, a Slack bot for JHipster](https://github.com/jhipster/hipslacker)
- [Limesurvey-rc, a Java 8 client Limesurvey](https://github.com/Falydoor/limesurvey-rc)
- [EveSmartTrader, a trade generator for the game EVE Online](https://github.com/Falydoor/EveSmartTrader)
- [My dotfiles](https://github.com/Falydoor/settings)