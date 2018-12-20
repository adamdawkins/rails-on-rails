# Sensible Rails defaults
The gems I add to every app.

# Getting Started
`git clone https://github.com/adamdawkins/rails-on-rails app_name`

Edit the database names in `/config/database.yml`
Edit the app name in `/config/application.rb`

# Extra install steps for gems

## Testing

### Cucumber
```
rails g cucumber:install
```

### Rspec
```
rails g rspec:install
```


## Functionality

### Devise
```
rails g devise:install
```

### Simple form
Include optional `--bootstrap` flag to use Bootstrap HTML structure.

```
rails g simple_form:install --bootstrap
```
