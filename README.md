# README

This is part of the Forms Project in The Odin Project’s Ruby on Rails Curriculum. 
Find it at http://www.theodinproject.com


# Re-former

This is a simple Ruby on Rails application called "Re-former" that allows users to create and edit user accounts.

## Features

- Users can create new accounts by providing a username, email, and password.
- Users can edit their account details, including username, email, and password.
- Form validations are implemented to ensure that usernames and emails are unique, and passwords are at least 6 characters long.
- Error messages are displayed when form submissions fail validation.

## Setup

To run this project locally, make sure you have the following prerequisites installed:

- Ruby (version 3.3.0)
- Rails (version 7.1.3)
- SQLite or other supported database system

Follow these steps to set up and run the project:

## 1. Clone this repository to your local machine:
```
git clone https://github.com/Jaaystones/re-former.git

```

## 2. Navigate to the project directory:
```
cd re-former
```
## 3. Install dependencies
```
bundle install
```
## 4. Set up the database:
```
rails db:migrate
```
## 5. Fire up Rails server:
```
rails server
```

## 6. Open your web browser and visit [http://localhost:3000](http://localhost:3000) to access the application.

## Usage

- To create a new user account, navigate to the "New User" page and fill out the required fields in the form.
- To edit an existing user account, navigate to the "Edit User" page and update the account details in the form.
- Error messages will be displayed if form submissions fail validation, indicating the reason for the failure.

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request.
The front end aspect need some cute CSS designs and page functionality

## License

This project is licensed under the [MIT License](LICENSE).
