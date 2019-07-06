# My Four Favorite Ruby Methods

### `.times`

An easy loop that outputs x the number of times specified
```ruby
10.times { puts "Hello, World" }
```

### `.chomp`

Outputs a new string with the white space or specified characters removed
```ruby

"Garett".chomp("ett") #=> "Gar"
```

### `.reverse!`

Reverses the input array

```ruby

Array1 = ["cats", "dogs", "penguins", "cows"]

A=Array1.reverse!

puts "#{Array1}"

Output #=> ["cows", "penguins", "dogs", "cats"]
```

### `.pop`

Removes elements from the end of an array and returns end of array
```ruby

Array1 = ["cats", "dogs", "penguins", "cows"]

A = Array1.pop

puts "#{A}"

Output #=> cows
```
