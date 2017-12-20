---
layout: page
title: Data and component wiring
published: true
---


At this stage you should have rudimentary functionality in place. For instance if you were building a web or mobile app there should be frontend components hitting api endpoints that are pulling data from the database. You should have all the components/views planned out and started in code even if they are simple placeholders. You should be at the point where you have some of your presentational components (UI) laid out and have started on wiring things together with any data sources such as your api server (or computational/algorithmic logic depending on your project).

## Implementation and Wiring

For this milestone the main idea is to get a "deep" wiring of your project components.  If you have a frontend and backend, make sure they can talk to each other.  If you have computational elements and display elements, this is the time to move past mockup data and have the display use the computed data.  You don't have to have every data connection wired up, but at least one should be working - the idea being to test the full data path.

## README.md

Make sure your README.md files are updated with the current installation and deployment instructions as well as any architecture changes.

## Continuous Integration / Testing (optional)

You could set up Travis CI for your project with automatic linting / build checking. If you are writing for the web - set up your project with eslint.   Whenever you push to github it will automatically run eslint. There are automatic build runners for most languages. This is optional but can be helpful - especially linting.  You can have Travis CI run other stuff/tests. For web here's a small howto on how to set up [Travis](/resources/dev-resources/travis.md).
