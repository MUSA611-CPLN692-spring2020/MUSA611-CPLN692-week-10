# Final Project Proposal

Your assignment this week is to write a detailed proposal for your final
project. In proposing your final, try to address each of the following
areas. Please produce at least a paragraph which addresses the topics below

## Problem / Question

Applications are ultimately just tools. What problem or question does
your application attempt to resolve or grapple with? How does your
application speak to this problem/question?

The application will provide information about all green space in Philadelphia.
Users will use this website to check the location of each park, the address, basic
facilities, how to get to this place based on the location of themselves.

## The data

Geospatial applications are all about working with data. What datasets
would you plan/like to use? If the data you'll be working with isn't
already stored in a way that you can use, how will you be storing your data?

The application will use open space/green space data from OpenData Philly. The data
now is geojson format.

## Technologies used

Which technologies covered in class (or discovered on your own!) do you
plan to use? How do you anticipate using each of these technologies?

Review the APIs/online examples of leaflet, turf, jQuery, underscore (or
any library not explicitly covered in class) for functions/uses which
you'd like to explore. Briefly describe how you might use them.

It will have all the functions l learned before midterm, including click, slides.
It will also contain allow website to locate users and calculate the route to
specific locations. Click function will highlight the information. Also, some of
the css style will be included, such as dropdown menu, link and welcome page. Generally,
the website will have multiple slides.

## Design spec

#### User experience

At a high level, how do you expect people to use your application?
- Who are the users?
- What do they gain from your application' use?
- Are there any website/application examples in the wild to which you can compare your final?

people who are interested in green space in Philadelphia.
check out all the current locations of green spaces, the route to get there, recommended/most popular
parks in philly and some basic information about this park.
For example, https://bikemaps.org/

#### Layouts and visual design

So far, we've built all our applications with a side bar for
representing non-map content and navigation. This is not the only
successful design. Extra content could be displayed in a top bar,
through modals, through side bars on both sides, and any combination of
these as well as a number not mentioned. Try to describe your
application's visual layout. Conceptually (no need for extensive CSS
here), what will this design require?

first welcome page, then click into main slide. The slide will have side bar, top bar with dropdown
function, bottom bar with some contact, FAQ or help. Majority of information will be showed on
the slide bar through clicking each parcel. Also, by click, users can see a new slide
showing top 10 popular parks in Philly.

## Anticipated difficulties

Thinking about weaknesses can be useful. What do you anticipate being
most difficult about this project? How will you attempt to cope with
these difficulties? For example, asynchronous behavior (ajax, events)
are hard to use and think about. Global variables are a strategy for
coping with that difficulty by breaking data out of the asynchronous
context.

might be creating multiple website slides.

## Missing pieces

We've only managed to scratch the surface of the available technologies
by which you could construct an application. What use-cases haven't we covered
that you think would be useful? What technologies not covered seem exciting to
you (you don't necessarily have to fully understand what they're for,
this is a chance for you to get help interpreting a technology's
purpose/usage).

how to show the transportation method/route specific information instead of showing
just a line, something like google map?
