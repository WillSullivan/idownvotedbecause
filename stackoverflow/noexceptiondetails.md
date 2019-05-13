---
title: Missing exception details
byline: your question is missing exception details
permalink: noexceptiondetails/
categories: "Stack Overflow"
redirect_from:
  - noexceptiondetail
  - NoExceptionDetails
  - NoExceptionDetail
  - Noexceptiondetail
  - Noexceptiondetails
---
## We need ALL Exception details to help you! {#introduction}
In your question, you indicated that there was an exception thrown when your code executes. That's good information that we need to help you find a solution. However, in order to find that solution, **we need to know ALL the details that can be found within the exception.** If a question lacks this detailed exception information, it becomes harder for us to help. 

## Why this is a problem {#whythisisaproblem}
The question contained only a part or none of this information, making it harder or impossible to help. Exceptions contain lots of information--information we need to determine what is going on in your code. 

### What details do we need?
Exceptions contain many details about what happened at the time they are thrown. All this information gives us clues about why the exception was thrown.  Details from the exception that we need are

* The Type of the Exception
* The Exception message
* The [stack trace](https://en.wikipedia.org/wiki/Stack_trace)
* All inner Exceptions, their types, messages, and stack traces

Any one (or more) of these may be needed to properly diagnose your problem. If you don't provide this information, we are forced to guess what might have happened.  It is often very simple to gather all this information. Keep reading for hints on how to do this.

## Why this is worth a downvote {#whythisisworthadownvote}
Exceptions contain almost all of the information we, the people trying to help you, need in order to give you a quick answer. When you do not give us this information, we must examine your question in hopes to find clues to the information that would have been readily available had you included Exception details in your question. This wastes the time of people who (for free!) are volunteering to help.

## What to do next {#whattodonext}
Get a text report of all of the contents within it. Remember, the details of the Exception should be captured as text--[do not take an image of the Exception details!]({% link stackoverflow/imageofanexception.md %}) This can usually be accomplished very easy, depending on what language and tools you are using. Here are some examples of capturing these details.

### Visual Studio and .NET

If you are debugging in Visual Studio, the Exception Helper Dialog contains a link that will copy all exception details to the clipboard

![The link to copy exception details to the clipboard on the exception helper dialog](/images/stackoverflow/exceptionimage2.PNG)

If you are experiencing the Exception at runtime, you can [catch the exception](https://stackoverflow.com/questions/9526139/how-to-catch-exceptions) and call `ToString()` on it. Log the result, using whatever method is most convenient for you.

Once you have gathered all the details from the exception, you can paste it into your question in an edit. **This is important** -- Do not try to paste the exception details into a _comment_, as there is not enough room for all the details. There is an "edit" link at the bottom of your question, click it and paste the details into your question. And don't forget to format it!

## Leave a comment! {#leaveacomment}
Once you have done this, leave a comment to the person who sent you this link. They will be happy to retract their downvote.

## Did this page help you?
This website is here for everyone's benefit, most importantly yours! If this did <i>not</i> help you, or if you would
like to leave feedback, please **[create an issue regarding this page on GitHub,](https://github.com/WillSullivan/IDownvotedBecause/issues/new) or [submit an improvement directly.](https://github.com/WillSullivan/IDownvotedBecause/edit/master/{{ page.path }})**
