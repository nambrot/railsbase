# Base Project for bootstrapping

### Features

- User System with Devise
- Basic Style with Foundation
- Responsive with OffCanvasMenu
- Mobile View Paths

### Init

````
bundle
rails g foundation:install
rails g devise:install
rails g devise User
rake db:migrate
````

### Caveats

- When cloning, reset the Rails secret in config/initializers/secret_token.rb

````
rake secret
````