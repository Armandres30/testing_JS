# Automatically create .gitignore file for a project. Copy in your .gitignore file
https://www.toptal.com/developers/gitignore

# Copy into .editconfig file from "edit config airbnb" google searche url:
https://github.com/airbnb/javascript/blob/master/.editorconfig

# Install running commands in installation.sh in /src folder and then run tests with:
npm run test

## Add "test": "jest ", in package.json

### IMPORTANNT ADD LINT AND LINT FIX COMMANDS SCRIPTS IN PACKAGE.JSON

## ADD "jest: true," in .eslintrc.js

# Then for showing lint issues run following:
npm run lint

# For for fixint lint issues (fixing static errors in code automatically) run:
npm run lint:fix

# To show coverage of unit tests
npm run test -- --coverage