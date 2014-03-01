# Random gif hook for [Taut](https://github.com/philtr/taut)

Graps a random gif from the [Giphy API](https://github.com/giphy/GiphyAPI)

## Usage

Put this in your Gemfile:

```ruby
gem "taut", github: "philtr/taut"
gem "taut-gifme", github: "philtr/taut-gifme"
```

It sets up a single route, `GET /gif`. When you pass it the params for a Slack slash command, it
will find a random gif from the Giphy API and post it in Slack.

## Configuration

Set the following environment variables

```
GIPHY_API_KEY=dc6zaTOxFJmzC
```
