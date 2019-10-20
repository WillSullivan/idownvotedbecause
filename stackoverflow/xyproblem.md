---
title: XY Problem
byline: asking about attempted solution rather than actual problem
permalink: xyproblem/
categories: "Stack Overflow"
redirect_from:
  - XYProblem/
  - XYproblem/
  - XY-Problem/
  - XY-problem/
  - xy-problem/
  - XYProblem
  - XYproblem
  - XY-Problem
  - XY-problem
  - xy-problem

---
## The [XY](http://www.perlmonks.org/index.pl?node_id=542341) [problem](https://mywiki.wooledge.org/XyProblem) is asking about your attempted *solution* rather than your *actual problem.* {#introduction}

That is, you are trying to solve problem `X`, and you think solution `Y` would work, but instead of asking about `X` when you run into trouble, you ask about `Y`.

## Why this is a problem {#whythisisaproblem}
This can lead to frustration by people who are trying to help you solve the problem because by the time you ask about it, the solution that you need help with might not have any obvious connections to the problem that you are trying to solve.

## Why this is worth a downvote {#whythisisworthadownvote}
By not decribing the actual problem, it becomes impossible to point the asker in the direction of another, maybe better approach

## How to Avoid {#howtoavoid}

To avoid falling into this trap, always include information about a broader picture along with any attempted solution.  If someone asks for more information, or especially a more specific question, do provide details.  If there are other solutions which you believe will be suggested and which you've already ruled out, then don't try to avoid going over them again – instead state why you've ruled them out, as this gives more information about your requirements and helps others provide better answers.


# An Example {#anexample}

A recent IRC conversation for illustration:

> **Q:** Is there a function to return a string between two delimiters?  

> **B:** i don't understand what you mean, but i doubt there's already a function  

> **C:** split and slice  

> **D:** partition too  

> **Q:** I tried partition  
> **Q:** I was trying to use built-ins to get the number between something like this in a string "attribute1: 50.223, attribute2: 442.1"  

> **D:** why not just parse the string?  

> **Q:** I thought there may have been some built in parsing stuff  

> **D:** pairs = [x.strip() for x in s.split(",")]; attribs = {k: v for x in pairs for k, v in [x.split(": ")]}  
> **D:** there's a few libraries, but simplistic formats are easy enough -- if you don't care about error handling  
> **D:** changing the source to use a well known format, e.g. json or yaml, is preferred when possible  

> **Q:** This code actually comes from HTML  
> **Q:** but I don't know how to parse Javascript with HTMLParser or whatever it's called  

> **D:** is it merely embedded in html, or some mangled version of html?  

> **Q:** It's embedded in the HTML  

> **D:** if it's javascript (and that is, except for missing outer braces), json can probably parse it  

> **Q:** thanks  

> **D:** I didn't say it explicitly: json only parses data structures, not js code  

> **Q:** That's all I need parsed is a data structure  

The problem is really about how to parse JavaScript data structures, not find "a string between two delimiters", yet it takes quite a bit of time and intuition to get to the real issue.

This is easier to do in a fully interactive chat (regardless of what mode), but on a SE site, where you polish a post a bit, post it, and then have 5-30 mins, or longer, before feedback, it really helps to head in the right direction from the start.
## Leave a comment! {#leaveacomment}
Once you have done this, leave a comment to the person who sent you this link. They will be happy to retract their downvote.

## Did this page help you?
This website is here for everyone's benefit, most importantly yours! If this did <i>not</i> help you, or if you would
like to leave feedback, please **[create an Issue regarding this page on GitHub,](https://github.com/WillSullivan/IDownvotedBecause/issues/new) or [submit an improvement directly.](https://github.com/WillSullivan/IDownvotedBecause/edit/master/{{ page.path }})**

--------

source:[https://meta.stackexchange.com/questions/66377/what-is-the-xy-problem/66378#66378](https://meta.stackexchange.com/questions/66377/what-is-the-xy-problem/66378#66378)
