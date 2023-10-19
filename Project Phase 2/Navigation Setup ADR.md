# Title

Wacky Weather: Navigation Setup
Date: 2023-10-14
William Black, Robert Carlson, Paul Sholter

## Status

Approved, Navigation stack tool. Using imported functions to display pages.

## Context

Our app has needs to have a small variety of basic features to ensure requirements are met. These include having a welcome page, a home page to provide the user with basic features, and a page where users can customize their experience (settings). We need to implement a navigation system that will make it easy to the user to switch between these pages.

## Decision

We have decided to use navigation stack to fulfill this requirement. We have decided to implement three main pages, home page, display page, and settings page. The home page will be opened upon starting the app, this will display basic information and navigation tools. The display page will implement more detailed information about weather, location, and jokes related to the weather. Settings page will used to customize certain features and tailor the user experience. All these pages will be navigated to from a navigation bar. Each of these pages will also be separate .js files which will imported into the navigation stack to make our code cleaner and more maintainable

## Consequences

This will allow users a easy and friendly way of looking at different features. The navigation stack is also an easy to implement react native feature which will allow us to integrate it into our app more seamlessly. The is also a lot of node modules and attributes which can used in conjuction with navigation stacks to create animations and unique features to make a more engaging user experience.
