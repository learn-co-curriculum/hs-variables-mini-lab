---
tags: kids, variables, strings
languages: ruby
level: 1
type: lab
---

##Mini-Lab: Variables Practice


###What is a Variable?
We use variables in programming to store pieces of data. Variables can store any type of data (strings, integers, floats, etc). A variable names contain all lowercase letters. For example:

```ruby
dog = "Fido"
```

In this example, all we've done is defined a variable named `dog` and set it equal to the string `Fido`. Now, any time we tell our program to `puts dog`, it will print out `Fido`.

```ruby
puts dog
puts dog
puts dog
```

In this example, we should see `Fido` printed out three times.

What would happen if we did the following:

```ruby
name = "Fido"
name = "Bessie"

puts name
```

On the first line, we assigned the variable `name` to store `Fido`. On the next line, we reassigned the value of the variable `name` to store `Bessie`. Each variable can only store one value, so all we did was overwrite the value of the `name` variable. When we `puts name` on the last line, we will see `Bessie` printed out.

What if we want to have more than one word in our variable? Like:

```ruby
best friend = "Steph"

puts best friend
```

Ruby gives us an error! `Undefined method Best`. Ruby doesn't know what `best` is because of the space between the words `best` and `friend`. It's just like when we're creating directories or files in terminal, the spaces signify a different variable. Instead, replace spaces with underscores:

```ruby
best_friend = "Steph"

puts best_friend
```

###Let's practice!

 
What will be printed to the screen after running each of these? Talk to a partner and decide on an answer before running your code from a ruby file that you create called variables_practice.rb.

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
Assign your first name to a variable called `first` and your last name to a variable called `last`. Assign the number of siblings you have to a variable called `siblings`. Output a string using these variables that says your full name and the number of siblings that you have in the form of a sentence.

####8
Set `x` equal to 34679, `y` equal to 566 and `z`equal to 47. Output the product of these three numbers. Then output the sum of the three numbers. Assign each of these to a new variable and then find the difference between the product and the sum.
