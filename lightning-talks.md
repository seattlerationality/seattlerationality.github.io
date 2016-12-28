---
layout: page
title: Lightning Talks
permalink: /lightning-talks/
_example_talks: # Just to show the schema; we can delete this once we have some real talks up.

  -

    speaker: Spencer Pearson
    topic: Explore vs. Exploit
    date: 2016-04-18
    youtube_code: jhFDyDgMVUI

  -

    speaker: Lauren Lee
    topic: Learning Networks
    date: 2016-12-19
    youtube_code: jhFDyDgMVUI

---

Our reading groups often start with somebody giving a short talk. Here are some examples:
{% unless page.talks %}
* (none recorded/uploaded yet)
{% endunless %}

{% for talk in page.talks %}
* **{{talk.topic}}** (by {{talk.speaker}}, on {{talk.date | date:'%Y %b %d'}})

    <iframe width="560" height="315" src="https://www.youtube.com/embed/{{talk.youtube_code}}" frameborder="0" allowfullscreen></iframe>
{% endfor %}
