# Blog App

This is a basic blog application built with Ruby on Rails. It features user authentication, article management (create, edit, delete), and comments. The app is designed as a learning project from the perspective of a Laravel developer trying out Rails.

## Features

- User registration, login, and password recovery (powered by Devise)
- Create, edit, and delete articles
- Post comments on articles
- Basic form validation within models

## Getting Started

### Prerequisites

Ensure you have Ruby and Rails installed. This app was developed with:

- Ruby 3.3.5
- Rails 7.2.1

You'll also need a SQLite3 set up.

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/thijskok/ruby-on-rails-blog.git
    ```

2. Navigate to the app directory:

    ```bash
    cd ruby-on-rails-blog
    ```

3. Install the required gems:

    ```bash
    bundle install
    ```

4. Set up the database:

    ```bash
    rails db:create
    rails db:migrate
    ```
5. Run the Rails server:

    ```bash
    rails server
    ```

The app will be available at http://localhost:3000.

### Usage

- To sign up, register via the signup form.
- Create, edit, and delete articles once logged in.
- Post comments on individual articles.

## Contributing

Feel free to fork the repository and submit pull requests for improvements or new features.

## License

This project is licensed under the MIT License.