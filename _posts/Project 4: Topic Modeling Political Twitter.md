## Project 4 Blog

I just finished presenting project 4 of Metis’s Data Science Bootcamp, and it’s almost hard to believe I’m only one project away from being finished with the program, and being able to officially call myself at a data scientist.

I say almost because out of the many accomplishments I am proud of, and of the many stretches I’ve had of being extremely busy, I have never worked so hard week in and week out at anything in my life. While I continue to look back and marvel at the staggering amount of new programming and packages I’ve learned during this bootcamp, I also find myself marveling at how much coffee and how little sleep have become a part of my daily routine. But the pace of the program and having to learn and do so much in such a short period of time make it seem that having a regular data scientist job will be a piece of cake.

**Project 4**

This project involved all things natural language processing, and helped me learn more new skills, concepts, and packages to add to my data science toolkit. We learned a variety of clustering algorithms such as K-Means, DBScan, Hierarchical Agglomerative Clustering, and a few others.

Before the bootcamp, the concept of converting text or image data into something that can be quantified and grouped accordingly seemed completely foreign and almost too magical to comprehend. But within just a few weeks of seeing them for the first time, these NLP tools now seem straightforward to work with, and something I can picture using on many fun and interesting future projects.  We also learned the ins and outs of using MongoDB to gather, store, and manipulate large data sets like those used for this project.

For my project, I worked with the Twitter API and used the python library Tweepy to gather the tweets of nearly 700 congress members, governors, and presidential cabinet members over a five day stretch. As someone who has volunteered for many political campaigns and always been very politically engaged, yet somehow never had an account on Twitter, the most widely-used social platform of politicians, I was very excited to do topic modeling on the tweets to and from politicians that were being most widely shared.

While I really enjoyed reading as well as laughing out loud at a lot of tweets (mostly those directed at politicians),  I cannot say that the results of my topic modeling matched what I expected or hoped to find.

In knowing that Twitter is the mostly widely used platform for discussing politics, and that the quality of political discourse on Facebook leaves much to be desired, the optimist in me hoped to find a lot of thoughtful discourse on a variety of important topics, from a variety of diverse viewpoints. However, what I found is that political Twitter is really all about the president.

The t-sne distribution chart below reiterates this, as this breaks the topics identified by the topic models down to their simplest components, and illustrates the differences between them. If the model was producing very distinct topics, it would show the different colored dots clustered in different areas of the chart.. But since all the colors are largely bunched together, this shows there is little separation among the topics my models could identify.

![T-SNE distribution](proj4tsne.png)


During a five-day stretch where a couple states passed sweeping abortion bans, $15B in aid payments were given to farmers hurt by tariffs, and the Women’s Equality Act passed in the House, the overwhelmingly dominant topics identified by my topic models involved the president, mostly relating to the Mueller Investigation.

I could not believe that these were the results of every model that I ran after the first day of the tweet collection period, until I saw that 29% of the 1.5M Tweets I had collected during this five-day stretch were re-tweets of the president’s account.

While I expected the president to be influential on Twitter, his influence is much larger than I expected. In fact, of the nearly 700 politician accounts for which I was collecting tweets, only one account had even 2% of the retweets that the president had.

That account belongs to Justin Amash, who during this tweet collection period tweeted his thoughts on the Mueller Report and became the first Republican in Congress to publicly declare support for impeaching the president. This become the overwhelmingly dominant topic over the next few days among people on the left and right, and ended up being the most dominant topic for the collection period on the whole. The word cloud below that was generated from the tweets I collected reiterates the fact that the president and comments on the Mueller Investigation and associated parties continue to dominate political Twitter, even though we are now weeks past the release of the Mueller Report.

![Tweet Word Cloud](proj_4_wordcloud.png)

This project also showed the massive extent to which political Twitter on both sides of the aisle revolves around being reactionary to the tweets of the president, and any bold statements about the president that elicit a lot of strong opinions and emotions. Before this project, the Twitter activity of the president seemed silly and pointless to me, but now I believe he accomplishes an awful lot with it, as he is able to single-handedly change or shape the political discourse with a single tweet. This was demonstrated as his tweet about possible conflict with North Korea was rapidly retweeted so many times that it became one of three topics in my final model. The Latent Semantic Analysis model that uses a count-vectorizer produced the most distinct topics of any model, which are the three topics below. Words and names are in lowercase  with spaces removed for consistent modeling.

Topic 1:		justinamash, mueller, report, barr, president

Topic 2:		iran, want, state, united, never

Topic 3:		country, congress, amp, justinamash, democrat

**Thoughts Before the Final Project**

As I prepare for the final project of the bootcamp and feel ready to graduate and return to a normal sleep schedule, in some ways, I wish I could continue. I feel grateful to be in an environment that pushes me to do and learn so much each week. I really enjoy the camaraderie of being around so many other intelligent people with diverse backgrounds and data science interests, and I wish I had time do to several different passion projects. But I only get to do one before leaving the program and becoming a working data scientist.

I still have not decided what to do with my final project, but it is not a decision I take lightly, and I am glad to be in a position where I have so many project ideas that I feel excited about. After all I have learned and accomplished over four projects, and many weeks of intense study, I feel well-equipped to do a big project that is entirely of my own design, which I will use to showcase to employers and begin the next stage of my data science journey.
