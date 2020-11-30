## IMDB-Comparison-App

This app contains 2 sub-modules, a back-end app (NestJS + TypeScript) & front-end app (React Hooks + Recharts + Material UI).

The back-end is using Puppeteer in order to scrape IMDB movie pages (by thier URL) and returns a normalized "Movie" object to it's consumers.

The front-end app contains many comparison charts in order to analyze the correlation between different parameters in those movies.

(yarn was used during the development)

## Usage

1. Clone this repository with its submodules (`git clone --recursive https://github.com/avi182/imdb-comparison-app.git`)
2. Run "yarn/npm run install-apps"
3. Ensure port 3000 & 5000 are free on your machine
4. Run "yarn/npm start"

## Enjoy!
