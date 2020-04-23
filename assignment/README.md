# Final Project Proposal

Your assignment this week is to write a detailed proposal for your final
project. In proposing your final, try to address each of the following
areas. Please produce at least a paragraph which addresses the topics below

## Problem / Question

Applications are ultimately just tools. What problem or question does
your application attempt to resolve or grapple with? How does your
application speak to this problem/question?

* The project is a map-based web dashboard to show the grocery locations in
Philadelphia. It should allow users to see the accessibility, potential service
area of each location. The app should also give a sense of which neighborhood
faces the potential under demanded problem.

## The data

Geospatial applications are all about working with data. What datasets
would you plan/like to use? If the data you'll be working with isn't
already stored in a way that you can use, how will you be storing your data?

* I acquired the grocery locations from OpenData Philly and OpenStreetMap API in
Python. I organized those data into a GeoJSON file and uploaded to my GitHub.
I plan to use jQuery to acquire them, but if it cause trouble, I may simply
store them in local folder.

## Technologies used

Which technologies covered in class (or discovered on your own!) do you
plan to use? How do you anticipate using each of these technologies?

Review the APIs/online examples of leaflet, turf, jQuery, underscore (or
any library not explicitly covered in class) for functions/uses which
you'd like to explore. Briefly describe how you might use them.

* The library such as leaflet, turf, jQuery as well as Mapbox API will be
covered in this project.

## Design spec

#### User experience

At a high level, how do you expect people to use your application?
- Who are the users?
People who want to know more about the food accessibility in their neighborhood.
- What do they gain from your application' use?
They can view the distribution of grocery location in an more organized method.
The locations will be counted in the unit of neighborhood. The travel time
isochrones allows people to see the travel buffer around each store.
- Are there any website/application examples in the wild to which you can compare your final?
https://maps.openrouteservice.org/directions
https://www.trafforddatalab.io/maps/explore/

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

* The travel time isochrones is the most difficult part. MapBox and
OpenStreetMap have the API to achieve this. If I cannot figure out how
to apply those APIs, the alternative would be distance buffer with turf.

## Missing pieces

We've only managed to scratch the surface of the available technologies
by which you could construct an application. What use-cases haven't we covered
that you think would be useful? What technologies not covered seem exciting to
you (you don't necessarily have to fully understand what they're for,
this is a chance for you to get help interpreting a technology's
purpose/usage).
