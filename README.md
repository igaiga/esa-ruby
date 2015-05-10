# Esa

( ⁰⊖⁰): Write a gem description

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'esa'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install esa

## Usage

```ruby
client = Esa::Client.new(access_token: "<access_token>", api_endpoint: "http://api.esa.dev", current_team: 'foo')
client.team
client.team('bar')
client.teams
client.posts
client.post(1)
client.update_post(1, name: 'baz')
client.current_team = 'foobar'

client.send_post
client.send_get
client.send_patch
client.send_delete
client.send_put
client.send_request
```

## Contributing

1. Fork it ( https://github.com/esaio/esa-ruby/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
