⚠️ This is a fork that serves as the frontend for a Uniswap app in Nomos. It includes minor customizations and fixes to better suit this particular use case.

### Pre-requisites

This fork requires a fully deployed Uniswap instance and two custom tokens to be available on the chain.
That information must be provided via an `.env` file (already present in the repository, albeit with placeholder values) or through environment variables:
```
REACT_APP_NOMISWAP_ROUTER_ADDRESS=0x0
REACT_APP_NOMISWAP_TOKEN_NMO_ADDRESS=0x1  # (Stand-in for NOMOS)
REACT_APP_NOMISWAP_TOKEN_MEM_ADDRESS=0x2  # (Stand-in for MEHMET)
```

### Running

To run the app simply install the dependencies with `yarn install` and then run `yarn start`.

### Troubleshooting

- If the web app doesn't load (e.g., the screen stays white), it's likely due to incorrect address values. You can usually gather more information by opening your browser's developer console.
- If issues persist, please open an [Issue](https://github.com/logos-co/nomos-example-uniswap).

---

### 📄 Original README Below

---

# NOTE: This is a proof-of-concept. Use it at your own risk, and it's not intended for any sort of production use.

This is an alternative interface to Uniswap V2 contracts deployed on an EVM blockchain. We used ReactJS for the project, with the EthersJS module to connect to the blockchain via metamask in the browser, and Material-UI for the frontend. As it was a static site, we used github pages to host the application.


Publishes to [https://ben-haslam.github.io/Alternative-Uniswap-Interface/]()

Check out the blog [here](https://medium.com/clearmatics/how-i-made-a-uniswap-interface-from-scratch-b51e1027ca87)

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**
