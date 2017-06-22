---
title: No exception details
byline: your question is missing exception details
permalink: noexceptiondetails/
categories: "Stack Overflow"
---
## We need all Exception details to help you!
In your question, you indicated that there was an exception thrown when your code executes. That's good information that we need to help you find a solution. However, in order to find that solution, **we need to know the details that can be found within the exception.** If your question lacks this detailed exception information, it becomes harder for us to help you.

### Why this is a problem
Exceptions contain lots of information--information we need to determine what is going on in your code. This information includes:

* The Type of the Exception
* The Exception message
* The [stack trace](https://en.wikipedia.org/wiki/Stack_trace)
* All inner Exceptions, their types, messages, and stack traces

Please note, pictures of Exceptions that shows some of the detail contained within the exception [_are also not helpful_]({% link stackoverflow/imageofanexcecption.md %}). Please, do not take an image of your Exception and paste it into an edit!

![Viewing the details of the exception](/images/stackoverflow/exceptionimage3.PNG)

### Why this is worth a downvote
Exceptions contain almost all of the information we, the people trying to help you, need in order to give you a quick answer. When you do not give us this information, we must examine your question in hopes to find clues to the information that would have been readily available had you included Exception details in your question. This is, in short, a waste of our time.

### How to fix this
Get a text report of all of the contents within it. Remember, the details of the Exception should be captured as text--[do not take an image of the Exception details!]({% link stackoverflow/imageofanexcecption.md %}) This can usually be accomplished very easy, depending on what language and tools you are using. Here are some examples of capturing these details.

#### Visual Studio and .NET

If you are debugging in Visual Studio, the Exception Helper Dialog contains a link that will copy all exception details to the clipboard

![The link to copy exception details to the clipboard on the exception helper dialog](/images/stackoverflow/exceptionimage2.PNG)

If you are experiencing the Exception at runtime, you can [catch the exception](http://stackoverflow.com/questions/9526139/how-to-catch-exceptions) and call `ToString()` on it. Log the result, using whatever method is most convenient for you.

### What to do next
Once you have gathered all the details from the exception, you can paste it into your question in an edit. **This is important**--do not try to paste the exception details into a _comment_, as there is not enough room for all the of details. There is an "edit" link at the bottom of your question, click it and paste the details into your question. And don't forget to format it!

## Leave a comment!
Once you have done this, leave a comment to the person who sent you this link. They will be happy to retract their downvote.
