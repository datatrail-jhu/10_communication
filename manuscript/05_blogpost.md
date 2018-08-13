# How To Write a Blog Post

Blog posts are pieces of writing that are posted to and shared on the Internet. For data scientists, writing blog posts can help to share ideas, projects, and information with others while reading blog posts can help you learn how others analyze data, figure out what new tools are out there, and obtain new skills and tools that will be helpful to you as a data scientist. Thus, learning where to find data science blogs and how to write a good blog post is an important skill.

First and foremost, blogs do *not* have to be the same quality as a published article or academic paper. They do not have to be as polished as a published and peer-reviewed paper would have to be. Instead, blog posts can be of different levels of sophistication and varying lengths. They can be short and just provide a single, simple example. Or, they can be longer, more in-depth, and more polished. 

That said, whatever the blog post is about, it should always aim to be **clear** and to **tell a story**. This means that the blog post should always explain in the beginning *why* the reader should care and/or *what* problem is being tackled in the post before diving into the rest of the blog post. Sections of the blog post should be separated using section headers to help organize the post and guide readers along. Finally, the post should end with a conclusion.

### Types of Blog Posts

While there are many different types of blog posts out there, the four most common are:

* Announcement
* How-To
* Analysis
* Workflow

We'll describe what each of these is in this lesson and walk through an example or two of each type of post, highlighting the important parts of each post. 

#### Announcements

**Announcement** posts most importantly **provide information about a tool or resource that may be helpful to the community**. They can optionally include an example of how to use that tool or examples of why this information is important to the community. However, most importantly, their **purpose is to make the community aware of something**. 

