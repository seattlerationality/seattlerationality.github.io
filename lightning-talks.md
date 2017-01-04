---
layout: page
title: Lightning Talks
permalink: /lightning-talks/
talks:
  - speaker: Spencer Pearson
    topic: Forecaster Scores and Surprise
    date: 2016-04-18
    youtube_code: nxeiOPN7ILk
---

Our reading groups start with an opportunity for people to give short talks on things they're excited about. Here are some examples:

{% for talk in page.talks %}
* **{{talk.topic}}** (by {{talk.speaker}}, on {{talk.date | date:'%Y %b %d'}})

    <iframe width="560" height="315" src="https://www.youtube.com/embed/{{talk.youtube_code}}" frameborder="0" allowfullscreen></iframe>
{% endfor %}
