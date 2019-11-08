[![Build Status](https://travis-ci.com/yuriigouveia2/personal-page.svg?branch=master)](https://travis-ci.com/yuriigouveia2/personal-page)

# personal-page
This is a static web page project for my personal portfolio. Still in progress.

Click [here](http://d3r1df6s4qxfyl.cloudfront.net/index.html#/home) to access it.

## CI/CD
This application uses the concept of continuout integration and continuous delivery. To build the application I use Travis CI and every commit to the master branch, I configured the `.travis.yml` to publish the new builded application to deploy it directly to a S3 bucket that I host the frontend project as a static web page.
