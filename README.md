# Twofishes

A client/wrapper for foursquare's sparse geocoding / reverse geocoding server Twofishes (https://github.com/foursquare/twofishes).

## Installation

Add this line to your application's Gemfile:

    gem 'twofishes'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install twofishes

## Configuration

    Twofishes.configure do |config|
      config.base_url = 'http://mytwofishes.com:8081'
    end

## Usage

TODO: Write usage instructions here

## Contributing

1. Fork it ( http://github.com/masone/twofishes/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Run tests (`rake test`)
5. Push to the branch (`git push origin my-new-feature`)
6. Create new Pull Request