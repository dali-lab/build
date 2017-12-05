---
layout: page
title: Mockups & Data Models & Scaffolding
published: true
---



![](img/mockups.gif){: .fancy .small}

# Design

## Mockups/Sketches

Based on the various features and pages you described in the feature spec, draw up sketches of each view.  Napkin style quick sketches are a good place to start. Focus more on thinking through the common actions that the users will be making rather than how and where the buttons go.  As you draw our these sketches with your team several things will come to light, features you might have missed or interactions that need to be changed.  Make your sketches comprehensive, they should cover all the views and functionality that your apps needs. Additionally you should make a site map style overview showing how the views are connected.

Don't worry too much about making pixel perfect designs, once you have some sketches, refine them and feel free to make them pretty. It's more important to think through layout and functionality than making sure your color scheme or logo are perfect as you can continue to iterate on those.  I recommend against most wireframing software, for wireframing you might as well just sketch on paper, waste of time to learn a separate program.

Once you are ready to make it prettier just go straight into a tool like [Figma](https://www.figma.com/) (free for students). [Invisionapp](https://www.invisionapp.com/) is a nice way to put your designs together.  [Pop](https://marvelapp.com/pop/) — Prototyping on Paper, is a good way to get started without doing high quality designs and get something that you can click through.

There are many good design resources out there. Here's [one](http://cdn.ustwo.com/PPP/PP3.pdf) about pixel perfect design.

[Here's an beautiful example](https://projects.invisionapp.com/share/HABOKZQRZ#/) of an invision walkthough for a smaller scope 2 week project from CS52 and [a tutorial for figma](http://cs52.me/workshops/design).  And another cool invision mockup for a [project that did AR](https://projects.invisionapp.com/share/76AJI0NJN).


## Data Models
This is also a good time to plan out some of your data models.  Consider what data you need for your project and figure out some of the fields and objects.  You don't need to create a full relational model, but do consider what your data should look like. Describe the objects you think you will need (an informal schema for your data).  Create a Wiki page with the data models you plan out.

## Summary
* Mockups submitted in [invisionapp](https://www.invisionapp.com/) or [figma](https://www.figma.com) links - link from your github wiki!
* Sketches of each view of your product
* A site map showing how your views interconnect (can be hand drawn)
* Data Models on a Wiki page
* Submit urls to each wiki page on canvas

# Code

![](http://i.giphy.com/GWbMbUysgsIda.gif){: .fancy .medium}

This milestone is all about setting up some initial code scaffolding.

## Scaffolding

Now that you have your functionality mapped out let’s start on planning the coding. You now have the features all planned out. How do you want to build it? Plan out what technology you think you want to use and let’s get some code scaffolding ready. The project does have some minimal technical complexity that must be satisfied, but you are free to choose whatever tech stacks you wish.

You should get some basics of your project up and running.  If your project as a UI try to do a little layout so that you have a main component and a hello world for the frontend and a hello world from the backend. If you have an idea of any modules and libraries you are planning on using, document them and or get them installed in your repos. At this point you should have your project code started and ready to work on.  The frameworks should be set up and running and a local development environment set up for everybody on the team.

## Readme

In your project’s main README.md file (you may have multiple repos, but for now just use the repo you’ll be using for whatever is ending up being the frontend) start to outline the tech stack you will using. As you work on the project your README.md file will be a record of the tools you are using and how to get your dev environment running.

Start this doc now:
```

# Project Name

TODO: short project description, some sample screenshots or mockups

## Architecture

TODO:  descriptions of code organization and tools and libraries used

## Setup

TODO: how to get the project dev environment up and running, npm install etc

## Deployment

TODO: how to deploy the project

## Authors

TODO: list of authors

## Acknowledgments
```

You don’t have to fill in the whole document for this milestone, but do start on it and fill in what you can. This README is for now the defacto "landing page" for your project. It should be kept up-to-date so that I / anybody can clone your repos and run your project dev environment.

Note: using github will be an essential part of how you will work together.  You are required to use git flow — i.e. use branches and pull requests as you work together. You don’t necessarily need to do code reviews, but doing git flow with feature branches will help you organize your team and your code.

## Summary
* GitHub URL to your repo on canvas (for grading ease)
* Code scaffolding:
  * some initial starter code
  * working hello worlds for any server/frontend/etc platforms
  * github repos set up with README.md files started
  * demonstrated use by every team member of git branches -> pull requests
