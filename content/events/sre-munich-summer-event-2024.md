---
title: "SRE Munich at Celonis 2024"
date: 2024-07-07T07:30:00+02:00
draft: false
---

We’re excited to announce the next Meetup of the Site Reliability Engineering Munich group for July 10th.
This time around we will be meeting at Celonis . Let's all meet up again, talk about reliability, exchange ideas and see where we can continue to learn on our journey as site reliability engineers (and folks that aspire to be one!).
Meetups are about engaging within the community, so we are looking to everyone to share ideas and learn to ultimately to reduce the risk of disasters.
Please help to spread The Word! Feel free to post this event on social media using the #sremuc hashtag!
You can reach the organizers at muc@sre.xyz (Ideas, Presentations, Comments)

## Agenda

* 6:30 pm Get together with food and drinks
* 7:00 pm Celonis welcomes you to SREmuc
* 7:10 pm Talk 1: Upgrading thousands of stateful applications across a global Kubernetes infrastructure (Michael Lex, ClickHouse)
* 7:40 pm Talk 2: Lessons learned from 15 years DevOps (Paul Stack, System Initiative)
* 8:30 pm Networking + Drinks
* 9:00 pm Leave happy and inspired :)


## Abstracts

### Talk 1: Upgrading thousands of stateful applications across a global Kubernetes infrastructure (Michael Lex, ClickHouse)

How do you upgrade thousands of similar but independent stateful applications running ClickHouse in a controlled way, across tens of regions in all major cloud providers? Full automation is a must - at that scale manual toil is time consuming and error prone. Full control is necessary as well - on-call engineers need to interact with the automation to pause the rollout, resume it or roll back. And most important: the automation needs to be safe - taking into account signals from monitoring systems to automatically detect problems caused by the rollout (and react to them in an appropriate way). A full rollout can take several days - potentially weeks. So any automation must be able to deal with interruptions, intermittent upgrades or even temporary downtime of the automation system itself. With [Temporal.io](Temporal.io) and its "durable execution" paradigm, the rollout automation system developed for the ClickHouse Cloud addresses all those concerns.

[Michael Lex](https://www.linkedin.com/in/michael-lex-a84a9b1b8/) is a seasoned engineer who has worked in various fields ranging from consulting to fast-paced startups. He currently works as an Engineering Manager at Clickhouse where he and his team work on friction-less deployments of stateful applications for thousands of customers.

Slides: [Clickhouse](/slides/2024_07/clickhouse.pdf)

### Talk 2: Lessons learned from 15 years DevOps (Paul Stack, System Initiative)

It's almost 15 years since the inception of DevOps. The core value of DevOps was to break down the silos and improve communication to achieve stability, reliability, availability, and security. In the boom of the ecosystem since that point, it sometimes feels like we've created more silos and stemmed communication in every way with the tooling we have. What if we take the lessons we’ve learned along the way and try to reimagine DevOps tooling to fulfill the original promise of the DevOps movement? What if we could remove the 200% problem (the need to know a specialist language AND a cloud framework) from our tooling? What if we could focus on delivery in a collaborative manner rather than communicating via a series of handoffs via pull requests? It’s time for a second wave of DevOps tools.

In this talk, Paul is going to reflect on the lessons we've learned along the DevOps journey, for example Infrastructure as Code, and talk about the work System Initiative is doing to revolutionize how people collaborate to build and maintain complex infrastructure. System Initiative is the beginning of an ecosystem to create a real-time, multiplayer, multi-modal reinvention of DevOps tooling. System Initiative provides a modern, state of the art approach to infrastructure management that increases productivity with its simulation-based workflow.

Once you see what it’s possible to achieve, you won’t want to settle any longer.

[Paul Stack](https://www.linkedin.com/in/stack72/) is an infrastructure coder and has spoken at various events throughout the world about his passion for continuous integration, continuous delivery and good operational procedures and why they should be part of what developers and system administrators do on a day to day basis. He believes that reliably delivering software is more important than its development. Paul’s passions are the DevOps and Continuous Delivery movements and how they help the entire business and its customers.

Slides: [It's time to rebuild DevOps](/slides/2024_07/it_is_time_to_rebuild_devops.pdf)

## Photos

![photo 1](/photos/2024_07/IMG_1596.JPEG)
![photo 2](/photos/2024_07/IMG_1597.JPEG)
![photo 3](/photos/2024_07/IMG_1598.JPEG)
![photo 4](/photos/2024_07/IMG_1600.JPEG)
![photo 5](/photos/2024_07/IMG_1607.JPEG)
![photo 6](/photos/2024_07/IMG_1609.JPEG)
![photo 7](/photos/2024_07/IMG_1614.JPEG)
![photo 8](/photos/2024_07/IMG_1618.JPEG)
![photo 9](/photos/2024_07/20240710_182135.jpg)

## Participation

We're always looking for 20-45 minute (technical) talks related to the very broad field of Site Reliability Engineering.
Get in touch with the organizers if you'd like to present!

## Legal

There may be audio and video recordings of the talks with the purpose of sharing the learnings and advertising future events. 
By attending the event you give your consent to be recorded.