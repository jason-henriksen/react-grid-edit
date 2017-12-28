# React Data Grid 
Excel-like grid component for with editors, keyboard navigation, copy/paste, excellent performance, and much much more...
https://github.com/react-data-grid/react-data-grid  


[Join the discussion on slack](https://react-data-grid.slack.com/)





![React Data Grid chat](https://react-data-grid.herokuapp.com/badge.svg)



Installation
------------
2017-12-12:  THIS PROJECT IS CURRENTLY IN TRANSITION.  We hope to be ready for use sometime in January of 2018.

We have moved from adazzle to react-data-grid as the hosting organization.  NPM will be updated soon.  

```sh
npm install react-data-grid
```

This library is written with CommonJS modules. If you are using browserify, webpack, or similar, you can consume it like 
anything else installed from npm.

Overview 
--------
ReactDataGrid is an advanced JavaScript spreadsheet-like grid component built using React.

Themes
------
Our themeing solution is changing with this fork.
Our plan is to supply a stand-alone style sheet with additional theme support for Bootstrap, Material UI and easily accessible hooks to perform your own styling.


Migrations
--------
If you intend to do a major release update for you react-data-grid check [the migration documents](migrations).
We are not planning any breaking changes as we move from ADazzle to this repository.  However, some css changes may occur and will be called out in release notes.
  
Features
--------
( Example code for all features will be provided.  However we are still in transition as of 2017-12-12 )

- Lightning fast virtual rendering
- Can render hundreds of thousands of rows with no lag
- Keyboard navigation
- Fully editable grid
- Rich cell editors like autocomplete, checkbox and dropdown editors, complete with keyboard navigation
- Custom cell Editors - Easily create your own
- Custom cell Formatters
- Frozen columns
- Resizable columns
- Sorting
- Filtering
- Context Menu
- Copy and Paste values into other cells
- Multiple cell updates using cell dragdown
- Association of events of individual columns
- Easy to use with both MobX and Redux

We our forking the examples into a stand alone Create-React-App example project for ease of use and simple, in-browser experimentation.

FAQs
----

- Why is react-data-grid better than other grid tools?
> react-data-grid minimizes the amount of churn when rendering.  It can handle millions of records and still provide excellent rendering speed.  It also provides a wide array of features for editing and managing your data.

- What is the data store requirement
> react-data-grid is very flexible.  If you already have an array of JSON objects, you're ready to view and edit that data with react-data-grid.  It works easily with MobX and Redux.

- Why is this fork required?
> ADazzle has done great work and we hope that they will continue to be a supporter of this project.  They are welcome to pull in our enhancements to their project and uses.  However, their management goals did not align with react-data-grid getting the fixes and deployment attention it deserves.  This fork of the project continues to be MIT licensed, but will be more focused on accepting pull requests in a timely and efficient manner.  Many fixable issues had been left wanting for attention and we plan to change that.  This fork will resolve many long standing issues and provide enhanced documentation.


Contributing
------------

Please see [CONTRIBUTING](CONTRIBUTING.md)

Credits 
------------
This project has been built upon the great work done by [Prometheus Research](https://github.com/prometheusresearch). For the original project, please click [here]( https://github.com/prometheusresearch/react-grid). It was then managed by ADazzle before it was forked into this repository.   react-data-grid is released under the [MIT](https://github.com/react-data-grid/react-data-grid/blob/master/LICENSE) license.

