# Unidom Payment

[![License](https://img.shields.io/badge/license-MIT-green.svg)](http://opensource.org/licenses/MIT)

Unidom (UNIfied Domain Object Model) is a series of domain model engines. The Payment domain model engine includes Payment and its relative models.
Unidom (统一领域对象模型)是一系列的领域模型引擎。支付领域模型引擎包括支付及其相关的模型。

## Usage in Gemfile:
```ruby
gem 'unidom-payment'
```

## Run the Database Migration:
```shell
rake db:migrate
```

## Call the Model:
```ruby
Unidom::Payment::Payment.valid_at.alive.first
```
