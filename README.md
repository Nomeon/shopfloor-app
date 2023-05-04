# :house: Shopfloor Viewer 
<br/>
<div  align="center">

![Shopfloor Viewer Banner](https://github.com/Nomeon/shopfloor-app/blob/master/banner.png?raw=true)
<br/>

[![forthebadge](http://forthebadge.com/images/badges/uses-html.svg)](http://forthebadge.com)&nbsp;&nbsp;&nbsp;[![forthebadge](http://forthebadge.com/images/badges/uses-css.svg)](http://forthebadge.com)&nbsp;&nbsp;&nbsp;[![forthebadge](http://forthebadge.com/images/badges/uses-js.svg)](http://forthebadge.com)
  
</div>


## :moyai: Overview

The aim of this project is to create an IFC viewer with specialized functionality for the shopfloor. Generic BIM viewers cannot be customized much, which causes often used functions to be hard to reach. This viewer tends to solve that issue, by only implementing what's necessary in a convenient way.
  
<br />

## :books: Packages used:

**`electron`** allows the creation of desktop applications with JavaScript by providing a runtime with rich native (operating system) APIs.

**`electron-builder`** is used as a complete solution to package and build a ready for distribution to Windows, MacOS, and Linux.

**`web-ifc-viewer`** doesn't only parse and generate the THREE.js geometry of IFC models in JavaScript, but also provides multiple tools to parse proprties, create clipping planes, etc.

**`svelte`** handles the frontend of the application. With Svelte, you can write Javascript in the HTML to load data dynamically. This allows for much cleaner code regarding displaying the details of an IFC model for example.

<br />

## 🚀 Getting Started


```bash

# Clone the Project

$  git  clone  https://github.com/Nomeon/shopfloor-app.git

  
# Switch location to the cloned directory

$  cd  shopfloor-app

  
# Install dependencies

$  npm install

  
# Run your app

$  npm run dev


# Package Your App

$  npm run  electron-pack

```

<br />

## :memo: Contents

- `src/App.svelte`: IFC viewer and the logic behind it
- `src/Icon.svelte`: Component to serve icons dynamically
- `src/Help.svelte`: Component which creates the 'help' overlay
- `public/global.css`: Styling of the viewer

<br />

## :construction: Functionalities and future implementations

- [x] IFC viewer: geometry and data
- [x] Creating subsets based on custom property
- [x] Isolating an element
- [x] Hiding one/multiple element(s), even on subsets
- [x] 3D clipping planes
- [x] Showing transparent elements of previous workstations
- [x] Custom Property menu: only gives select, necessary information from a custom pset
- [x] Measurement with snap functionality
- [x] Help menu overlay

- [ ] Ability to select path for custom properties?

<br />

## ✒️ Author

Stijn Nijhuis
- [LinkedIn](https://www.linkedin.com/in/stijn-nijhuis-56593524a/)
- [GitHub](https://github.com/Nomeon)

<br />

## :heavy_check_mark: Acknowledgments

Inspiration, code snippets, etc.

- [IFC.js](https://ifcjs.github.io/info/)
- [Francesca's viewer](https://github.com/duffra/BIMexp_o)
- [Svelte + Electron](https://github.com/soulehshaikh99/create-svelte-electron-app)
