# mruby-example   [![Build Status](https://travis-ci.org/your-github-username/mruby-example.svg?branch=master)](https://travis-ci.org/your-github-username/mruby-example)
Example class
## install by mrbgems
- add conf.gem line to `build_config.rb`

```ruby
MRuby::Build.new do |conf|

    # ... (snip) ...

    conf.gem :github => 'your-github-username/mruby-example'
end
```
## example
```ruby
p Example.hi
#=> "hi!!"
t = Example.new "hello"
p t.hello
#=> "hello"
p t.bye
#=> "hello bye"
```

## License
under the MIT License:
- see LICENSE file