For example, [Julia Silge](https://stackoverflow.blog/authors/juliasilge/) contributed an announcement post to the [Stack Overflow blog](https://stackoverflow.blog/) titled: [Public Data Release of Stack Overflow's 2018 Developer Survey](https://stackoverflow.blog/2018/05/30/public-data-release-of-stack-overflows-2018-developer-survey/). The main goal of this post is right there in the first sentence. The post was written to inform readers that they can now **"access the public data release for Stack Overflow's 2018 Developer Survey."** 

![Announcement Post]()

The post goes on to describe what the [Stack Overflow 2018 Developer Survey](https://insights.stackoverflow.com/survey/2018) is with **hyperlinks to information that may be helpful** to readers. Readers *could* go to that link to read all the details of this important annual survey, which asks more than 100,000 developers about the technologies they use, careers they have, and how they learn; however, that's not required.

This is because in addition to making this announcement Julia also includes what types of questions these data can be used to answer with figures and short explanations of each example right in her blog post. Each example in her blog post is separated by a bold header that asks a question. Julia then provides a figure answering that question with a short bit of text after the figure explaining what readers should take away from the figure.

![Examples using the announcement]()

Specifically, if we look at the section "Who considers themselves part of the Stack Overflow community?" in the post, we see a clear figure with "years of coding experience" on the x-axis and "% who consider themselves part of the Stack Overflow community" on the y-axis. The lines on the graph are colored by gender, with a key for which line is which gender off to the right. Below the figure is a short paragraph explaining in words how readers could interpret the information on this plot. 

This blog post is a great example of an announcment blog post as it:

* Makes the announcement
* Explains why this information is helpful
* Includes a few clear examples

The post uses clear language and examples and does not go into unnecessary detail, which is perfect for an announcement blog post. Generally, announcement blog posts are helpful for announcing new software, new datasets, and/or new resources.

#### How-To

Another very common and helpful type of blog post is a **How-To** blog post. This type of post is also often referred to as a **tutorial**. These blog posts **explain and teach how to do something** and include all the necessary information for others to do the same. 

How-To blog posts on introductory data science topics, such as data wrangling, can be incredibly helpful to those just getting started in. For example, in an earlier course when we were discussing the `dplyr` package, we referenced Suzan Baert's [four-part](https://suzan.rbind.io/2018/01/dplyr-tutorial-1/) [data](https://suzan.rbind.io/2018/02/dplyr-tutorial-2/) [wrangling](https://suzan.rbind.io/2018/02/dplyr-tutorial-3/) [series](https://suzan.rbind.io/2018/04/dplyr-tutorial-4/). These posts are an example of wonderful How-To posts. Through explanatory text and helpful examples, this set of posts teaches users new to programming or programmers new to `dplyr` how to wrangle data in R.

How-To blog posts should **introduce what it is the post will teach** and then **provide all the information needed for the reader to learn** the topic being covered. In Suzan's `dplyr` posts specifically, the title first describes what readers will learn by reading the blog post.

![`dplyr` tutorial]()

She also helpfully includes a table of contents for readers, so that skipping to the section of most interest to you is simple!

![table of contents]()

Then, for each section, Suzan includes a section title, text to describe what the section will teach, the necessary code, and the results of the code.

![each section of the post]()

By using this structure, each step is organized into a digestible amount of information. Suzan doesn't introduce all the topics at once. Instead, she incrementally walks readers through each required step. This is an important part of writing good how-to blog posts!

For another example, [Hilary Parker](https://hilaryparker.com/about-hilary-parker/) wrote a blog post called ["Writing an R package from Scratch"](https://hilaryparker.com/2014/04/29/writing-an-r-package-from-scratch/) on her blog [Not So Standard Deviations](https://hilaryparker.com/). While we haven't discussed writing R packages on your own yet in this Course set, we have worked with many different R packages! Each package has a similar structure. Hilary Parker explains how to write an R package in her [very helpful how-to blog post](https://hilaryparker.com/2014/04/29/writing-an-r-package-from-scratch/)! 

![Writing an R package from scratch]()

In this post, she includes a very clear title and begins her post with a story about *why* she's writing this post. This helps draw the reader in. Then, at the end of the introduction she informs the reader what they will get out of the tutorial.

As her blog post continues, she includes links to where readers can find more in-depth information about the topic as well as clearly defined steps so that a reader could make a package of their own.Steps are separated into sections and code is clearly separated from explanatory text.

In both of these examples, the How-To Post:

* Introduced the topic/problem being tackled
* Included text and code
* Explained all necessary steps for reader to follow along

Writing a good How-To post involves identifying a problem that others may run into and writing a helpful post about how to step-by-step solve that problem.

#### Analysis

In addition to How-To posts, data scientists often blog about interesting analyses they have done. One that we have already discussed in previous lessons is [David Robinson's](http://varianceexplained.org/about/) ["Text analysis of Trump's tweets confirms he writes only the (angrier) Android half"](http://varianceexplained.org/r/trump-tweets/). In this blog post, David Robinson walked readers through his analysis of Donald Trump's tweets.  

He includes the main point of his analysis in his title and then introduces where he got the idea to do this analysis. 

![Blog post begins with background information]()

After introducing the question, David Robinson introduces his readers to the dataset he's used for the analysis, including code for others to also carry out the analysis

![Dataset introduction]()

The post then walks readers through all the code necessary to reproduce his analysis, text to explain each step in his analysis, and figures throughout the post to display the results. For example, in the "Comparison of words" section of his post, he shows readers the code used to wrangle the data used in his figure. Then, the displays the figure with text beneath explaining what the figure shows.

Note that all the figures in this post are clear; however, they're not always as polished as what you may see in a published article. This is OK! The point is to convey the results of your analysis, not to have the prettiest figures. Thus, time should be spent ensuring that your post is clear and your analysis correct, but it's not necessary on a blog post to ensure that everything is of publication quality! Of course, you don't want to share incorrect information. So, it's best to spend time cleaning your data, ensuring that your analyses are correct, and considering the ethical implications of your work before sharing it online.

#### Workflow

Finally, helpful blog posts can also provide readers with a **description of the authors' workflow.** These types of posts are helpful to understand how others work on their computers and analyze data. They provide readers with ways to speed up their current data analysis process, introduce readers to new technology, and provide an alternate approach that may be different than your current approach. One popular workflow blog post is from [Jenny Bryan](https://www.stat.ubc.ca/~jenny/) titled ["Project-oriented workflow"](https://www.tidyverse.org/articles/2017/12/workflow-vs-script/). In this post, Jenny Bryan explains how she sets up her working environment in RStudio using a project-oriented workflow. She begins the post by explaining what prompted her to write this post. She follows up the introduction by defining some important terms (necessary background information!) that will help readers understand the rest of her post.

![Introduction]()

Then, Jenny Bryan introduces the `here` package and using RStudio Projects in your workflow. She includes section headers to organize the post and all necessary code to get started using this workflow

![workflow details]()

It's a brief but helpful post about how to approach data analysis using projects and what the potential downfalls are of opting *not* to use this type of workflow. 


### Why Blog?

Now that we've covered the four most common *types* of blog posts, why is this an effective form of communication for a data scientist and why dedicate the time to blogging? First and foremost, writing blog posts can help you clarify and organize your thoughts by writing them down in a clear and concise blog post. This can be helpful to you and others who may read your blog post and learn from it. Second, your potential audience is huge. With a blog post, you have the ability to reach anyone with access to the Internet. Helpful blog posts can help get your name out there, which is important in a field where there are lots of jobs but also lots of individuals interested in those jobs!

### Blog Etiquette

When looking at others' work, it's often easier to be critical than supportive. Being openly critical of others' work online can also *seem* easy since there's a computer screen between you and the person/people whose work you are criticizing. Thus, while being critical of others' work is OK, it is **not ok to be mean or rude when doing so**. It's ok to disagree with others online, however, the comments about others' work should always be limited to the work itself (no personal attacks!) and the tone should be as kind as possible. There's no need to make enemies, and you'll look like a jerk if you act like a jerk online. It's much better to be supportive of others in blog posts than to be rude. People will be more likely to help you when you have questions in the future and to keep up with your work if you approach blogging in a supportive manner. Keep this is in mind whenever you generate content online, be that a blog post or a comment on someone else's work.

### Summary

Now that we've walked through the main types of blog posts and why you would want to write a blog post, we'll leave you with a few of the dos and don'ts of writing blog posts:

#### Do
 
* have an informative title
* include hyperlinks and references to others' work
* separate sections with headers
* include good figures
* use clear, concise language
* proofread
* blog about things that are interesting to you!

#### Don't 

* be a jerk
* use a click-baity title
* spend all your time making sure it's absolutely perfect
* leave out important details
* disparage others' work
* be afraid to put your work out there!


### Additional Resources

For access to blog posts written by R users, check out the following two resources:

* [R-bloggers](https://www.r-bloggers.com/)
* [R Weekly](https://rweekly.org/)


### Slides and Video

![How To Write a Blogpost](UPDATE)

* [Slides](https://docs.google.com/presentation/d/1CoJJ4zEULcwzIcII6YU_ymO5mmdgD-HjVDdWEPwnm5U/edit?usp=sharing)


{quiz, id: quiz_05_blogpost}

### How To Write a Blogpost quiz

{choose-answers: 4}
? If a blog post is a tutorial, how else could you describe that type of blog post?

C) how-to
o) descriptive
o) inferential
o) announcement
o) workflow
o) analysis

{choose-answers: 4}
? What should you avoid when blogging?

C) being a jerk
C) being too-wordy
C) trying to make everything in the post absolutely perfect
o) generating good figures
o) including background information
o) including an informative title
o) using section headers
o) describing what the figures are showing
o) referencing the work of others


{/quiz}

