---
layout: default
title: Four level hierarchy of the community health metrics
parent: Community health metrics
nav_order: 3
---

# Four level hierarchy of the community health metrics
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

## The top-level metrics. The health of the entire project

What does health or success mean for the project overall? 

> A healthy project is the project where users efficiently get what they came for.

Any community project should have one composite metric that incorporates efficiency of all main mechanics on the site. Company executives and department heads are the primary users of this metric. In many cases, this metric is accessible to every employee in the company so they can see how things are. The metric should be extremely simple to present and interpret.

Top level metric is unique for each project, though the idea behind is the same. Any community is a tool that solves a specific problem. The top-evel health metric should show the effectiveness of the project as a solution for the problem.

## The second-level metrics. Health metrics of the main subsystems

At this level we start measuring each subsystem separately (content, community, software). To develop the metrics at this level, we ask the same health questions as we did on the higher level, but for each subsystem independently. 

Although the set of metrics may vary from project to project, most metrics for a particular subsystem should be universal and reusable.

### Content health metrics

What does health or success mean for the content? 

> Healthy content is the content that people look for.

There are three important health metrics for the content: 

- Number of pieces of content created per period of time.
- Number of pageviews that all content received. 
- Number of pageviews per piece of content in the database.

We can think about content like a commodity which we exchange for people's attention. The metrics above show the effectiveness of creating a new “commodity,” how much attention we receive for the commodity we have, and what the average “value” of a unit of content is.

### Community health metrics

What does health or success mean for the community? 

> A healthy community is a community that has more people joining it than people leaving it.

The suggested metrics are:

- The ratio of the number of users who started participating on the site to users who stopped participating on the site.
- The number of monthly engaged users 

**Users started to users stopped**

User churn is a common phenomenon in online communities. In order for the community to continue to exist, it is necessary to compensate for leaving users with new ones.

The difficulty in creating this metric comes down to defining a churned or inactive user because it varies greatly from community to community. A good starting point would be to consider a user to be inactive if they have not performed any action during the quarter.  On the other hand, when you count the influx of new users, don't forget to count the reactivated ones.

Depending on what you care about, you can present the metric as a ratio or as a difference.

- The ratio allows one to see the proportion of new users to those who became inactive. If the ratio is greater than one, then there are more users who join and the community can be considered healthy. If the ratio is less than one, then the user churn is greater than the influx of new ones, and this situation is not good.
- The difference allows one to look at the absolute number of the user balance that sometimes is useful. 

**Monthly engaged users**

The most tricky nuance with this metric is to define an engaged user. Usually users vary from those who take one action per month to others who take thousands of actions in the same period of time. They all are engaged but to a different degree. For a community to function correctly it is critical to have all those users. To have a good representation of the health, we must measure users with different levels of engagement separately.

Here is one of the ways to split the users by the level of their engagement.

1. *Visitors*. The number of unique people who visit the site.
2. *Active users*. Users who visit the site and take any action.
3. *Casual contributors*. Users who create a piece of content or do something else that is equal to a minimal valuable contribution.
4. *Engaged contributors*. 10x contribution of a casual contributor (i.e. users who have contributed 10+ pieces of content)
5. *Core contributors*. 10x contribution of an engaged contributor (i.e users who have contributed 100+ pieces of content).

The rule of thumb of dividing users into different engagement levels is if the contribution of two users differs by an order of magnitude they should go to different groups. You can check your split by adding up the number of contributed actions of all users of the same level and then comparing the sums between the levels. The total sum of contributed actions on each level should not differ from the others by more than 10 times.

Please note that for different time ranges you may need different thresholds to split the users into engagement groups. 1-10-100 are great thresholds to group users within one month. They may not be suitable to group users within one year. To choose the right thresholds, consider how many actions you expect a user to do per day at a given level, then multiply by the number of days in the grouping period. In the case of 1-10-100 for grouping by month, the expected contribution for a user per day is 1/30, 1/3 and 3 activities per day, respectively.

Thus, we can extend the definition of a healthy community. A healthy community is a community where there are users with different levels of engagement, the total sum of contributed actions for all engagement groups is approximately equal and each group gains new members to the same extent or more than it loses them.

### Software health metrics

What does health or success mean for the software? 

> Healthy software is the software that people use.

A set of software health metrics to use depends on whether you are going to use third-party software or develop it in-house.

**Use of third party software**

