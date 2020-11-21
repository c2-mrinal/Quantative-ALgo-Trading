# Quantitative Algorithmic Trading
The proposed system helps the people in the stock market business and makes it easy for them to decide where to invest their valuable money and what is the best time to sell the stocks they own. The data for Stock charts and Forex conversion will be provided by the Alpha Vantage API which provides current data of any NASDAQ listed company with their stock values and past performances. Other components use the TradingView library. It also provides years worth of data whenever needed. The system is intended to be distributed under the MIT License.


## Table of Contents
* [Installation](#installation)
* [Usage](#usage)
* [What's included](#whats-included)
* [System Architecture Overview](#system-architecture-overview)
* [Contributing](#contributing)
* [Documentation](#documentation)

## Installation

``` bash
# Go to the directory where you want to clone the repo
$ cd dir_name

# Clone the repo
$ git clone https://github.com/bjpadhy/quantitative-algo-trading.git quantitative-algo-trading

# Go into app's directory
$ cd quantitative-algo-trading

# Install app's dependencies
$ npm install
```

## Usage

``` bash
# Serve with hot reload at localhost:3000. Port number maybe different. Check terminal logs.
# Use this for development
$ npm run serve

```

## What's included
Within the download you'll find the following directories and files, logically grouping common assets and providing both compiled and minified variations. You'll see something like this:
``` 
quantitative-algo-trading
├── .github/ISSUE_TEMPLATE/
│   ├── bug_report.md
├── assets/
│   ├── logo.jpg
│   ├── logo.png
│   ├── logo.svg
├── css/
│   ├── style.css
│   ├── style.css.map
│   ├── style.min.css
│   ├── style.min.css.map
├── js/
│   ├── symbols.js
├── .gitignore
├── aboutus.html
├── forex.html
├── index.html
├── issue.html
├── marketinfo.html
├── marketnews.html
├── strategy.html
├── package.json
├── package-lock.json
├── LICENSE
└── README.md
```

## System Architecture Overview

![System Architecture Overview](https://lh3.googleusercontent.com/pw/ACtC-3eWH69gYq9NRra535M8VfXydzRSfAO_SnQ4g6N5wEIMmhsi7IZxU1jn5R9fMuj5meybwOWQk_QTCFRCTD3wvILfTr-ML1NHxWlWgrbh340JYkL90jZBOpYt80m8LSDPJzhDBlc6uIYCRO2liu2zjK1q_g=w2326-h1642-no)

## Contributing

Edit files in the / directory. When you run ```npm run serve``` the project will be served on localhost from / with hot reload enabled. i.e any changes made and saved to a file will be visible in browser without having to reload the page. When all changes are stable and nothing seems to be broken, commit the changes along with a descriptive message.

### Committing and Pushing to GitHub

Stage all changes. **Include a descriptive commit message clearly stating the changes made.** Push ta new branch and issue a Pull Request to master only if a module is complete, 100% working and doesn't break anything else. **Biswaranjan Padhy** will resolve any conflicts and merge to master as and when required.

- If you have no experience with Git then follow the quick guide at [GitHowTo](https://githowto.com/)

## Documentation

- Documentation for the CoreUI Bootstrap Template is hosted at [CoreUI](https://coreui.io/docs/getting-started/introduction/#coreui-admin-template)
- [TradingView](https://www.tradingview.com/widget/) Library Documentation
- AlphaVantage API [Documentation](https://www.alphavantage.co/documentation/) and Vanilla JavaScript [cookbook](https://prediqtiv.github.io/alpha-vantage-cookbook/)
- Design and Business documents pertaining to this project are located at [Documentation](https://drive.google.com/open?id=1f4cEnPXLHRUnu_AwKlCRpet3rGzvd-_P)

**The ReadME shall be updated with future changes and enhancements**
