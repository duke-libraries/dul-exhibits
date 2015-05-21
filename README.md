Getting Started with DUL-Exhibits
====================

This project uses [Middleman](https://middlemanapp.com), a static site generator, that uses ERB templates, sprockets, and other Ruby on Rails conventions.

1. To get started with this project first clone this repository to your workstation.

    ```
    $ git clone git@github.com:duke-libraries/dul-exhibits.git
    ```

2. Enter the dul-exhibits directory and run bundler to install dependencies.

    ```
    $ cd dul-exhibits
    $ bundle install
    ```

3. Start the Middleman server.

    ```
    $ bundle exec middleman server
    ```

4. Open a browser to [http://localhost:4567/](http://localhost:4567/).


[Documentation about Middleman](https://middlemanapp.com/basics/directory-structure/).


Deploying to Heroku (Staging)
====================

Once you've been added as a collaborator on the App (ask Cory) you should be able to deploy the website to Heroku.

1. You might need to install Heroku on your workstation. On a Mac, Homebrew is a good option.

    ```
    $ brew update
    $ brew install heroku
    ```

2. You should then be able to deploy the application using the following command. You might be prompted for your heroku credentials.

    ```
    $ git push heroku master
    ```

3. View the application as deployed to Heroku by running the following command.

    ```
    $ heroku open
    ```
    