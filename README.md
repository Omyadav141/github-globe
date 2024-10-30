# Github Globe

![github-globe made by Om yadav](https://github.com/Omyadav141/github-globe/blob/main/ommcre8.png)

## Inspiration

This project was inspired by [Github's homepage](https://github.com/home), where they display real-time Github activity on a globe map.

## Implementation

GitHub Globe
Overview
The GitHub Globe project visualizes real-time GitHub activity on a 3D globe using Three.js. Inspired by GitHub’s homepage, this project aims to provide an engaging way to see global GitHub activity.

Features
Real-time Data Visualization: Displays recent pull requests and merges from around the world.
Interactive 3D Globe: Rotate and zoom to explore different regions.
Customizable: Easily add your own data and customize the globe’s appearance.
Installation
To get started with the GitHub Globe project, follow these steps:



Usage
Development: The development build is available in the ./dist directory.
Production: The static production build is also in the ./dist directory.
Customization
To customize the globe, you can modify the src files. For detailed documentation, please visit the three-globe documentation.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Contributing
Contributions are welcome! Please open an issue or submit a pull request.

Acknowledgements
Three.js: A JavaScript 3D library.
three-globe: A Three.js data-visualization project by @vasturiano.
Feel free to modify any sections 

## [Live demo](https://omyadav141.github.io/github-globe/)

All attended/cancelled flights (2019-2020) are displayed on the globe. If you try to follow one arc, that would be the sequence of travel destinations. Red arcs are cancelled flights.


## Usage

This project is bundled with [Webpack](https://webpack.js.org/):

```json
"build": "webpack --config=webpack.prod.js",
"build-dev": "webpack --config=webpack.dev.js",
"start": "webpack serve webpack-dev-server --open --config=webpack.dev.js"
```

Details:

```bash
npm start        # development build in ./dist
npm run build    # static production build in ./
```

## License

[MIT](https://choosealicense.com/licenses/mit/)

