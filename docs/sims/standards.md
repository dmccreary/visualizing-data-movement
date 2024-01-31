# MicroSim Standards

One of the best ways to create reuseable simulations and animations is to make them consistent.  This
was done early on in the [p5.js editor tool](https://editor.p5js.org/).  Each
p5.js application had the following files:

1. A main HTML file called index.html
2. A CSS file called style.css
3. A JavaScript file called script.js that includes a setup and draw function template.

The main index.md file contains lines that import both the style.css and the script.js.

We have also created a set of standards that is
inspired by this structure.

1. A directory that contains the MicroSim
2. An image of the MicroSim an image of the simulation for social media posts, galleries and catalog listings.
2. An index.md file that describes the simulation in standard MarkDown format.  This also contains a link to the simulation and a link to allow you to open the simulation in the p5.js editor.
3. An HTML file that is used to run the simulation
4. The JavaScript file that runs the simulation
5. Any additional files such as JSON data files
that are used to initialize the simulation.

We have also provided a [Templates](./templates.md)