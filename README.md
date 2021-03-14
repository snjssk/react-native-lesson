// typesync  
yarn add --dev typesync

// eslint  
yarn add --dev eslint  

// 
./node_modules/.bin/eslint --init

```
✔ How would you like to use ESLint? · style
✔ What type of modules does your project use? · esm
✔ Which framework does your project use? · react
✔ Does your project use TypeScript? · No / Yes
✔ Where does your code run? · browser, node
✔ How would you like to define a style for your project? · guide
✔ Which style guide do you want to follow? · standard
✔ What format do you want your config file to be in? · JSON
Checking peerDependencies of eslint-config-standard@latest
The config that you've selected requires the following dependencies:

eslint-plugin-react@latest @typescript-eslint/eslint-plugin@latest eslint-config-standard@latest eslint@^7.12.1 eslint-plugin-import@^2.22.1 eslint-plugin-node@^11.1.0 eslint-plugin-promise@^4.2.1 @typescript-eslint/parser@latest
✔ Would you like to install them now with npm? · No / Yes
```

// prettier  
yarn add --dev prettier eslint-plugin-prettier eslint-config-prettier  

// .prettierrc  
// https://prettier.io/docs/en/configuration.html#docsNav  
touch .prettierrc  
touch .prettierignore
