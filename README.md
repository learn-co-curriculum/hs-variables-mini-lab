---
tags: kids, variables, strings
languages: ruby
---

#Mini-Lab: Variables Practice

What will the return value be after running each of these? Talk to a partner and decide on an answer before running your code from a ruby file that you create called variables_practice.rb.

####1:
```ruby
a = 25
b = 36

puts a * b
```

####2:
```
dog = "Ralph"
cat = "Whiskers"

puts dog + cat
```

####3:
```
band = "The Beatles"
puts "My favorite band is " + band 
```

####4 (fix the output so it looks right):
```
first = "BARACK"
last = "OBAMA"
age = 53

puts "The president of the US is " + first.capitalize + last.capitalize + "and he is " + age.to_s + "years old."
```

####5
```
artist_first = "NiKKi"
artist_last = "MiNaj"

puts "When I listen to" + artist_first.upcase + " " + artist_last.downcase + "I feel like my brain is melting."
```

####6
```
name = "Bill"
age = 16
location = "New York"

puts "Hi. I'm " + name.upcase + ". I'm from " + location.swapcase + "and in ten years I'm going to be " + (age+10).to_s
```

####7
Assign your first name to a variable called `first` and your last name to a variable called `last`. Assign the number of siblings you have to a variable called `siblings`. Out a string using these variables that says your full name and the number of siblings that you have in the form of a sentence.

####8
Set `x` equal to 34679, `y` equal to 566 and `z`equal to 47. Output the product of these three numbers. Then output the sum of the three numbers. Assign each of these to a new variable and then find the difference between the product and the sum.
