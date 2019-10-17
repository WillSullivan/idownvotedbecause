---
title: I downvoted because...
byline: — a website designed to help you help others!
---
 [Like this website? Want to take charge of it to ensure it stays around?](https://github.com/WillSullivan/idownvotedbecause/issues/131)
 
# This website is designed to help people understand why you downvoted.

Participation in a reputation-ranked online community comes with its ups and downs. You post something and it gets upvoted when people like or agree with it--*and that's great!*

Unfortunately, it may also receive a downvote because **someone didn't**--and that can stink.

Maybe your post got downvoted, and you're wondering why. Or maybe you're the downvoter, and you want to let the person who owns the post know why you downvoted. This website is **built for you.**

The goal for *I Downvoted Because* (an independent website not affiliated with any reputation-ranked online community) is to give people an **easy, productive and helpful way** to let someone know **what caused your downvote, what they can do to fix it, and why you think they should do so.** It also gives people who experience downvotes a simple way to learn what happened and why. They can also learn what the culture of a community sees as a reason to downvote, and therefore how to reverse it.

## How does this website work?
This website hosts one page per reason for a downvote. Each reason has its own URL in the format

> idownvotedbecau.se/ashortdescriptionofwhy

When you wish to let someone know why you downvoted and how they could reverse it, simply leave a link to the relevant page.

## All the reasons*
Here's the current list of all pages, sorted by community!  Not finding something you want? [See below to learn how to get it!](#you-can-help-make-this-website-better) Please note, this website is not affiliated in any way with any of the organizations or websites below.

{% for cat in site.category-list %}
### {{ cat }}
<ul>
  {% for page in site.pages %}
    {% for pc in page.categories %}
      {% if pc == cat %}
        <li>
          <a href="{{ page.url }}">{{ page.title }}</a>
        </li>
      {% endif %}   <!-- cat-match-p -->
    {% endfor %}  <!-- page-category -->
  {% endfor %}  <!-- page -->
</ul>
{% endfor %}  <!-- cat -->

<small><small><small>**Special thanks to [mrenaud and his answer here](https://stackoverflow.com/a/17913214/1228) for making this section possible.*</small></small></small>

## You can help make this website better!
This website is hosted on [GitHub](https://github.com/WillSullivan/IDownvotedBecause) and served via [GitHub Pages](https://pages.github.com/). This means that if you have a GitHub account you can request changes, updates, and even new pages.  You can do this by [submitting an issue at GitHub](https://github.com/WillSullivan/IDownvotedBecause/issues/new). You can even add them yourself by [forking](https://help.github.com/articles/fork-a-repo/) the website's repository and make the changes as you see fit. Once completed, you can send me, [@willSullivan](https://github.com/willSullivan), a [pull request](https://help.github.com/articles/using-pull-requests/) to add your changes to the website.

