---
title: Image of an exception
byline: an image of your exception isn't helpful
permalink: imageofanexception/
categories: "Stack Overflow"
redirect_from:
  - /ImageOfAnException/
  - /Imageofanexception/
  - /ImageofanException/
  - /Imageofanexception/
---
## Pictures of exceptions are not helpful {#introduction}
In my question, I indicated that there is an exception thrown when my code executes. That's good information that would-be answerers need to help me find a solution. However, in order to find that solution, they need to know the details that can be found within the exception. If my question lacks this detailed exception information, it becomes much harder for people to help me.

## Why this is a problem {#whythisisaproblem}
Pasting a picture of my exception is not helpful. I do not have to prove my code threw an Exception with a picture of it—the community trusted me when I stated this fact within my question.

![The exception dialog](/images/stackoverflow/exceptionimage1.PNG)

Pictures of Exceptions that shows some of the detail contained within the exception *are also not helpful.*

![Viewing the details of the exception](/images/stackoverflow/exceptionimage3.PNG)

## Why this is worth a downvote {#whythisisworthadownvote}
One of the first things people do when trying to help someone with an exception is *they copy text from the exception and paste it into their favorite search engine*. When I put an image of the exception into my question, I force people who are trying to help me (for free!) **to transcribe the exception from my image**. Not only is this an annoying waste of time, but also it can result in transcription errors and reduce the chance that the search is successful.

No image can contain **all of the details** from my exception. Exceptions contain [stack traces](https://en.wikipedia.org/wiki/Stack_trace) which are often very long and won't fit in an image. Exceptions also can contain *inner exceptions* which have stack traces of their own, and they can have inner exceptions as well. Answerers need all that information to answer my question. My image isn't giving them any of this necessary information!

In addition, text in images isn't indexed. This makes it very hard, if not impossible, to find my question via search engines. It reduces the visibility of my question and prevents future readers from finding it. It also prevents people who use screen readers from being able to answer my question.

## What to do next {#whattodonext}
I must capture all the details from the exception and then paste it into my question in an edit. **This is important**—I shouldn't try to paste the exception details into a comment, as there is not enough room for all of the details. There is an "edit" link at the bottom of my question. I should click it and paste the details into my question. I should make sure the text is formatted well and can be easily read.

### Capturing exception details
Capturing all details from an exception can usually be accomplished very easily, depending on what language and tools I'm using. Here is an example of capturing these details: {::comment}Note--if you add more examples, please pluralize the previous sentence!{:/}

#### Visual Studio and .NET
If I'm debugging in Visual Studio, the Exception Helper Dialog contains a link that will copy all exception details to the clipboard:

![The link to copy exception details to the clipboard on the exception helper dialog](/images/stackoverflow/exceptionimage2.PNG)

If I'm experiencing the Exception at runtime, I can [catch the exception](http://stackoverflow.com/questions/9526139/how-to-catch-exceptions) and call `ToString()` on it. I can log the result using whatever method is most convenient for me.

## Leave a comment! {#leaveacomment}
Once you have done this, leave a comment to the person who sent you this link. They will be happy to retract their downvote.

## Did this page help you?
This website is here for everyone's benefit, most importantly yours! If this did <i>not</i> help you, or if you would
like to leave feedback, please **[create an Issue regarding this page on GitHub,](https://github.com/WillSullivan/IDownvotedBecause/issues/new) or [submit an improvement directly.](https://github.com/WillSullivan/IDownvotedBecause/edit/master/{{ page.path }})**
