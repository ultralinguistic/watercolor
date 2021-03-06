## Water Color

### Background

Water Color is a canvas that user can click on and shows the water color dying effect from the clicked spot.
It uses breadth-first algorithm to pick the next pixel.

### Functionality & MVP  

With this Water Color simulator, users will be able to:

- [ ] Pick a color
- [ ] Click on the canvas
- [ ] See the effect
- [ ] Clear, pause, resume effect

In addition, this project will include:

- [ ] A production Readme

### Wireframes

This app will consist of a single screen with a canvas, a color picker, and short explanation how to use the app.

[wireframes]: ./wireframes

### Architecture and Technologies

This project will be implemented with the following technologies:

- Vanilla JavaScript for overall structure and game logic,
- `HTML5 Canvas` for DOM manipulation and rendering,
- Webpack to bundle and serve up the various scripts.

In addition to the webpack entry file, there will be three scripts involved in this project:

`watercolor.js`: this script will handle the logic for creating new path generator and rendering it to the DOM.

`path_generator.js`: this script will handle the logic for creating canvas, passing information to the breadth first object, and event handling.

`breadth_first.js`: this script will handle the logic for generating the cells and fill the color on them.

`jscolor.js`: this script is the js-color picker from http://jscolor.com.



### Implementation Timeline

**Day 1**: Get the canvas showing and handle click.

**Day 2**: Set the basic algorithm and get it working with one color.

**Day 3**: Set up color picker.

**Day 4**: Polish.

### Bonus features

- [ ] Multiple click handling.
- [ ] Example picture starting when user enters.
- [ ] Speed handling.
- [ ] Size handling.
- [ ] Add options for different algorithm.
