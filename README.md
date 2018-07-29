# updown-status-page

> General updown.io status page for all your public checks


## How it works

Fetches updown.io's API via the read only key and populates the page.

## Config

 * Fork

 * Edit `page_config.json` and enter your details (read only key, website url, logo url etc.)

 * Link the repositroy to Netlify


## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

## TODO

 * Add loading icon

 * Automatically update checks every x minutes (based on the lowest checks.period)

 * Handle http error

 * Add footer (twitter, email and homepage link)

 * Improve layout for mobile