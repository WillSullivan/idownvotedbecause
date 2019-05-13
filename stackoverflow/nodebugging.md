---
title: No debugging
byline: there was no effort to debug the code
permalink: nodebugging/
categories: "Stack Overflow"
redirect_from:
  - NoDebugging
  - Nodebugging  
---
## There appears to have been no effort to debug the code {#introduction}
Debugging code is one of the most important things that a developer can do. When a program's result is unexpected, or when a program crashes at runtime, debugging is a way for a developer to quickly isolate and identify the problem. In the vast majority of cases, once the problem is identified, the solution is clear. But when a developer does not debug their code, the problem becomes much harder to fix.

## Why this is a problem {#whythisisaproblem}
Without making the effort to debug failing code, the less obvious the problem is, the harder it will be to find a solution. Sometimes you are lucky and the problem may be evident in the code itself. But that is not always the case. A fix that might take ten minutes to find through debugging may drag out for hours and consume the effort of multiple people. 

## Why this is worth a downvote {#whythisisworthadownvote}
Without debugging, you risk wasting the time of those who are trying to help you. If the problem is easy to fix, and would have become self evident when debugging, there was no need to ask the question in the first place. Time you spent composing the question could have been spent fixing your problem. Time others spent reading your question could have been spent helping others with harder to diagnose problems. And when your problem *is* hard, without isolating the issue through debugging, it requires others to **guess** at the possible causes. There will be much more back-and-forth over possible causes and solutions, taking much more time than was necessary to fix your problem. Debugging helps prevent all of this.

## What to do next {#whattodonext}
Debug your code! Execute your code with your favorite IDE's debugger attached, or use your browser's developer tools for client-side JavaScript. Place breakpoints near where your code fails. Examine variables and their contents at runtime. Watch your logic evaluate these variables and examine the results for correctness. You may find what you believed to be the result was not, allowing you to fix your algorithm. Or you may not understand why the algorithm was failing. Record all of this information--the algorithm, your variable's values, and what the unexpected result was. You will need it to compose a good question!

Once you have debugged your code, take everything that you have learned and edit your question. Note: don't add this information as one or more comments on your question! Add all your findings in a clear and well-formatted edit. Add missing code, if any, that is relevant to the question.

If you found the solution to your problem when debugging, and that solution may be useful to others, you can add an answer to your question with details about what you did and what you found while debugging.  If other people answered your question, and they were somewhat or exactly right, select the best one as correct. If your answer is the only one, after the required waiting period, you can select your answer as correct and close out the question. It may seem odd, but that's how we handle this situation.  If your answer is of no use to anyone else, and no one has answered your question, you can simply delete it.

### How to debug {#howtodebug}
Often times new developers do not know how to debug their code. Following are a number of different articles detailing how to debug code using different tools.

#### What is debugging? {#whatisdebugging}
If you aren't sure what this whole "debugging" thing is, [here's an introductory article on Wikipedia](https://en.wikipedia.org/wiki/Debugging).

#### What exactly do I do? {#whattodo}
If you're not sure how to start debugging your application, Eric Lippert's article ["How to debug small programs"](https://ericlippert.com/2014/03/05/how-to-debug-small-programs/) is a good starting point.

#### Visual Studio and Visual Studio Code {#visualstudio}
To learn how to use debugging tools in the latest version of Visual Studio, [click this link](https://docs.microsoft.com/en-us/visualstudio/debugger/debugger-feature-tour). For Visual Studio Code, [look here](https://code.visualstudio.com/docs/editor/debugging).

#### JavaScript (in browser) {#javascriptinbrowser}
You can debug your JavaScript directly in most common browsers, including [Chrome](https://developer.chrome.com/extensions/tut_debugging), [Firefox](https://developer.mozilla.org/en-US/docs/Tools/Debugger), [Edge](https://docs.microsoft.com/en-us/microsoft-edge/f12-devtools-guide/debugger), and [Safari](https://developer.apple.com/safari/tools/).

#### Xcode {#xcode}
You can learn how to debug in the Xcode IDE [at this link](https://developer.apple.com/library/content/documentation/DeveloperTools/Conceptual/debugging_with_xcode/chapters/debugging_tools.html).

#### Android Studio {#androidstudio}
To learn how to debug your Android app in Android Studio, [visit this link](https://developer.android.com/studio/debug/index.html).

#### C and C++ using the Gnu Debugger (GDB)
For a tutorial using the [Gnu Debugger](http://www.gnu.org/software/gdb/) to debug your C or C++ application, [visit this link](http://www.thegeekstuff.com/2010/03/debug-c-program-using-gdb/).

#### MATLAB {#matlab}
To learn how to debug your MATLAB program in the MATLAB editor, [visit this link](https://www.mathworks.com/help/matlab/matlab_prog/debugging-process-and-features.html).

#### Your favorite IDE
Have a favorite IDE/Language combo you want to add to this list? [Submit your addition here!](https://github.com/WillSullivan/IDownvotedBecause/edit/master/{{ page.path }})

## Leave a comment! {#leaveacomment}
Once you have done this, leave a comment to the person who sent you this link. They will be happy to retract their downvote.

## Did this page help you?
This website is here for everyone's benefit, most importantly yours! If this did <i>not</i> help you, or if you would
like to leave feedback, please **[create an issue regarding this page on GitHub,](https://github.com/WillSullivan/IDownvotedBecause/issues/new) or [submit an improvement directly.](https://github.com/WillSullivan/IDownvotedBecause/edit/master/{{ page.path }})**
