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
