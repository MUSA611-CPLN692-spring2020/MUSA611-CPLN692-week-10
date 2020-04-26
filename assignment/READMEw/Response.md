# Final Project Proposal

Your assignment this week is to write a detailed proposal for your final
project. In proposing your final, try to address each of the following
areas. Please produce at least a paragraph which addresses the topics below

## Problem / Question

Applications are ultimately just tools. What problem or question does
your application attempt to resolve or grapple with? How does your
application speak to this problem/question?

## The data

Geospatial applications are all about working with data. What datasets
would you plan/like to use? If the data you'll be working with isn't
already stored in a way that you can use, how will you be storing your data?

## Technologies used

Which technologies covered in class (or discovered on your own!) do you
plan to use? How do you anticipate using each of these technologies?

Review the APIs/online examples of leaflet, turf, jQuery, underscore (or
any library not explicitly covered in class) for functions/uses which
you'd like to explore. Briefly describe how you might use them.

## Design spec

#### User experience

At a high level, how do you expect people to use your application?
- Who are the users?
- What do they gain from your application' use?
- Are there any website/application examples in the wild to which you can compare your final?

#### Layouts and visual design

So far, we've built all our applications with a side bar for
representing non-map content and navigation. This is not the only
successful design. Extra content could be displayed in a top bar,
through modals, through side bars on both sides, and any combination of
these as well as a number not mentioned. Try to describe your
application's visual layout. Conceptually (no need for extensive CSS
here), what will this design require?

## Anticipated difficulties

Thinking about weaknesses can be useful. What do you anticipate being
most difficult about this project? How will you attempt to cope with
these difficulties? For example, asynchronous behavior (ajax, events)
are hard to use and think about. Global variables are a strategy for
coping with that difficulty by breaking data out of the asynchronous
context.

## Missing pieces

We've only managed to scratch the surface of the available technologies
by which you could construct an application. What use-cases haven't we covered
that you think would be useful? What technologies not covered seem exciting to
you (you don't necessarily have to fully understand what they're for,
this is a chance for you to get help interpreting a technology's
purpose/usage).






# Final Project
Akshay Nagar& Miaoyan Zhang


## Introduction

Our final project is to prepare a dashboard to be used by City of Baltimore Vehicle & Fleet Management Department, it helps them see which vehicle is likely to be broken quickly and hence could have a comeback, and which vehicle has a low risk of Comeback , This tool will thus help the city take more efficient and cost effective decisions. This tool could help save a lot of valuable tax payer’s money and at the same time make sure the fleets are available when needed.

## The Business Problem & Client &  Problem The Application Repsosne

Our Client is the Vehicle Repair Department of Baltimore City government fleet management system, they are having an unusual problem, they are spending too much on vehicles and too many are coming back too often, or at least this is what they perceive, they want us to analyse their data set and give a mathematical definition of ‘what exactly is a comeback’. We start by exploring two vehicle spending and developing some tools to keep visiting thorough our analysis, and ultimately defining a comeback, and then finally predicting it to help the city better manage their fleet and reduce their spending.

The problem even after the machine learning model would be how to convey this information efficiently , effectively and properly to city officials and mechanics. This is where our JavaScript Dashboard. Application will help,

## JavaScript Dashboard Application  (Main Portion of the App):

The main constituent of our JavaScript App would be a dashboard, our application in JavaScript will make this data available in a streamlined way to the Mechanics and Coty officials so that they can see the above prediction model results and vehicle history all in charts format, as well as with interactivity and will do it effectively to save time and effort and make the repair decision making process faster, efficient and stream lined.

## Map for JavaScript Application (Minor use in the App):

While most of the application’s major purpose would be the dashboard. There would also be a key map on location of cctv data, this will help to deploy vehicles after they are repaired, and the officers can refer to nearest cctv locations to both get vehicles to workshop and to deploy them back.








## Data Sets :

1)	The most important dataset which we are working with for our practicum has been provided by the city . This data would be made available to the app, and this is what the Dashboard would work on.

2)	The Second Data would be for mapping and have location data of cctvs, which can help deploy and call vehicles to and fro workshops : These are open Data Sources for which the link are below:

https://data.baltimorecity.gov/Public-Safety/CCTVMAP/nn6t-vxz4

https://data.baltimorecity.gov/Public-Safety/Fells-Point-Downtown-CCTV/7awx-knb7


## Technologies used

We Would be using leaflet, turf, jquery, canvasjs, and chartsjs.org and maybe even mapbox, we will decide between mapbox and leaflet after testing both for results.


## Design specifications : User experience


Our App is being developed for the public sector, it will be used by city officials and mechanics, we want to thus make it as easy and efficient to use, as possible. This will save them time in an engaging way, instead of
Briefly it will be like financial dash  board, or a technical dashboard or a healthcare dashboard. Some websites where users can see their internet status speed, in a detailed way such as network info download vs upload as well technical aspects as well as similarly, websites where financial stock data or healthcare data as in these times is being shown as engaging charts come similar to what we are trying to create, in however a different context, as our app is for select users, despite that we want to make it engaging and easy to use, as even though our userbase is select, they are public level officials, and their work impacts everyone’s quality of life and health and safety in Baltimore City, hence we view our app as a very important tool and it’s user experience vital.

## Design specifications  Layouts and visual design

Our Application will be closer to a financial data board, and other similar dashboards discussed above, we will hover also have a mapping data, even though the website will mainly be a dashboard, we may make the user scroll down for map, however main screen will have links using html so that the initial page, shows all links, and the user does not need to scroll down to see everything, and can easily select links on the page to go to different sections.

## Anticipated difficulties

We have started work on our app, Charts in general are a thing we covered later in class, and only virtually so while we have got them working, we know we could be facing some challenges, and currently we our finding it very difficult to plot charts with database data, the task is much simpler with dummy data, plus we will be publishing this app on UPenn’s Website, and he we will be posting the dataset online, to refer to it, so our prior task of linking to the database might get even tricky as ajax can be unrealisable and hard to debug at times.
We however see these difficulties as doable, and anticipate to make them a learning experience of us and not a hindrance.

## Missing Pieces

In terms of Charting we would like to learn more about efficient ways to link to database and have multiple selection features, and perhaps more about what chart libraries are best for simple or interactive or filters or combination of these ideas. However we are able to get the desired results right now, but it would be good to learn about more libraries to do this more efficiently.
We would like to include information about gprs tracking, where the app could also show where vehicles are moving live, and hence workshops can prepare for their arrival and help navigate them to other workshops when they are busy. These are some ideas about which we would want to learn later in our careers.
