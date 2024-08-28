---
layout: default
title: "Theo Lebrun - Blog"
---

## Welcome

I am a seasoned Data Engineer and Technology Consultant with a vast experience in cloud computing, databases, and software development. With expertise in a range of tools and technologies including AWS, Kafka, Databricks, and Python, I have helped numerous clients optimize their data pipelines meeting and exceeding their goals.

My technical expertise are matched by my passion for sharing my knowledge with others. I have authored multiple blog posts covering and breaking down technical topics such as high-scaled streaming development with Kafka or Databricks Tips and Tricks. I have also presented in multiple conferences such as DevNexus, Connect.Tech and RVATech Data Summit.

I have a very good knowledge of [JHipster](https://www.jhipster.tech/) and I can provide expertise about it. I have been using JHipster for more than 5 years and also [contributed](https://github.com/jhipster/generator-jhipster/pulls?q=is%3Apr+author%3AFalydoor+is%3Aclosed) to the project.

## Talks

- **2024-08-28** - AWS Community Day New York - [Craft your own Generative AI Chatbot with Amazon Bedrock](https://www.awscommunitynewyork.com/)

- **2024-04-11** - DevNexus - [Build next generation Big Data applications with Delta Lake](https://devnexus.com/archive/devnexus2024/presentations/build-next-generation-big-data-applications-with-delta-lake/) ([Video](https://www.youtube.com/watch?v=K_evPwvEumg))

- **2024-03-09** - DataTune - [Build next generation Big Data applications with Delta Lake](https://www.datatuneconf.com/index.html)

- **2024-01-25** - RVA Data Engineering - [Build next generation Big Data applications with Delta Lake](https://www.meetup.com/rva-data-engineering/events/298171697/) ([Video](https://www.youtube.com/watch?v=xbm8878P758))

- **2023-10-26** - Connect.Tech - [Creating a Modern Web App Using Spring Boot and Vue.js with JHipster](https://2023.connect.tech/session/500852) ([Video](https://www.youtube.com/watch?v=LgEKth5jR58))

- **2023-04-06** - DevNexus - [Creating a Modern Web App Using Spring Boot and Vue.js with JHipster](https://devnexus.com/archive/devnexus2023/presentations/creating-a-modern-web-app-using-spring-boot-and-vue-js-with-jhipster/)

- **2023-03-30** - RVA Tech DataSummit - [Easily transform data in your warehouse using DBT (Data Build Tool)](https://rvatech.com/rvatech-events/2023-rvatech-data-summit/)

- **2020-06-25** - Datastax Webinar - [Successful scale-out data approach for Financial Services with Apache Cassandra™](https://www.datastax.com/resources/webinar/successful-scale-out-data-approach-financial-services-apache-cassandratm) ([Video](https://www.youtube.com/watch?v=mX2CYJVW9So&t=1040))

- **2020-05-13** - VueDC - [Creating a Modern Web App Using Vue.js and Spring Boot with JHipster](https://www.meetup.com/Vue-DC/events/269973905/) ([Video](https://www.youtube.com/watch?v=B5QgxVwnEws))

- **2019-02-22** - JHipster NYC Meetup - [Workshop - Introduction to Vue.js with JHipster](https://www.meetup.com/JHipster-NYC/events/258529587/)

- **2018-08-21** - JHipster NYC Meetup - [Brace yourself, JHipster 5 is out](https://www.meetup.com/JHipster-NYC/events/251106398/)

## Blog posts

{% for post in site.posts %}
- {{ post.date | date: "%Y-%m-%d" }} - [{{ post.title }}]({{ post.url }})
{% endfor %}

## Cool projects I maintain

- [Hipslacker, a Slack bot for JHipster](https://github.com/jhipster/hipslacker)
- [Limesurvey-rc, a Java 8 client Limesurvey](https://github.com/Falydoor/limesurvey-rc)
- [EveSmartTrader, a trade generator for the game EVE Online](https://github.com/Falydoor/EveSmartTrader)
- [My dotfiles](https://github.com/Falydoor/settings)
