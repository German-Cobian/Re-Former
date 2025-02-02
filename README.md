# Form-Creator

A Rails app which allows the user to input and save his/her username, email address and password.

![Form](/app/assets/images/Form.png?raw=true "Form")

This project was an exercise in the building of forms, starting with HTML then using the helper methods that Rails provides (#form_tag and #form_with). The Rails way sends parameters to a controller which builds an instance of the model for the view.

## Getting Started

To get a local copy up and running follow these simple example steps:

### Prerequisites

* Ruby
* Rails
* SQLite3
* Node.js
* Yarn


### Setup and Install

* Open your terminal - Windows: `Win + R`, then type cmd | Mac: `Command + space`, then type `Terminal`
* Navigate to a directory of your choosing using the `cd` command
* Run this command in your OS terminal: `git clone git@github.com:German-Cobian/Form-Creator.git` to get a copy of the project.
* Navigate to the project's directory using the `cd` command
* Run `rails webpacker:install` to configure Webpacker for your environment
* Install dependencies by running `bundle install`
* Migrate the database to your environment by running `rails db:migrate`
* Navigate to the bin folder of the project using the `cd` command and then execute `rails server` or `rail s` to fire up the server
* Navigate to `http://localhost:3000/users/new` to see the new user form on your browser
* Once you've created a user, you can edit or update the same by navigating to `http://localhost:300/users/:id/edit` where `:id` is the actual number associated to that user
* To close the server, enter `Ctrl + C` in your terminal


### Usage

The front end ( `http://localhost:3000/users/new` ) displays a form which allows a user to input their username, email and password. The back end shows the server output and/or any errors stack trace. None of the input fields can be blank on the edit page: `http://localhost:3000/users/:id`.


## Features
* All actions start from the form at the root url `http://localhost:3000`
* Users, password and email must be created with some validations check (Name must be at least 5 characters long, password, email must be at least 7 characters and password must be at least 8 characters long)
* Each User is created and assigned an index automatically by rails
* Each users can be accessed using rails routing system. User can be added as there is no limit to that


## Authors

👤 **Promise Johnson**

* GitHub: [@promise-J](https://github.com/promise-J)
* Twitter: [@Promise94353263](https://twitter.com/Promise94353263)
* LinkedIn: [LinkedIn](https://www.linkedin.com/in/promise-chiemela)

👤 **German Cobian**

* GitHub: [@German-Cobian](https://github.com/German-Cobian)
* Twitter: [@GermanCobian1](https://twitter.com/GermanCobian1)
* LinkedIn: [@german-cobian](https://www.linkedin.com/in/german-cobian/)


## 🤝 Contributing

Contributions, issues, and feature requests are welcome!


## Show your support

Give a ⭐️ if you like this project!


## Acknowledgments

Guidelines for project supplied by [The Odin Project](https://www.theodinproject.com/lessons/ruby-on-rails-forms)


## 📝 License

This project is [MIT](https://github.com/German-Cobian/Form-Creator/blob/main/LICENSE) licensed.
