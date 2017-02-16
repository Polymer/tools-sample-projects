# tools-sample-projects
Sample projects that Polymer tools should handle.


## polymer-1-app

The pure 1.0 app scenario is mostly a regression test of a scenario: our tooling shouldn't break 1.0 support. `polymer-1-app` contains several elements in the `views/` directory that highlight the use of Polymer 1.x-only patterns and APIs. When the application is viewed in a browser, each view is a separate page that should render and behave as expected. Linting, Testing, and Serving should continue to work for all of these application elements.


## polymer-2-app

The pure 2.0 app scenario represents an application completely migrated over to Polymer 2.0. `polymer-2-app` contains several elements in the `views/` directory that highlight the use of Polymer 2.x-only patterns and APIs. When the application is viewed in a browser, each view is a separate page that should render and behave as expected. Linting, Testing, and Serving should continue to work for all of these application elements.


## polymer-1-hybrid-app

Still TODO, once polymer-1-app & polymer-2-app are finalized. An application running on Polymer 1.0 with some 1.0-only elements and some hybrid elements. This will represent an app transitioning from 1.0 to 2.0.


## polymer-2-hybrid-app

Still TODO, once polymer-1-app & polymer-2-app are finalized. An application running on Polymer 2.0 with some hybrid elements and some 2.x elements. This will represent an app transitioning from 1.0 to 2.0.
