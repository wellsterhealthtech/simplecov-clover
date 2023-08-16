# Simplecov::Clover

TODO: Write a gem description

## Installation

Add this line to your application's Gemfile:

```ruby
group :test do
    gem 'simplecov-clover', '~> 0.1', require: false, git: 'https://github.com/wellsterhealthtech/simplecov-clover'
end
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install simplecov-clover

## Usage

Include the formatter in your `spec_helper.rb` as:
```ruby
require 'simplecov-clover'
SimpleCov.formatter = SimpleCov::Formatter::CloverFormatter
```

## Contributing

1. Fork it ( https://github.com/[my-github-username]/simplecov-atlassian-bamboo/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
