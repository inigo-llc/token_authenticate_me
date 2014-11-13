# TokenAuthenticateMe
This gem adds simple token authentication to users.

## Getting started

Add the gem to your Gemfile:
`gem token_authenticate_me`

Run `bundle install` to install it.

To add or create a user with token authentication run:
`rails generate token_authenticate_me <model>`

Replace `<model>` with the class name used for users. This will crate the necessary migration files, and optionally create the model file if it does not exist.

