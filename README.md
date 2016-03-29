# Unidom Payment 支付领域模型引擎

[![License](https://img.shields.io/badge/license-MIT-green.svg)](http://opensource.org/licenses/MIT)

Unidom (UNIfied Domain Object Model) is a series of domain model engines. The Payment domain model engine includes Payment and its relative models.
Unidom (统一领域对象模型)是一系列的领域模型引擎。支付领域模型引擎包括支付及其相关的模型。

## Recent Update
Check out the [Road Map](ROADMAP.md) to find out what's the next.
Check out the [Change Log](CHANGELOG.md) to find out what's new.

## Usage in Gemfile
```ruby
gem 'unidom-payment'
```

## Run the Database Migration
```shell
rake db:migrate
```

## Call the Model
```ruby
Unidom::Payment::Payment.valid_at.alive.first
```
