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
Questions often include the fact that the code in question generates errors when compiled or throws exceptions when executed. That's good information that we need to help find a solution, and is important to include within the question. However, in order to find a solution, we need to know the details that can be found within the error or exception. If the question lacks this detailed information, it becomes harder for us to help solve the problem.

## Why this is a problem {#whythisisaproblem}
Pasting a picture of an error or an exception is not helpful. No one needs to prove the code resulted in an error with a picture of the error--we trust people when they tell us this within the question. But these images are not helpful for a number of reasons. For example,

![The exception dialog](/images/stackoverflow/exceptionimage1.PNG)

pictures of exceptions show only part of the detail contained within the exception are not helpful, as they lack the full details needed to diagnose the issue. Trying to include these by taking images of the exception details is also not helpful, as the full detail cannot be easily captured.

![Viewing the details of the exception](/images/stackoverflow/exceptionimage3.PNG)

## Why this is worth a downvote {#whythisisworthadownvote}
One of the first things people do when trying to help someone with an exception is *they copy text from the exception and paste it into their favorite search engine*. When someone puts an image of an exception into their question, they force people who (for free) are trying to help **to transcribe the exception from your image**. Not only is this a waste of their time, but also it can result in transcription errors and reduce the chance that the search is successful.

Images cannot easily contain **all** of the details from an exception. Exceptions contain [stack traces](https://en.wikipedia.org/wiki/Stack_trace) which are often very long and won't fit in an image. Exceptions also can contain *inner exceptions* which have stack traces of their own, and they can have inner exceptions as well. Helpers need all that information to answer a question. An image isn't giving them all of this necessary information in an easy to consume form.

In addition, text in images isn't indexed. This makes it very hard, if not impossible, to find similar questions via search engines. It reduces the visibility of these questions and prevents future readers from finding it. It also prevents people who use screen readers from being able to answer these questions.

## What to do next {#whattodonext}
Capture all the details from the exception as text and then paste it into the question in an edit. **This is important**--users should not try to paste the exception details into a comment, as there is not enough room for all the of details, nor can comments be formatted neatly. There is an "edit" link at the bottom of all questions. Users can click that link and paste the details into their question. It is alwasys important to make sure the text is formatted well and can be easily read.

### Capturing exception details
Capturing all details from an exception can usually be accomplished very easy, depending on what language and tools being used. Here is an example of capturing these details. {::comment}Note--if you add more examples, please pluralize the previous sentence!{:/}

#### Visual Studio and .NET
When debugging in Visual Studio, the Exception Helper Dialog contains a link that will copy all exception details to the clipboard 

![The link to copy exception details to the clipboard on the exception helper dialog](/images/stackoverflow/exceptionimage2.PNG)

If the Exception is being thrown at runtime, [catch the exception](https://stackoverflow.com/questions/9526139/how-to-catch-exceptions) and call `ToString()` on it. Log the result, using whatever method is most convenient.

## Leave a comment! {#leaveacomment}
Once you have done this, leave a comment to the person who sent you this link. They will be happy to retract their downvote.

## Did this page help you?
This website is here for everyone's benefit, most importantly yours! If this did <i>not</i> help you, or if you would
like to leave feedback, please **[create an Issue regarding this page on GitHub,](https://github.com/WillSullivan/IDownvotedBecause/issues/new) or [submit an improvement directly.](https://github.com/WillSullivan/IDownvotedBecause/edit/master/{{ page.path }})**
