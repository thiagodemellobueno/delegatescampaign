SuperDelegates Campaign
==========

demo site: http://dhornbein.github.io/delegatescampaign


## Requirements

* [Node.js](http://nodejs.org/) >=4
* [npm](http://npmjs.org)


## Usage

### Download the site

    git clone git@github.com:dhornbein/delegatescampaign.git
    cd delegatescampaign


### Install Dependencies

    npm install


### Build

1. Build the site using the following command:

  ```
  npm run build
  ```

2. Visit the compiled `build` folder to see the built site


### Deployment

Deploy the site by running:
  ```
  npm run ghdeploy
  ```

### Development

1. Run the following command to build, watch and serve the site:

  ```
  npm start
  ```

2. Visit [`0.0.0.0:8000`](http://0.0.0.0:8000) in your browser
3. Visit [`0.0.0.0:8000/stylguide`](http://0.0.0.0:8000/styleguide) for the style guide


## Technobabble

* [Metalsmith](http://www.metalsmith.io) static site generator
* [Swig](https://paularmstrong.github.io/swig/) template engine
* [SASS](http://sass-lang.com) CSS pre-processor
* [Grunt](http://http://gruntjs.com/) for automating tasks
