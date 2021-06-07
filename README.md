## Morr Assignment
### How to run the app:

Step 1: Run `yarn` command to install npm packages

Step 2 (optional): Run `yarn build` to generate `dist` folder to check the build files 

Step 3: Run `yarn watch` to start the app



### Q & A:
<b>How did you decide on the technical and architectural choices used as part of your solution?</b>

After reading the project requirements in the README file, I decided to develop this app using the following technologies:

- http://webpack.io/webpack.io/webpack.io (for code compling at runtime)

- Building up atomic design concepts
The construction of React components (previous experience)
- styled-components to make it easy to create my own custom components
- React hooks, which I used to develop my own hooks for dealing with API requests. 
- `react-testing library` I have been thinking of doing unit tests (If I can have more time, I can do it)

<b>Are there any improvements you could make to your submission?</b>
  - Unit tests need to be covered
  - css need to be improved [try to follow with design as much as I can]
  - webpack plugins knowledge weakness (need to investigate more)
  - support better responsive display
  - need to setup eslint and husky for pre-checking before commit
  - will refactor `useFetch` function to extract the data filter as an independent function to make code more cleaner
  - forgot to put `prop-types` (need to add in)

<b>What would you do differently if you were allocated more time?</b>
  - defnitely add unit tests (eg: test the custom hook function I wrote)
  - polish `webpack.config.js` file
  - make pixel prefect css (eg: top head bar ingradiant and bottom shadow effect and button styling etc)
  - also will test more responsive display with different browsers (compatibility)
  - improve variable constant namings
  - separate css into few files (tiny and tidy)
  - I may try to use `http-server` library to host `sample.json` file locally in order to make API request 
  - take out `feed` folder from `src` folder
  - can try to deploy the app by using netlify
  - maybe next time can try `Parcel`
