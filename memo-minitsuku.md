
# CORDING RULES #

[Rubyコーヂング規約](http://shugo.net/ruby-codeconv/codeconv.html)



## method def ##

``` ruby
def foo(x, y)
  ...
end

def foo
 ...
end
```

## Class method def ##

```Ruby
class Foo
  def self.foo
    ...
  end
end
```

## calling methods ##

```Ruby
foo(1, "abc")

# you can ommit paren when calling print, puts and p
```

## method chain ##

```Ruby
s = ary.collect { |i| i.to_s }.join(",")
```

## Return ##

```Ruby
def add(x, y)
  return x + y
end
```

## If conditional & case ##

```Ruby
if X > 0
  puts "X > 0"
else
  puts "x <= 0"
end

# you can't use else with 'unless'#

unless x
  puts "x is false"
end

puts "x is true" if x

case x
when 1
  ...
when 2
  ...
end
```

## while loop ##

```Ruby
while cond
  ...
end

# you can use 'until' instead of while !x

until cond
  ...
end
```

## naming ##

```ruby
# method
add_something

# method returns bool
visible?

# dustructive method
split
split! # distructive split

# constant
EXAMPLE_COSTANT

# vars
tmp
local_variable

#file name
foo.rb
foo-bar.rb
```
