# react-template-starter

**A simple folder structure template bootstrap for react projects.**

There is no way that is 100% correct to structure your application, this is purely based on my opinions as to what I feel is comfortable. Feel free to adjust it to your satisfaction or adopt it as is for your a project :)

## Getting Started

1. Ensure you've followed the ReactJS - [Getting Started Guide](https://reactjs.org/docs/getting-started.html)
2. Clone this project git clone `https://github.com/LaughingRover/react-template-starter.git`
3. Run `npm install` from root directory to install dependencies
4. Run `npm start` from root directory

## Folder Structure

* `build/` - Files that are optimized and deployed for production (Create it as needed)
* `public/` - Static files that can be accessed by the public
* `scripts/` - Miscellaneous files and scripts
* `src/` - Contains all of our react codebase
  * `api/` - Api call related function
  * `assets/` - Images, fonts and other static files
  * `components/` - [Dumb Components](https://medium.com/@thejasonfile/dumb-components-and-smart-components-e7b33a698d43), components that are given a set of props and render some data to the screen
    * `common/` - Shared components and all other reusable components, like buttons, cards, boxes
  * `config/` - Config files? Possibly sensitive
  * `containers/` - [Smart Components](https://medium.com/@thejasonfile/dumb-components-and-smart-components-e7b33a698d43), components that manipulate data, connect to services and deal with user interaction
  * `context/` - [React Context](https://reactjs.org/docs/context.html)
  * `hooks/` - All reusable [hooks](https://reactjs.org/docs/hooks-intro.html) will be placed here
  * `layout/` - Container and presentational components that represent your overall [layout structure](https://dev.to/olenadrugalya/layout-component-and-why-we-use-it-in-react-d8b) like header, main, navbar, and footer
  * `pages/` - Pages are unique parts of your application, they group the main container component and all non-reusable presentational components
  * `services/` - Javascript function to manage API integration based on the type of data
  * `utils/` - Helper functions (string utils, array utils, constants, etc). The utils folder is just a place to locate some utility functions that used repeatedly in the project. Files in the utils folder should only contain some functions like date formatting, string conversion, etc.
  * `App.js` - Application Entry point
  * `App.test.js` - Unit test for
  * `index.js` - Base react component
  * `reportWebVitals.js` - __
  * `setupTest.js` - Unit test library
  * `routes.js` - App navigation (create it as need)

Just in case you are wondering where I would put my styles, I would recommend [modular styling](https://alligator.io/react/react-css/#modular-stylesheets), but if you are more interested in cutting edge solutions then you can deep dive into [stylyed components](https://styled-components.com/docs/basics) and if you like it but already use another progressive technology like tailwind, there is no reason why you can't combine both of them, here is a solution for you [tailwind-styled-components - npm (npmjs.com)](https://www.npmjs.com/package/tailwind-styled-components). I hope this helps you as it does for me. Happy coding❤️

### Additional Resources

[Creating path aliases in create-react-app with react-app-rewired | by Suraj Pasayat | Medium](https://medium.com/@suraj.93p/creating-path-aliases-in-create-react-app-with-react-app-rewired-c2cde81b472)

---

### Source

[Guidelines to improve your React folder structure — Max Rozen](https://maxrozen.com/guidelines-improve-react-app-folder-structure) 2021, accessed 24th March 2021

[pcofilada/simple-react-starter: Simple ReactJS starter with an opinionated folder structure. (github.com)](https://github.com/pcofilada/simple-react-starter) 2021, accessed 24th March 2021

[Domain-driven design - Wikipedia](https://en.wikipedia.org/wiki/Domain-driven_design) 2021, accessed 25th March 2021
