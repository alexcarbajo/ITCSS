# About the Server
Hi,
I've built this test in a little and old node server that I've used to give refactor workshops to different teams in the past.

To run the server:

1. Install node and grunt (npm install -g grunt-cli)
2. "npm install" in the root folder
3. "grunt" to initialize the server
4. open localhost:3000/index

In case that you can't run the server, there's a "dist version" folder with the html and CSS compiled.

This server has handlebars, a sass compiler, cssnano and autoprefixer.


# About the CSS Architecture
The CSS Architecture is a mix between ITCSS and Atomic Design. I usually use this methodology when there are Visual Designers who don't code in the projects. It's easier for them to understand Atomic Design structures than differenciating contexts and components.

I did a talk last January in a CSS Meetup in Barcelona about this architecture. You can see the slides of it in here: https://docs.google.com/presentation/d/1v9rwKXKD58DY6AdYi0v7-pQ3NyD8_3hHFTSUoxGT7us


# About the test
I didn't use for this test any framework, just applied the CSS Architecture, focusing in low specificity code, maintainability and scalability :)

+ No breadcrumb in mobile
+ Microinteractions for desktop users

I didn't go further in the templating because of the time (creating different templates, using JSONs for content, …) and also, as I told to Laura, JS is not my best skill. I understand some JS for interactions but I always try to improve the business part of my role (UX Design) or improving the Design System (modularisation, CSS Architecture) so I'm not usually doing it.
