# SeekandHit FE Position Demo Project

Base project for job candidates applying for frontend developer position at [Seekandhit](https://seekandhit.com/).

## Project goal

This project is an opportunity to demonstrate both your development skills and your determination to get a job done right. The task is to build a generic `Autocomplete` component. You should design its API based on these requirements:

- component has a default style, but it can be extended through props
- haystack items can be an array of strings or objects
- in case of objects, client must provide a getter function to take the wanted property from the object
- it can be used **uncontrolled**: client provides a list of items, mapper object in case the list consists of objects and a callback when a value is selected from the list
- it can be used **controlled**: client also provides a custom search function which will be called in place of default search function

A complete solution would include both the implementation of the component and a few examples demonstrating the controlled and uncontrolled use cases. Feel free to style the component as you see fit.

Third party packages can be used, as long as they don't help with rendering. Meaning it is OK to use a package for [fuzzy filtering](https://www.npmjs.com/package/fuse.js), but it is not OK to use complete or half-complete dropdown components like [downshift](https://www.npmjs.com/package/downshift).

## Criteria

When reviewing your solution, we will pay attention to these kind of details:
- correctnes of component behavior
- potential performance issues
- code readability
- component API design & documentation
- test coverage

## Development

Fork this repo and install the dependencies using `npm i`. This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app), so all the available documentation applies to this project too. Base scripts are:
- `npm start` - start the dev server
- `npm build` - build the production version of the app
- `test` - run the tests in interactive mode