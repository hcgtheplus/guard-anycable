# Guard::Anycable

Guard::Anycable automatically starts/stops/restarts anycable gRPC server

referencing from [Guard::Sidekiq](https://github.com/uken/guard-sidekiq)
## Installation

Please be sure to have [Guard](http://github.com/guard/guard) installed before continue.

Install the gem:

    gem install guard-anycable

Add it to your Gemfile (inside test group):

    gem 'guard-anycable'

Add guard definition to your Guardfile by running this command:

    guard init anycable

## Usage

TODO: Write usage instructions here

## Development

After checking out the repo, run `bin/setup` to install dependencies. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and the created tag, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/[USERNAME]/guard-anycable.
