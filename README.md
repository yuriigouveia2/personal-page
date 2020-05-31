[![Build Status](https://travis-ci.com/yuriigouveia2/personal-page.svg?branch=master)](https://travis-ci.com/yuriigouveia2/personal-page)

# personal-page
This is a static web page project for my personal portfolio. Still in progress.

Click [here](http://d3r1df6s4qxfyl.cloudfront.net/index.html#/home) to access it.

## CI/CD
This application uses the concept of continuout integration and continuous delivery. To build the application I use Travis CI and in every commit to the master branch, due to a configuration at the `.travis.yml`, the new builded application is deployed directly to a S3 bucket, which I host the frontend project as a static web page.
 
