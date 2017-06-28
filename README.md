# Open Savannah Brigade Data Sharing Hub [![Build Status](https://travis-ci.org/timwis/jkan.svg?branch=gh-pages)](https://travis-ci.org/timwis/jkan)

This is a simple, lightweight, database-free open data sharing hub for [Open Savannah](https://opensavannah.org) brigade members. It is powered by [JKAN](https://github.com/timwis/jkan), and uses Jekyll to serve static files and Gatekeeper to enable authentification via GitHub.

To access the admin  portal and upload new datasets/create organizations, you **must be a member of the Open Savannah organization repository on GitHub**. If you're not a member of this GitHub org., you may request to be added by emailing the Core Leadership team at yall@opensavannah.org.

This project is not to be confused with the more robust, public-facing [Open Savannah instance of DKAN](https://test-city-of-savannah.pantheonsite.io) intended as a protoype for local government agencies to use.

## Development
Please see the [Architecture](https://github.com/timwis/jkan/wiki/Architecture) page in the wiki.

## A note of caution:

Avoid putting any numbers in a date format of YYYY-MM-DD into the [submission form to add a dataset](https://opensavannah.github.io/jkan/add-dataset/). Information in these fields populates the top matter of the dataset's MD page. The date format confuses the parser and it will not output a static page for the dataset.