In this case, you have very little control over the software and its features. Usually, there is no option (and a need) to develop your own software metrics. The only decision you might need to make is if you need to change your community platform to another one. 

**Developing software in-house**

The aspect that interests us the most in this approach is how well the platform helps users be successful on the site and get what they came for. 

Here are two suggested metrics: 

1. *Percent of coverage of tools*. For both cases it will be useful to have a list of software tools that your community needs or you envision for your community to have and track how the software you use covers the needs.
2. *Number of actions taken*. The most effective approach here is to track this number for each software tool separately.  

In addition, you can use UX metrics specifically designed for particular tools.

if you are working on your own software it might be also beneficial to track:

- *Adoption success rate*. Number of users who take any new type of action that they have not taken before.

## The third-level metrics. Measuring the impact of individual initiatives

There are three important aspects of developing good metrics for individual initiatives: identifying what you can influence, asking the right questions and understanding the deliverables.

### Identifying what you can influence: Work only on the things you are intended to change

The purpose of metrics is to help a decision-maker make better decisions. There are two situations that nullify the value of even the best metrics:

1. *There are no real plans to change anything in what you are measuring*. 
2. *It is not possible to change anything in what you are measuring*. 

It's important to focus your metrics only on what you can and are likely to change if the data shows the need for it. If you cannot change anything by any reason, then there is very little point in measuring it.

### Ask right questions

We do measurements to answer particular questions of our interest. Asking the right questions correctly is the foundation of any metric. The right questions are:

- *Actionable*. The right questions assume taking actions once the correct answer is known. 
- *Measurable*. The right questions should be quantitatively measured, as well as the actions taken based on the future answer. 
- *Based on domain knowledge*. 

### Design metrics for each initiative separately

We want to achieve long-term goals. The path to achieving long-term goals consists of achieving a number of short-term goals. The issues arise when long-term goal metrics are used to measure short-term goal initiatives. The long-term goal metrics are based on many measurements and as a result are influenced by many factors. Each short-term initiative should have its own metrics that measure the deliverables for that particular initiative. 

### Metrics for measuring сontent initiatives

Most of the content initiatives are directed to one of the following: increasing quality of the content, increasing quantity of the content, increasing awareness that the content exists on your platform. Based on the end goals we can define the following categories of metrics for individual initiatives.

**Quality metrics**

The most universal and easiest way to define the quality of the content is through the interest from the content consumers. Thus, the content has good quality if people consume it and act on it. Any metrics that represent consumers’ interest can be used. For example;

- Number of page views per visit
- Number of page views per piece of content in the database
- Average session duration

**Internal quantity metrics**

The metrics at this level represent how much content you have, how fast it gets created, or any other change in the quantity of the content on the site. For example:

- Number of pieces of content created
- Number of pieces of content deleted
- Total number of content on the site

**External quantity metrics**

Any project at an early stage requires some work directed to spreading a word that the project  exists. A typical metric for these activities is the number of backlinks to your site on other sites.

### Metrics for measuring community initiatives 

Most community initiatives are somehow related to building, growing or maintaining the community.

**Community growth metrics** 

Essential part of growing a community is acquiring new users. It means one needs to run initiatives that make people join the community and then onboard those who did. Example of metrics that help us measure that:

- Number of signups 
- Number of users who start acting for the first time

**Community building metrics**

Community building initiatives are directed to existing users. Their goal is to make the existing users become more active. Most of such initiatives happen at the special place that is dedicated for that. It might be a chat for core users, a dedicated site for meta discussions, etc. Typical measurements for community building initiatives are:

- Number of meta discussions initiated by staff
- Number of meta discussions initiated by the users
- Number of users participated per discussion 
- Number of new unique users participated for the first time per discussion 
- Number of replies per discussion (non-employee only)

Helping users and guiding them by answering their questions play a special role in community building. You might want to have a special metric for that:

- Number of employees’ replies to users’ questions.

A lot of community building initiatives are intended to connect users to each other. A connection is created when one acts towards the other person and they both are aware of the action and its author:

- Number of unique connections between users per discussion. 

**Community maintenance metrics**

This kind of metrics that quantify how community managers support users and moderators and how moderators together with community managers support the users. Also, if you have some internal people who you provide the support, you might want to measure it here as well.

- Number of tickets received and solved
- Time to resolve a ticket

**Communication metrics**

