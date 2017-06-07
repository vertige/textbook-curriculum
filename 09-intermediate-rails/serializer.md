# Customizing JSON output with Serializer

## Learning Goals
-
-
-
-
-

## Why Serialize API Data

You can further customize how data is formatted in your JSON


## Installation

[Serializer Gem Documentation](https://github.com/rails-api/active_model_serializers/tree/0-10-stable)
Add gem


Add this line to your application's Gemfile:

```
gem 'active_model_serializers', '~> 0.10.0'
```

And then execute:

```
$ bundle
```


## Serialize an API's Data

Create a serialize file for the Pet model

In terminal, run the command:
```
rails generate serializer pet
```

Create a serializer file for every resource, or model, where you would like to customize the JSON output.

The name needs to be the same as the model.


## What Have We Accomplished?
-
-
-


## Resources
- [ActiveModel Serializers](http://railscasts.com/episodes/409-active-model-serializers)
- [blog post by thoughtbot about serialization](http://robots.thoughtbot.com/better-serialization-less-as-json)
