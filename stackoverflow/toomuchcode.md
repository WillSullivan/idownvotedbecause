---
title: Too much code
byline: a wall of code isn't helpful
permalink: toomuchcode/
categories: "Stack Overflow"
redirect_from:
  - TooMuchCode
  - Toomuchcode
---
## Please include the _minimum amount of code_ in the question needed to illustrate your problem {#introduction}
Including excessive amounts of code makes it hard for the people who are trying to help find errors.

## Why this is a problem {#whythisisaproblem}
It is really hard to answer a question about a bug in code when the question includes a huge block of code. When this happens, it takes much longer and is much more difficult for other users to search through the code to find the pieces that are relevant to the problem.

## Why this is worth a downvote {#whythisisworthadownvote}
The noise generated from all the code surrounding the error prevents future users from relating the question and answer to their own issue. It also makes it much harder for anyone to determine what the problem is, making it much less likely to get a quick, correct answer. The question is effectively only useful to the asker, is less likely to get answered, and offers little or no value to the developer community as a whole.

Including too much irrelevant code reflects a low effort question. When people are volunteering their time, free of charge, to help answer a question, appreciation can be shown by keeping the code concise--the minimum amount needed to illustrate the problem. 

## What to do next {#whattodonext}
Isolate the issue, and create a Minimal, Complete, Verifiable example ([see the StackOverflow help center for more details](https://stackoverflow.com/help/mcve)). Such an example is generally only a few lines of code, like a function or a database request.

The code should be debugged to identify _the precise spot at which the issue occurs_. It should then either be rewritten from scratch until the issue reappears or the original code should be largely cut through to remove working pieces which are not directly related to the issue.

For markup (html, xml, etc), remove attributes, namespaces, styles and elements that don't have anything to do with the issue.

If something is removed that may play a part in the issue, state so in the question. Users with domain knowledge in the issue will comment when additional information is needed. It is important to be available after posting a question and respond quickly to these requests. Ignoring a question means ignoring people who are trying to help.

The now minimal code can be used to replace the noisy code by editing the question. The edit link can be found at the bottom of the question.

Now the code can be quickly read, understood, and fixed by answerers! Future readers will be able to notice at a glimpse if their issue relates or not.

## Leave a comment! {#leaveacomment}
Once you have done this, leave a comment to the person who sent you this link. They will be happy to retract their downvote.

## Did this page help you?
This website is here for everyone's benefit, most importantly yours! If this did <i>not</i> help you, or if you would
like to leave feedback, please **[create an issue regarding this page on GitHub,](https://github.com/WillSullivan/IDownvotedBecause/issues/new) or [submit an improvement directly.](https://github.com/WillSullivan/IDownvotedBecause/edit/master/{{ page.path }})**
