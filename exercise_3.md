# Exercise 3

Create a new file `parser.rb`. In that file create a function `parse` which takes a list as argument:

```ruby
#parser.rb
def parse(tokens)
  #...
end
```

The purpose of that function is to consume the tokens and to calculate the result of the term provided. This means for the list of tokens `["plus", "2", "3"]` it should return the value `5`.

For this exercise, you can use the following Ruby tools:

- [`if`](http://www.howtogeek.com/howto/programming/ruby/ruby-if-else-if-command-syntax/)
- [`case`](http://www.skorks.com/2009/08/how-a-ruby-case-statement-works-and-what-you-can-do-with-it/)
- [`to_i`](http://ruby-doc.org/core-2.0.0/String.html#method-i-to_i) This converts a string into integer

If you want a function to return a value, you do it like so:

```ruby
def parse(tokens)
  #...
  result = 5
  result
end
```
