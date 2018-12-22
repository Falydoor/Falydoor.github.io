---
layout: default
title: "Theo Lebrun - Blog"
---

## Welcome

My name is Theo Lebrun, I'm a Software Engineer with 5+ years of experience and open-source lover. Beside IT, I'm a sports fan and traveler.

Currently living the life in the Big Apple, I enjoy resolving daily challenges at my work and sharing stories with my coworkers during happy hour.

My skills are mainly focused on the Java and Spring ecosystem. I have a lot of experience in the Cloud technologies, especially with AWS since I own two certifications.

I have a very good knowledge of [JHipster](https://www.jhipster.tech/) and I can provide expertise about it. I've been using JHipster for more than 3 years and [contributed](https://github.com/jhipster/generator-jhipster/commits?author=Falydoor) to the project.

## Blog posts

{% for post in site.posts %}
- {{ post.date | date: "%Y-%m-%d" }} - [{{ post.title }}]({{ post.url }})
{% endfor %}

## Talks

- JHipster NYC
	- 2018-08-21 - [Brace yourself, JHipster 5 is out](https://www.meetup.com/JHipster-NYC/events/251106398/)

## Cool projects I maintain

- [Hipslacker, a Slack bot for JHipster](https://github.com/jhipster/hipslacker)
- [Limesurvey-rc, a Java 8 client Limesurvey](https://github.com/Falydoor/limesurvey-rc)
- [EveSmartTrader, a trade generator for the game EVE Online](https://github.com/Falydoor/EveSmartTrader)
- [My dotfiles](https://github.com/Falydoor/settings)