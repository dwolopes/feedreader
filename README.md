# Feed Reader Testing

This project presents a web-based application that reads RSS feeds. The users can change the subject clicking in the 'menu' button, and through an API informations related to the topic are brought to the Feed. To make sure the applications will work perfectly, tests were implement using Jasmine. Assiscronous tests is one of the the many tests done in this project.

## Demo

> [Check it live](https://dwolopes.github.io/feedreader/).

## Getting Started

In order to play the game properly, consider the following steps:

1. Clone project:

    ```
    $ [sudo] git clone git@github.com:https://github.com/dwolopes/feedreader.git
    ```

2. Serve the application:

    ```
    $ [sudo] python -m SimpleHTTPServer
    ```

3. Open the game:

    ```
    $ open "http://localhost:8000"
    ```
    
### Prerequisites

In order to run the game properly, consider install:

    Python

> [Dowload Python](https://wiki.python.org/moin/BeginnersGuide/Download).


## Running the tests

Jasmine library (version 2.2) is already included in the project. After download that, you will see the tests Suites and Specs in the initial page. Click in each espec to run that test specifically.

### Break down into end to end tests

* RSS Feeds

    * It must have URl' loops through each feed and it should not be empty.
    * It must have name'loops through each fedd and it should not be empty.

* The menu

    * It should be hidden by default.
    * It should open and close by clicking on the hamburger button.

* Initial Entries

    * When loadFeed function is called and completes its work, there should be at least one .entry element within .feed container.

* New Feed Selection

    * it should change the contents when new feed is loaded.

## Built With

* [JavaScript](https://www.javascript.com/) - The main programming language used
* HTML
* CSS

## Contributing

Please read [CONTRIBUTING.md](./CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Authors

* **Douglas Lopes** - *Initial work* - [Douglas Lopes](https://github.com/dwolopes)

See also the list of [contributors](https://dwolopes.github.io/feedreader/) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](./LICENSE.md) file for details