[![Gem Version](https://badge.fury.io/rb/morph-cli.png)](http://badge.fury.io/rb/morph-cli)

# Morph Commandline

Runs Morph scrapers from the commandline.

Actually it will run them on Morph server identically to the real thing. That means not installing a bucket load of libraries
and bits and bobs that are already installed with the Morph scraper environments.

To run a scraper in your local directory

    morph

Yup, that's it.

It runs the code that's there right now. It doesn't need to be checked into git or anything.

## Installation

You'll need Ruby >= 1.9 and then

    gem install morph-cli

## Limitations

It doesn't currently stream the console output from the Morph server so you have to wait until the scraper has finished running before you see the output. I want to add streaming as soon as possible because it will make this a whole lot more responsive and usable.

It uploads your code everytime. So if it's big it might take a little while. Scrapers are not usually so I'm hoping this won't really be an issue

It doesn't yet return you the resulting sqlite database.

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
