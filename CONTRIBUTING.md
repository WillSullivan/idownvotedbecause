## How to help

To help with the project, start by copying the contents of the [post template](https://github.com/WillSullivan/idownvotedbecause/blob/master/posttemplate.txt) into a new markdown file.

The name of the markdown file should be a very short topic description, and placed in a subfolder based on the community.

## Using the template

The template should be clear (or clear once you submit a pull request to improve it!) on the front matter components, what they are for, and how they should be configured.

It should also be clear on the sections that should be included, their order, and what they should contain.  Text that should be changed is **[written in brackets]**. Comments on what a section should contain **{::comment}are surrounded by Kramdown comment markup{:/}**, which will not be rendered in the final website. 

Be careful with the yaml front matter. Text can generally be entered without quotes, but if your text contains [yaml special characters](http://yaml.org/spec/1.0/#id2559506) (sorry, that link sucks) you need to surround your text in 'single quotes'.  If your text contains single quotes and the front matter displays atypically in the preview (as code rather than as a table), surround the entire line in single quotes and escape the single quote in your text by doubling it.  E.g., *you don't say* becomes  *'you don''t say'*

## Subjects

Acceptable subjects are problems that attract downvotes *that can be reversed*.  If a post is not salvageable (i.e., nothing can be done to reverse the downvote), then the subject probably shouldn't be broached here.  Problems that can only be solved by deleting the post, thereby gaining back lost reputation points, should be kept to an **absolute minimum**.  It is hard to keep a positive and helpful tone when the only thing you can tell someone to do is "delete your post".  These should only be created for extraordinary circumstances.

## Tone

Be conscious of the tone of your topic. Talk about the problem as if it was its own entity, not the result of what any specific person did. If you aren't sure what this means, check the history of this document for an example. 

Be careful of sounding accusatory towards an individual person, rather speak of any person in a similar situation. And try not to use the passive voice _too_ much. Pages must state facts as they exist.

Pages must **not** make asumptions that could shed a dire light on the subject. For example, this is _not acceptable_:

> Homework questions show laziness and often attract downvotes.

This is making the asumption that the user is lazy. Not only does it not help, it can also make readers feel insulted or targeted. Instead:

> Homework questions are often frowned upon by users as they are generally low quality and show little work.

_Again,_ try to avoid targeting users in any way. They are likely to be upset already and feel that they are being personally down-voted. Re-enforcing this felling will not help the website contribute to their learning.

## Images

Images should be stored under /images in a subfolder by community (the same as the one you are posting about). Try to keep images as small as possible, focusing on what is important. We don't want to see your browser tabs. Also, images without freehand circles will be rejected. More freehand circles, pls.

## Kramdown
The site uses Kramdown for markdown processing. It's got some special features over and above standard markdown. [Here's a quick reference guide to its syntax.](https://kramdown.gettalong.org/quickref.html#html-elements-1)
