# Dijit with Ruby on Rails

If you want to use Dijit (a Dojo Toolkit component) with Ruby on Rails, this gem is certainly the answer to your problem. There is no real implementation of Dojo and its components for Rails so this gem should make you smile. Please also see [dojo-rails](https://github.com/robin850/dojo-rails) and [dojox-rails](https://github.com/robin850/dojox-rails).

## Setup

Just open your application's `Gemfile` and edit it adding the gem:

```ruby
gem 'dojo-rails'
gem 'dijit-rails'
```

Just run the `bundle` comand yo install it. Then in your javascript/Coffeescript file, you can add Dijit packages to your require package list just like that:

```coffeescript
require(["dijit/Editor"], (editor) ->
  # ... your code
)
```
## Contributing

### Code

If you found a bug or just want to improve the project at some level, you should just:

* Fork the project
* Clone the repository on your local machine
* Create a new branch with `git checkout -b new_feature`
* Make changes and commit them
* Then `git push origin master`
* And finally open a new pull request on this repo

### Issues and bugs

For issues and bugs, please open a [new ticket](https://github.com/robin850/dijit-rails/issues/new) to the issue tracker. Thanks for your help!

## License

This project is realeased under the MIT license. Please see the `LICENSE` file for more information.