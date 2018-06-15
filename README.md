# rails-react-starter-tutorial

## Installation

After cloning, `cd` into the folder and run `bundle install`. Then run `rails db:create db:migrate db:seed` to create, prepare, and seed the database (PostgreSQL).

## Running the App

You should use [forman](https://github.com/ddollar/foreman) to run this app. To run it, use this command:

```bash
foreman start -f Procfile.dev -p 3000
```

Then you should be able to access the app on localhost:3000.