Usually community managers help product teams to talk to the community about new upcoming features, solicit feedback about new ideas, etc. To track how your communication goes you might want to track:

- Average interest. The number of actions taken by all users in an announcement threat.
- Average reach. The number of unique users who viewed the post or the number of pageviews if it is impossible to count the number of unique users.

-  Announcement checklist score. You might want to evaluate your announcement before posting it against the list of best practices of product announcements. Here are the questions:

1. Does the post contain a story? 
2. Does the post contain a theme? Is there just one theme?
3. Is the post shorter than 1.5 pages?
4. Is the post written from a positive perspective (i.e. no blame to any group of our users)?
5. Is the post written from a user-centric perspective?
6. Does the post have a clear question or call to action for the community?
7. Is the post easy to read and understand?

Sum up the number of "Yes" answers to determine whether you should post the announcement or it needs more work:

- 6–7 means you have a green light to post the announcement.
- 4–5 means that your post probably can/should be improved.
- 3 or below means that you should *not* post your announcement in its current form.

**Trust & Safety metrics**

Clear and short community rules should lead to a good understanding of them. This should result in a low number of personal conflicts in the community and rule violations. 

- Percent of active users who have been contacted by a moderator.
- Percent of active users who have been suspended.

If the platform you use allows that, I would recommend tacking rudeness as a special category:

- Percent of active users whose content has been marked as rude or offensive

### Metrics for measuring software initiatives

Software defines the tools that users use to interact with the platform, content and between each other. The software metrics are very unique for each project and they change dynamically over time based on the project’s current priorities. Though, there are two metrics that most of the product teams like to track:

- User satisfaction score
- Moderator satisfaction score

## The fourth-level metrics. The indicators

When we mark a product or community initiative as completed we need to change the list of individual initiative level metrics to represent what we are going to work on next. At the same time, we might want to keep an eye on some things and get notified if something goes wrong. This is why some metrics continue their existence as indicators. 

To understand the difference between a metric and an indicator, think of a fuel level gauge in a car, which is a metric, and a low fuel level indicator, which is an indicator. The goal of the indicators is to help us know when the reality does not meet our expectations.

If the number of metrics is limited to and ties to the number of initiatives, the number of indicators is not limited in any way. There is only one requirement for any indicator: We need to know the threshold value that tells us when “everything is good” turns into “something is bad”.

Here is a list of example indicators, but again almost any metric that you know the threshold for can be present here 

- User satisfaction score (90%)
- Moderator satisfaction score (85%)
- Number of replies per topic (3.7)
- Number of signups per visits (0.1)
- Number of pageviews per piece of content in the database (1.5)

The goal of Indicators is to allow you to track many project parameters automatically. If any parameter does not meet your expectations, an indicator should notify you about this.

## Measuring financials

### Do not be overwhelmed by looking for meaning of Return On Investment 

Almost anyone at least once looked for how to calculate return on investment (ROI) for their community. There are a lot of articles that contain thoughts explaining that is something that any project must have but none of the experts tells us how exactly to calculate ROI. The reason is that ROI can only be calculated if our community activities and associated measurements have a link to financial metrics either directly or indirectly and it is rarely the case. 

When it is impossible to calculate ROI, you can try to calculate ROnI, the Risk Of not Investing. In an applied sense, you can find all the costs that a company would incur to achieve the same results that it now gets with the community now. 

To be more convincing, make a forecast for the growth of the community, and as a result of the benefits gained from it or, in the case of not investing, the costs that company will need to pay.

### To understand the financial performance of your community, compare it with a similar “standard business”

Let’s look at community management from a slightly different angle.

Working with volunteers or hiring employees are just different approaches, but the end goal is the same - creating some value. To measure the business success of your community you can compare it with a standard business using their metrics. To do this, you need to understand the value your community creates. There are two primary types of value created by an online community.

- *User actions*. We expect users to perform certain actions that have value in themselves. For example, buying a product, signing a petition, recommending your service to friends.

- *User generated content*. By interacting on your platform, users leave a digital footprint—the content. This content usually has value in itself and generates income.

You can measure the business success of your community as the difference between the value created minus the costs of creating and maintaining a community. When calculating the value created, make adjustments for community inertia. The larger the community, the greater the inertia and the longer the community can create value with almost zero costs. To understand how viable your community is, look at the financials of a “standard business” that creates similar value. For example, if you make money from the user generated content, you can compare your financial values to the values of companies that hire content creators.