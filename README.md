# 

## Installation

Install the gem:

    gem install kickster

Execute gem and scaffold Kickster files:

    kickster new site_name

Setup your environment:

    cd site_name
    bin/setup

You can push your project to any branch except `gh-pages`. For `sitename.github.io` repo users make sure to use another branch than `master`.

## Development

Run Jekyll:

    bundle exec jekyll serve

*If you do not want the Kickster setup but just the deploy scripts then copy them from the `bin` folder.*

## Deploy to GitHub Pages

Run this in the root project folder in your console:

    bin/deploy

*Don't forget to enable your repository on [Circle CI](https://circleci.com/docs/getting-started) and update the `_config.yml` file with your url!*
