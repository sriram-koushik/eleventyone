# EleventyOne

[![Netlify Status](https://api.netlify.com/api/v1/badges/056b4a67-70e6-4af4-9be5-dee151b8e906/deploy-status)](https://app.netlify.com/sites/eleventyone/deploys)

Phil's first port of call when starting another project using Eleventy.

This project scaffold includes:

- Eleventy with a skeleton site and some configs I use regularly
- A date format filter for Nunjucks
- Sass pipeline
- JS pipeline
- Serverless (FaaS) development pipeline with Netlify Functions for Lambda


![Eleventy screenshot](./eleventyone-template.png)


## Instructions

To get your own instance of this 11ty starter project cloned and deploying to Netlify very quickly, just click the button below and follow the instructions.

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/philhawksworth/eleventyone)


## Wait, what happens when I click that button?

Good question. Here's what it will do...

1. Netlify will clone the git repository of this project into your Github account. It will be asking for permission to add the repo for you.
2. We'll create a new site for you in Netlify, and configure it to use your shiny new repo. Right away you'll be able to deploy changes simply by pushing changes to your repo.
3. That's it really.


## Local development

To build the site you need:

- [Node](https://nodejs.org) - to run the build
- [Yarn](https://yarnpkg.com) - to install and manage dependencies


### Getting started

```bash

# clone this repository
git clone git@github.com:philhawksworth/eleventyone.git

# go to the working directory
cd eleventyone

# install dependencies
yarn

# start a local build server with hot reloading
yarn start
```


