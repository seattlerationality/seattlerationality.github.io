---
layout: page
title: Blogs
blogs:
  - name: Eukaryote Writes Blog
    topic: "\"A blog about risk, research, and life as a membrane-bound organism.\""
    url: https://eukaryotewritesblog.com/
    feed_url: https://eukaryotewritesblog.com/feed
    authors:
    - Georgia Ray
  - name: Tragedy of the Comments
    topic: "\"Global Catastrophic Risks and how human minds work.\""
    url: https://tragedyofthecomments.wordpress.com/
    feed_url: https://tragedyofthecomments.wordpress.com/feed
    authors:
      - Finan Adamson
  - name: Global Risk Research
    topic: "\"A global catastrophic risk is an event that kills a large percent of the human population. We're a group of researchers who want to help humanity survive into the far future.\""
    url: https://globalriskresearch.org/
    feed_url: https://globalriskresearch.org/feed
    authors:
      - Finan Adamson
      - Jeffrey Ladish
      - Georgia Ray
      - (Evan Gaensbauer)
  - name: Life in a Free Market
    topic: "\"The notions of identity, politics, memetics, and ethics, from a computational perspective.\""
    url: http://lifeinafreemarket.tumblr.com
    feed_url: http://lifeinafreemarket.tumblr.com/rss
    authors:
      - Pasha Kamyshev
  - name: Richard Wu's blog
    topic: "\"This blog is dedicated to all things worth appreciating, be they savory or bittersweet.\""
    url: http://rwu.io/
    feed_url: http://rwu.io/feed
    authors:
      - Richard Wu
  - name: Spencertopia
    topic: "\"Thoughts on cognition and new lenses to see the world through. Also a butt-ton of statistics.\""
    url: http://speezepearson.github.io/blog/
    feed_url: http://speezepearson.github.io/feed.xml
    authors:
      - Spencer Pearson
---

Several Seattle rationalists keep blogs, if you want to get some idea of what we get really enthusiastic about:

{% for blog in page.blogs %}

- __[{{ blog.name | escape }}]({{ blog.url | escape }})__ -- by {{ blog.authors | join: ", " }} ([feed]({{ blog.feed_url | escape}})).
    <br />
    <div style="margin-left: 2em">{{ blog.topic }}</div>

{% endfor %}
