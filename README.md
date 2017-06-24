# Twilreapi::ActiveCallRouter::PinCambodia

[![Build Status](https://travis-ci.org/dwilkie/twilreapi-active_call_router-unicef_io.svg?branch=master)](https://travis-ci.org/dwilkie/twilreapi-active_call_router-unicef_io)

This gem contains call routing logic for [somleng.unicef.io](https://somleng.unicef.io) for [Twilreapi.](https://github.com/dwilkie/twilreapi)

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'twilreapi-active_call_router-unicef_io', :github => "dwilkie/twilreapi-active_call_router-unicef_io"
```

And then execute:

    $ bundle

## Configuration

To configure [Twilreapi](https://github.com/dwilkie/twilreapi) to use `Twilreapi::ActiveBiller::UnicefIO::CallRouter`, set the environment variable `ACTIVE_CALL_ROUTER_CLASS_NAME=Twilreapi::ActiveCallRouter::UnicefIO::CallRouter`

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake spec` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/dwilkie/twilreapi-active_call_router-unicef_io.

## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
