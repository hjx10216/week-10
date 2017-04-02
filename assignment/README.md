# Final Project Proposal

<!-- Your assignment this week is to write a detailed proposal for your final
project. In proposing your final, try to address each of the following
areas. -->

Title: "How the street network density affect the city centralization of
different traffic modes"

In mid-term project, I focused on one way to evaluate the street network density.
For the final, I wish to add some contents about using this tool to solve problems
in real world (the city centralization of different traffic modes).


## Problem / Question

<!-- Applications are ultimately just tools. What problem or question does
your application attempt to resolve or grapple with? How does your
application speak to this problem/question? -->

1. Show the city centralization of different traffic modes
2. Introduce the tools which would be used to evaluate the street network density
3. Demonstration of how the street network density affect the city centralization
   of different traffic modes


## The data

<!-- Geospatial applications are all about working with data. What datasets
would you plan/like to use? If the data you'll be working with isn't
already stored in a way that you can use, how will you be storing your data? -->

1. The traffic flows of different traffic modes of central Philly - GeoJson
2. The street network of central Philly - GeoJson
3. Centroids of streets - GeoJson
4. The streets with the value of street density - GeoJson

All GeoJson data are converted from ArcGIS shapefile files, and would be stored
in Github.


## Technologies used

<!-- Which technologies covered in class (or discovered on your own!) do you
plan to use? How do you anticipate using each of these technologies?

Review the APIs/online examples of leaflet, turf, jQuery, underscore (or
any library not explicitly covered in class) for functions/uses which
you'd like to explore. Briefly describe how you might use them. -->

1. Using the Heatmap plugin to make the heatmap of traffic flows
2. Using Carto to connect all centroid of streets, calculate the length of each segment.
3. Using Mapzen API to generate optimal route, and calculate length of each route.
4. Using Bootstrap to make good-looking web-pages.


## Design spec

#### User experience
<!-- At a high level, how do you expect people to use your application?
- Who are the users?
- What do they gain from your application' use?
- Are there any website/application examples in the wild to which you can compare your final? -->

Hope people can get better understanding of how the tool works and how the tool
can be used, by playing the application.

#### Layouts and visual design
<!-- So far, we've built all our applications with a side bar for
representing non-map content and navigation. This is not the only
successful design. Extra content could be displayed in a top bar,
through modals, through side bars on both sides, and any combination of
these as well as a number not mentioned. Try to describe your
application's visual layout. Conceptually (no need for extensive CSS
here), what will this design require? -->

Need more time working on it, haven't made the final decision.


## Anticipated difficulties

<!-- Thinking about weaknesses can be useful. What do you anticipate being
most difficult about this project? How will you attempt to cope with
these difficulties? For example, asynchronous behavior (ajax, events)
are hard to use and think about. Global variables are a strategy for
coping with that difficulty by breaking data out of the asynchronous
context. -->

- Time is limited, I don't know whether I have enough time to make the application
as good as I wished...
- Maybe some NVD3 problems


## Missing pieces

<!-- We've only managed to scratch the surface of the available technologies
by which you could construct an application. What use-cases haven't we covered
that you think would be useful? What technologies not covered seem exciting to
you (you don't necessarily have to fully understand what they're for,
this is a chance for you to get our help interpreting a technology's
purpose/usage). -->
