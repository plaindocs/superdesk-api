# Superdesk API Documentation

[![Build Status](https://travis-ci.org/petrjasek/superdesk-api.svg?branch=master)](https://travis-ci.org/petrjasek/superdesk-api)

## Render the api

You can use [`aglio`](https://github.com/danielgtaylor/aglio) to render the api:

    ./node_modules/aglio/bin/aglio.js -i apiary.apib -o out.html

You can use [`protagonist`](https://github.com/apiaryio/protagonist) to test that the api has valid json:

    node test.js
