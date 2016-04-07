# Introductory Exercise

## Objectives

The main objective of this exercise is to get a better understanding of the current knowledge of the class in a number of areas. The other objective is to give a context for some of the topics that we will discuss in the coming weeks.

## Groups

You are 38 registered students in the class. Please form **6 groups of 6-7 students**. Feel free to work in the class or outside (but let me know where you are, so that I can listen to discussions in all groups).

## Scenario

You are managing a development team within a large bank (The Bank). 

Someone from the business side has contacted you, because The Bank wants to create a new online service (The Service) for its customers. The Bank already has an online trading platform, which allows users to get live market data (quotes) and to place orders (buy and sell).

It is very popular and The Bank now wants to bring something really unique to the market. The idea is to help small investors make good investment decisions, by combining an algorithmic approach with an expert counseling (human) approach. 


## Requirements

Here are some of the first ideas that came out in a business-oriented workshop:

- Customers should be able to access The Service via a Web Browser and via a Mobile App.

- Users who have not registered can only use basic features: they can get live market information (stock quotes). The data is provided by an existing system, but is presented in the UI of The Service.

- Customers need to register to use The Service to use advanced features.

- Customers can decide to use a Free Subscription Plan or to pay for a Premium Subscription Plan. Customers who have a bank account at The Bank with a least CHF 100'000.00 get the Premium Subscription Plan for free.

- Customers can manage their profile. They can specify how "conservative" or "aggressive" they want to be, on a scale from 1 to 5 (in other words, they can specify the level of risk they want to take).

- The Service should be able to analyze activity happening on the stock market and use "smart" algorithms to predict how the price of certain stocks is likely to evolve.

- The Service should also be able to consume data from various feeds (News sites, Twitter, search engines, etc.) and to apply data mining techniques to extract information that further improve these predictions.

- The Service makes recommendations to customers once a day. A recommendation is a list of statements such as "You should buy X shares of stock Y" or "You should sell X shares of stock Y". The recommendations are computed based on the results of the previous algorithms and on the customer profile (risk level).

- When the Customer with a Free Subscription Plan receives a recommendation, he can either click on a "Follow advice" or "Ignore advice" button. If he decides to follow the advice, then The Service sends a request to The Bank's Online Trading Platform (this is an existing system) to place the order.

- If the Customer has a Premium Subscription Plan, he has an additional button: "Discuss with Expert". This opens a voice call to an investment analyst, who will discuss the opportunity and the recommendation with the customer. During the conversation, the investment analyst has access to a lot of information: the customer profile, the customer transactions history, the information produced by the predictive algorithms, informations about the specific recommendation.

- The Marketing Manager at the Bank is also very interested by The Service. The Service Should provide business analytics tools, so that the Marketing Manager knows: what types of customers are more likely to follow recommendations, whether customers have been happy with the recommendations they have received, how many customers are upgrading from the Free Subscription Plan to the Premium Subscription Plan, etc. 

- Today, the Marketing Manager does not know if it is better to charge a flat fee (e.g. 200.00 / month), a transaction-based fee (e.g. 10.00 / human recommendation) or a mixed model (e.g. 20.00/month + 5.00/human recommendation).


## Step 0: fork and clone this repo

I will ask you to prepare 3 different slide decks. Instead of sending me e-mails, I ask you to fork this repo and to add your files in the `slides` directory.

Please **push** both your source files (Keynote, PowerPoint) and a PDF export.


## Step 1: use case analysis (35')

To get a better grasp of The Service and initiate the analysis phase, you decide to make a use case analysis. In other words, you decide to make the **list of actors interacting with The Service** and a **list of tasks** they will perform.

You like to do that by combining **visual modeling** (i.e. by producing something like a UML use case diagram) and **textual descriptions** (e.g. by writing a first set of user stories).

* 10 minutes to read and analyze the business requirements
* 20 minutes to identify actors and use cases
* 5 minutes to produce a slide deck (max 6 slides, including title) with a use case diagram and a brief textual description of key use cases and questions.


## Step 2: design the high-level system architecture (35')

Based on the use case analysis, you should have a first sense of what the high-level system architecture could be for The Service.

At this stage, what you first want to identify the "**large system components**". You also want to describe the **nature of the interfaces** between these large components. Finally, you may have some ideas about **specific technologies and frameworks** that you might want to use to build the components and assemble the system.

* 10 minutes to identify the main system components
* 10 minutes to describe the interfaces between these components
* 10 minutes to identify potential technologies/frameworks to implement the components
* 5 minutes to prepare a slide deck (max 6 slides, including title) with a high-level system architecture and a description of what you consider as the main aspects to consider.


## Step 3: select a development methodology and define the high-level planning (40')

Based on the use case analysis and high-level architecture design, you should know think about how you are going to plan the project, organize the team and manage the planning of the project.

* 5 minutes to discuss what methodology you think is appropriate for delivering The Service
* 5 minutes to discuss how you are going to build a team for the project and how this team is going to interact with the rest of the organization
* 30 minutes to do an initial planning for the project. You should try to answer some of these questions: what activities need to be done? In what order? **When will The Service be available (to internal and external users)?** How will you keep track of the progress?









