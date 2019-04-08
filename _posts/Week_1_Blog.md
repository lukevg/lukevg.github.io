## Week 1 Blog

Today was the end of my first week at Metis’s 12-week data science bootcamp, and my cohort already has our first completed data science projects under our belt. It was a fast-paced week filled with learning lots of programming tips and data science tools,  but it feels like I am well on my way to becoming a professional data scientist.

One thing I enjoy about this program is that we get a good feel for many of the daily activities of a data scientist on our very first day, and each day after. By the end of the first day, we already completed our first group programming problems, had a lesson where we learned and practiced how to clean and organize data with Pandas, and began working on our first data science project.

**Project 1**

Our first project involves using New York City’s MTA data to decide which subway stations to place street teams in order to generate interest and donations for a gala to support women in tech. At first, it seems overwhelming that the sentence above represents the entire instructions. However, I now appreciate and see a lot of value in laying out the first project in this way.

My group wanted to focus on targeting tech employees for the women in tech gala. We did that by finding maps of the concentrations of tech companies in each [Brooklyn](https://inhabitat.com/nyc/brooklyn-tech-triangle-plan-could-re-create-silicon-valley-in-nyc/) and [Manhattan](https://www.builtinnyc.com/2016/12/13/big-tech-companies-nyc-locations)
, and mapping out the latitude and longitude within those areas. We used those coordinates ranges to compare to the MTA’s data on station entrance coordinates, and filtered out stations that were outside of the two tech hubs.

From there, we identified stations that have much higher ridership on weekdays than weekends, with the goal of going to stations that have relatively more work commuters than tourists. Ultimately, we created a score for each station in the city based on its proximity to the tech hubs, its difference between weekday and weekend ridership, and its overall ridership volume. We recommended stations by their scores, and [these](https://github.com/lukevg/MTA-Project/blob/master/top20_rtd.png) stations were our highest scorers.

Seeing all the groups present their results reminded me that the same project can often be done in countless ways.  After all, data science requires a lot of creativity, problem-solving, and judgment calls when there is no right or wrong answer. So the open-ended nature of the project made it feel like something that might be done in a workplace.

It was really interesting to see how other groups structured their projects differently, and that some groups got similar results and conclusions to mine even though their process was very different.

**Takeaways from Week 1**

During the week we also got much more comfortable with data visualization tools like MatPlotLib and Seaborn. We got several tutorials on Github, which seems complex enough to justify several more.  We also got lots of helpful tips for how to design a project, structure our code to make it more readable, and communicate findings and results to a less nerdy audience. All of this makes me confident that we will learn a truly massive amount before the bootcamp is over.

I like that we have established a routine for each day, yet we learn and practice new things every day. Each day, we start with a new programming challenge where we work with different people solving different types of problems. After that, we have a lecture on a new topic where we can follow along and practice on helpful examples. And these lectures are supplemented with additional resources we can use to learn even more on our own. We then get the afternoon to work on our projects.

I like that as soon as the instructors cover something new, we practice it and start incorporating it into our next project right away. This helps build confidence and immediately starts removing doubts that something is too difficult or overwhelming.

After seeing all the we learned and accomplished in just five days, I am eager to keep learning,  and see what all of us can do with our upcoming projects.
