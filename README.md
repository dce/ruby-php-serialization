# Ruby::Php::Serialization

TODO: Write a gem description

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'php-serialization'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install php-serialization

## Usage

```ruby
require 'php_serialization'

# Convert a serialized string to a Ruby data structure
PhpSerialization.load(serialied_string)

# Convert a Ruby data structure to a serialized string
PhpSerialization.dump(ruby_object)
```

## Contributing

1. Fork it ( https://github.com/[my-github-username]/ruby-php-serialization/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
