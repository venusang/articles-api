# DESCRIPTION

This is a ruby on rails API that I built following the tutorial "Pagination in Ember with a JSON API Backend" by Frank Treacy (https://emberigniter.com/pagination-in-ember-with-json-api-backend/) .

This is a Rails 6 example with Kaminari (https://github.com/amatsuda/kaminari).

# APP INFO

- Ruby version 2.7
- Rails 6.0.2.1

## Prerequisites

You will need the following things properly installed on your computer.

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/) (with npm)
- [Ember CLI](https://ember-cli.com/)
- [Google Chrome](https://google.com/chrome/)
- Ruby version 2.7
- Rails 5 and up (this uses 6.0.2.1)
- The UI https://github.com/venusang/articles

## Installation

- `$ git clone git@github.com:venusang/articles-api.git`
- `$ cd articles-api`
- `$ bundle install`
- `$ bin/rails db:migrate`
- `$ bin/rails db:seed`
- `$ bin/rails s --binding 0.0.0.0`

## Running / Development

- Verify this app is running by visiting http://localhost:3000/articles
- Verify pagination is working by visiting http://localhost:3000/articles?page%20Bnumber%20B=3&page%5Bsize%5D=1

## Screenshots

 ### http://localhost:3000/articles
 
![Image of articles api](https://raw.githubusercontent.com/venusang/articles-api/master/app-screenshot-01.png)

### http://localhost:3000/articles?page%20Bnumber%20B=3&page%5Bsize%5D=1
 
![Image of articles api](https://raw.githubusercontent.com/venusang/articles-api/master/app-screenshot-02.png)
