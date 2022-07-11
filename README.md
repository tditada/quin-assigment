# Moonshot Calendar Inc.

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## How to start:

- Run `yarn` or `npm install` to install dependencies
- Run `yarn start` or `npm start` to start the app in development mode. It will automatically open.
```
http://localhost:3000
```

## How to build the app:

Run `yarn build` or `npm run build`. It bundles React in production mode and optimizes the build for the best performance. The build is minified and the filenames include the hashes.

### About the app
The main constrain was time (3 hours). My main goal was getting an MVP with clean code, some tests and clear documentation that works. So I choose to use technologies I'm comfortable with and that are less time consuming.

### How I started with the assignment
1) I first read the assignment completely to check if I understand it and if I have questions (best to ask them at this stage). 
2) As I'm working with an API, I tested it to see if it does what I expect and what endpoints and filters are available. 
3) I choose what my goal will be and I decided that I want to first have a list of all the launches with error and loading. Then I could add at least one filter to the list. I reasearch a few minutes about react-simple-maps and google-map-react but as it's my first time using maps I don't want to lose time with that.
4) Before coding, I also think a little about the components I'm building and what I want them to do. I put a HTML base with header, footer, main etc

### Folders
I have `src`, and at src root there's the main App and index. But then, the components I created are in `src/components`. If the project was bigger, the components could even get their own folder and type and style files for each own, also to better separate wich component should have access to what.

### Decisions about setup, library and techniques
1) This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app) with `React` and `Typescript`. I choose it because it's a well known library with good documentation I feel confortable with.  There are other newer options like `Vite` that could have also work.
2) `Styled components` as the  styling framework
3) `Jest` and `React testing library` for testing.
4) `NaterialUI`. I needed something quick for error and loading managment, and also select. Its a good UI library with clear documentation.
5) `Hooks` for state management as it's a small app and it can be managed just with hooks. Other option if it was a bit bigger and complex would have been redux (that also has thunks and sagas).

### What I would have change if I have more time, why and how.
1) Testing: I started with testing and documentation a bit late for my taste.
