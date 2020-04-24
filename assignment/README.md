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


Final Project Proposal: Public Opinion Explorer
Shuchang Dong

As public participation is always an important part of city planning, governors and planners now are seeking innovative ways to gather suggestions from the residents and make decisions based on the feedback, There are already similar applications such as the review function in google map and yelp, however, how to comprehensively make use of the geocoded information effectively and straightforwardly is still a challenge. This project is designed to response to this challenge. It will be based on the product of my midterm project, a platform that allows users to see spatial patterns and keywords in the public opinion collected from the residents of Xiamen City. 

The data is collected from the Pinstreet, a mobile application that geo-records user opinions. I further processed the data in python, removing the user identification, and only keeping the locations and comments. The processed data is exported into geojson format and ready to use.
In my midterm project, the website has already employed technologies such as customize data filters through dropdown menu, interactive data visualization charts, changeable zoom level,  and cross-selection between charts and maps. In the final project, I will further develop this website by adding: 1) drawing function that allows users to customize a bounding box to filter the data; 2) search function that allows users to find all feedbacks that contain the input keywords, showing them on the map by adding pop out boxes; 3) change layer function that allows users flip between point map, heatmap and other demographic and economic map layers.

The target users will be the city’s decision makers and planners, who can use this platform to easily generate comprehensive reports in both geospatial and topic levels with a minimal learning curve. The layout and visual design will be inherited from my midterm, but I will try to cut down the pages and combine all the infoboxes in one page. The most difficult part might be how to graphically make the website clean and easy to read while still containing a decent amount of information. One option is to use hidden windows that will only pop out upon request. Another challenge is to get demographic information of Xiamen City since this kind of data is usually not open to the public in China. 

This website could be turned to a real application that can be used not just in Xiamen. Using Django and python script, I can hardcode the data processing process in the server, grabbing data from Pinstreet using API in realtime. In this way, the user can see the most up-to-date report.


