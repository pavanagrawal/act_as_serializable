# ActAsSerializable

TODO: Write a gem description

## Installation

Add this line to your application's Gemfile:

    gem 'act_as_serializable'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install act_as_serializable

## Usage

in model, for any text column for which you want it to act as array column

mention:

act_as_serializable [:col1]

for mutiple columns:

act_as_serializable [:col1, :col2]


## Contributing

1. Fork it ( https://github.com/pavanagrawal/act_as_serializable/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
act_as_serializable
