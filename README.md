## Usage

0. Clone
```
    git clone https://github.com/rsfxiii/shopify-rails-sql-nginx-docker.git
```

1. Installation
```
    bundle install
    npm install
```
2. Startup
```
    bundle exec rake db:create db:migrate # First time only
    bundle exec rails server
```

---

# Database How-To

**Default Settings**:
* Port: 5432 (Container & Host)
* Config: `config/database.yaml`

## DB Management

To create a database:
`bundle exec rake db:create`

## Migrations

**To run migrations**, execute the following:
`bundle exec rake db:migrate`



