## Project 3 Blog

Project 3 of the Metis data science bootcamp is now complete, and we are now at the halfway point of the bootcamp. While my body is acting increasingly desperate for an afternoon nap and some extra coffee each day, it feels great to continue learning so many new data science tools and skills.

In just over two weeks since our previous project, we have learned a variety of classification models including K-Nearest Neighbors, Logistic Regression, Support Vector Machines, Naive Bayes, Decision Trees, and Random Forests. In addition, we incorporated all of these models into our recently completed project, so it’s nice to have experience working with these models on our own chosen data sets.

Although that seems like a lot to cover in a couple weeks, during that time we also learned how to upload, store, and interact with our datasets using Amazon Web Services. We now know how to create interactive visualizations using tools such as Tableau, Plotly, and Bokeh. And we also have gotten experience creating web apps via Flask. Below is a video of the visualization I created for my project, where I created an interactive grouped bar chart to demonstrate some of the differences in features between my project's customer and non-customer groups.

![Customer and Non-Customer Features](Project_3_Viz.mov)

Simply recounting that list of new skills makes me feel even more tired than I already am, but I still feel excited to keep moving forward

**Project 3**

For Project 3, I used the classification models listed above to predict whether or not members of a Chicago company’s sales pipeline would become customers. It was really exciting to be working with real-life data from an actual company, and trying to help them improve upon some critical aspects of their business.

The downside of working with this data instead of a dataset that is publicly available online, is that I got my first taste of what it’s like to work with a very sparse and messy dataset that we might expect to encounter in a job setting. Working with this data required the most data cleaning of any dataset I have encountered so far, but it was great to put my Pandas and SQL skills to the test to make this data ready to model.

Once my data was ready to model, it was really interesting to see how the different models performed on my data, and how I could improve the performance of the models by tuning their hyperparameters, and then adjusting the probability thresholds of different models to achieve more desirable results.

For my model, I wanted to maximize the number of customers that it  correctly predicted, without having it skew too heavily toward predicting that everyone would be a customer.  It was cool to tinker with the model to achieve the optimal combination.

After running all of the different model types, I chose logistic regression as my final model. By lowering it’s probability threshold to predict that anyone with at least a 45% chance of being a customer would be a customer, it was able to identify 80% of the the company’s actual customers that the model was tested on, while being over 70% accurate when it predicted that someone would not be a customer. The predictions of the final model are in the image below.

![Final Model Predictions](project_3_cm.png)



**Halftime Thoughts**

As I arrive at the halfway point of the bootcamp, I once again find myself looking back at all that I have learned and accomplished in recent weeks, and feel great about all the progress I have made. I truly feel like I have not learned so much in six weeks at any point in my life.

While the program only gets more challenging as time goes on, and the gap between what I know and what I feel like I should know seems to grow each day, I continue to learn so much, and feel more and more like a legitimate data scientist.

This makes all the hard work and lack of sleep seem well worth it. Even though I feel like I could sleep for a day straight, I am excited to begin my next project tomorrow, and dive into the complex and fascinating area of natural language processing.
