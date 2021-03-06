# Changes Log

###### 2.3.0

* add `lodash` module to shuffle the array of countries code
* add default headers to each requests
* update `_donwloadAllReviews` behavior (use a queue with 5 concurrent workers)

###### 2.2.2

* update examples (use `Movist` instead of `The Beatblaster`)
* `npm run-script xxx` will create a JSON file in the `tmp` folder
* upgrade third party modules version
* add gitter badge
* remove TravisCI configuration file and badge

###### 2.2.1

* remove remaining `console.log(...)`

###### 2.2.0

* add examples
* add a delay before each request (optional)
* choose between `JSON` and `XML` format for the response (you can find an update date for all reviews in `XML` format)

###### 2.1.2

* fix issue when HTTP status code (403) returned by Apple service

###### 2.1.1

* fix issue with undefined nextPageURL

###### 2.1.0

* retrieve next page url in Apple response instead of creating it
* return all reviews in one array instead of pages of reviews

###### 2.0.3

* update third party modules

###### 2.0.2

* update README with badges

###### 2.0.1

* add (again) `country_code` attribute on a review object. Useful when using events
* update README

###### 2.0.0

* use of events
* update schema
* update `package.json`
* update README

###### 1.0.1

* add `helpful_vote_count` and `total_vote_count` attributes to the review object

###### 1.0.0

* module creation
