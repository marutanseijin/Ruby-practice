

[Rubyコーヂング規約](http://shugo.net/ruby-codeconv/codeconv.html)


- 一行の桁数は最大80
- アクセサ（attr_accessor, attr_reader, attr_writer）

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

print "you can ommit paren when calling print, puts and p"

```