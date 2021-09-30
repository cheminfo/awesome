# **Awesome ChemInfo** [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A collection of awesome things for ChemInfo developers

- [Front-end](#front-end)
  - [State management](#state-management)
    - [immer](#immer)
  - [React](#react)
    - [draft-js](#draft-js)
    - [formik](#formik)
    - [nivo](#nivo)
    - [react-dropzone](#react-dropzone)
    - [react-fontawesome](#react-fontawesome)
    - [react-inspector](#react-inspector)
    - [react-mutable-context](#react-mutable-context)
    - [react-select](#react-select)
    - [react-window](#react-window)
    - [the-platform](#the-platform)
    - [use-immer](#use-immer)
- [Back-end](#back-end)
  - [Querying other servers](#querying-other-servers)
    - [got](#got)
  - [Buffer utilities](#buffer-utilities)
    - [crypto-md5](#crypto-md5)
    - [base64-js](#base64-js)
    - [fast-xml-parser](#fast-xml-parser)
    - [jszip]([jszip])
    - [node-gzip](#node-gzip)
    - [pako](#pako)
    - [papaparse](#papaparse)
    - [xlsx](#xlsx)
  - Sending email
    - [nodemailer](#nodemailer)
  - Node applicatins
    - [pkg](#pkg)
    - [yargs](#yargs)
    - [colorette](#colorette)
- [Math and processing](#math-and-processing)
  - [Pure math](#pure-math)
    - [ml-matrix](#ml-matrix)
  - [Processing](#processing)
    - [fft.js](#fft.js)
    - [Array](#array)
    - [Array XY](#array-xy)
- [On line tools](#online-tools)
  - [Graphical](#graphical)
  - [Javascript](#javascript)

## Front-end

### State management

#### [immer](https://github.com/mweststrate/immer)

Create the next immutable state by mutating the current one.

### React

#### [draft-js](https://github.com/facebook/draft-js)

A React framework for building text editors.

Draft.js is a JavaScript rich text editor framework, built for React and backed by an immutable model.

#### [formik](https://github.com/jaredpalmer/formik)

Build forms in React, without the tears.

#### [nivo](https://github.com/plouc/nivo)

nivo provides supercharged React components to easily build dataviz apps, it's built on top of d3.

#### [react-dropzone](https://github.com/react-dropzone/react-dropzone)

Simple HTML5-compliant drag'n'drop zone for files built with React.js.

#### [react-fontawesome](https://github.com/FortAwesome/react-fontawesome)

Font Awesome 5 React component

#### [react-inspector](https://github.com/storybookjs/react-inspector)

Advanced component allowing not only to inspect objects but also the DOM. Check the [storybook](https://react-inspector.netlify.com/?selectedKind=Numbers&selectedStory=positive&full=0&addons=1&stories=1&panelRight=0).

#### [react-mutable-context](https://github.com/targos/react-mutable-context)

Create a React context that can accessed and mutated with hooks.

#### [react-select](https://github.com/JedWatson/react-select)

The Select control for React.

#### [react-window](https://github.com/bvaughn/react-window)

React components for efficiently rendering large lists and tabular data

#### [the-platform](https://github.com/palmerhq/the-platform)

Web API's turned into React Hooks and Suspense-friendly React components.

#### [use-immer](https://github.com/mweststrate/use-immer)

A hook to use immer as a React hook to manipulate state.

## Back-end

### Sending email

#### [nodemailer](https://github.com/nodemailer/nodemailer)

Send quickly and easily emails from node

### Node applications

#### pkg

[pkg](https://github.com/zeit/pkg#readme)

Allows to create a cross-platform self contained executable

#### [yargs](https://github.com/yargs/yargs)

Parse the arguments given from command line

#### [colorette](https://github.com/jorgebucaran/colorette)

Allows to color the console.log in the terminal

### Querying other servers

#### [got](https://github.com/sindresorhus/got)

Got is a human-friendly and powerful HTTP request library.

### Buffer utilities

#### [base64-js](https://github.com/beatgammit/base64-js)

Encode / decode base 64 using bytes array.

#### [crypto-md5](https://github.com/jtblin/crypto-md5)

Generates an md5 hash using node crypto module.
Equivalent to `crypto.createHash('md5').update(data).digest('base64');`.

#### [fast-xml-parser](https://github.com/NaturalIntelligence/fast-xml-parser#readme)

Validate XML, Parse XML to JS/JSON and vice versa, or parse XML to Nimn rapidly without C/C++ based libraries and no callback.

#### [jszip](https://github.com/Stuk/jszip#readme)

Allows to zip and unzip files with promises. Works
in Node.js as well as in the browser.

#### [node-gzip](https://github.com/Rebsos/node-gzip)

Simply gzip and ungzip in Node.js with promises.

#### [pako](https://github.com/nodeca/pako)

High speed zlib port to javascript, works in browser and Node.js.

#### [papaparse](https://www.npmjs.com/package/papaparse)

Parse CSV files.

#### [xslx](https://www.npmjs.com/package/xlsx)

Convert excel, xls, xlsx files to json or text.

## Math and processing

### Pure math

#### [ml-matrix](https://github.com/mljs/matrix)

Matrix manipulation and computation library

### Processing

#### [fft.js](https://github.com/indutny/fft.js#readme)

#### Array

Fast small packages to get some stats / info on array of numbers.

- [ml-array-sequential-fill](https://github.com/mljs/array/tree/master/packages/ml-array-sequential-fill) Fill / create an array with sequential numbers
- [ml-array-min](https://github.com/mljs/array/tree/master/packages/ml-array-min) Get the minimum value in an array
- [ml-array-max](https://github.com/mljs/array/tree/master/packages/ml-array-max) Get the maximum value in an array
- [ml-array-rescale](https://github.com/mljs/array/tree/master/packages/ml-array-rescale) Rescale an array into a range
- [ml-array-mean](https://github.com/mljs/array/tree/master/packages/ml-array-mean) Get the average value in an array
- [ml-array-median](https://github.com/mljs/array/tree/master/packages/ml-array-median) Get the median value in an array
- [ml-array-mode](https://github.com/mljs/array/tree/master/packages/ml-array-mode) Get the first mode value in an array
- [ml-array-normed](https://github.com/mljs/array/tree/master/packages/ml-array-normed) Get a normed array
- [ml-array-sum](https://github.com/mljs/array/tree/master/packages/ml-array-sum) Get the sum or the array elements
- [ml-array-variance](https://github.com/mljs/array/tree/master/packages/ml-array-variance) Get the variance in an array
- [ml-array-standard-deviation](https://github.com/mljs/array/tree/master/packages/ml-array-standard-deviation) Get the standard deviation in an array

#### Array XY

Fast small packages to get some stats / info on an object containing properties `x` and `y` that are arrays of numbers.

- [ml-array-xy-centroids-merge](https://github.com/mljs/array/tree/master/packages/ml-array-xy-centroids-merge) Merge abscissa values if the ordinate value is - in a list of centroids
- [ml-array-xy-covariance](https://github.com/mljs/array/tree/master/packages/ml-array-xy-covariance) Calculates covarience of 2 vectors
- [ml-array-xy-equally-spaced](https://github.com/mljs/array/tree/master/packages/ml-array-xy-equally-spaced) Returns equally spaced data
- [ml-array-xy-filter-x](https://github.com/mljs/array/tree/master/packages/ml-array-xy-filter-x) Filter data based on x values
- [ml-array-xy-integrate](https://github.com/mljs/array/tree/master/packages/ml-array-xy-integrate) Integrate data
- [ml-array-xy-weighted-merge](https://github.com/mljs/array/tree/master/packages/ml-array-xy-weighted-merge) Merge abscissa values on similar ordinates and - weight the group of abscissa
- [ml-array-xy-max-merge](https://github.com/mljs/array/tree/master/packages/ml-array-xy-max-merge) Merge abscissa values on similar ordinates and keeps the - abscissa with bigger ordinate value
- [ml-array-xy-max-y](https://github.com/mljs/array/tree/master/packages/ml-array-xy-max-y) Sort a set of point based on the abscissas values
- [ml-array-xy-weighted-merge](https://github.com/mljs/array/tree/master/packages/ml-array-xy-weighted-merge) Ensure x unique and merge y
- [ml-arrayxy-uniquex](https://github.com/mljs/array/tree/master/packages/ml-arrayxy-uniquex) Ensure that x values are unique

## Online tools

### Graphical

- [figma](https://www.figma.com) Collaborative design application that replaces adobe illustrator

### Javascript

- [bundlephobia](https://bundlephobia.com/) Determine the size of your dependencies
- [jspm](https://jspm.org/) Convert npm package to javascript code compatible with the browser
