# About

This repo contains images for testing Odoo projects in an CI/CD environment. I've chosen [CircleCI](https://circleci.com/) but you can use something else.

## Updater Image
This image listens for github webhooks, when a new package is released for the target repo it will pull the new image and stop the old container while starting the the new one.
