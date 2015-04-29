---
tags: kids, variables, strings
languages: ruby
level: 1
type: lab
---
##Mini-Lab: Variables Practice

###What is a Variable?
We use variables in programming to store pieces of data. Variables can store any type of data (strings, integers, floats, etc). When we name a variable, we use all lowercase letters. For example:
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
Ruby gives us an error! `undefined method 'best'`. Ruby doesn't know what `best` is because of the space between the words `best` and `friend`. Ruby doesn't recognize `best` as a key word (like puts) or as a data type, so it throws an error. It's just like when we're creating directories or files in the terminal, the space confuses the computer. Instead, replace spaces with underscores:
```ruby
best_friend = "Steph"

puts best_friend
```
###Let's practice!
What will be printed to the screen after running each of these? Talk to a partner and decide on an answer before running your code from a Ruby file that you create called `variables_practice.rb`.
???
# Variables Practice

?: What is the outcome of running the code below?
```ruby
a = 25
b = 36

puts a * b
```
[-]

?: What is the outcome of running the code below? 
```
dog = "Ralph"
cat = "Whiskers"

puts dog + cat
```
[-]

?: What is the outcome of running the code below?
```
band = "The Beatles"

puts "My favorite band is " + band 
```
[-]

?: What is the outcome of running the code below?
```
first = "BARACK"
last = "OBAMA"
age = 53

puts "The president of the US is " + first.capitalize + last.capitalize + "and he is " + age.to_s + "years old."
```
[-]

?: What is the outcome of running the code below?
```
artist_first = "NiCKi"
artist_last = "MiNaj"

puts "When I listen to" + artist_first.upcase + " " + artist_last.downcase + "I feel like my brain is melting."
```
[-]

?: What is the outcome of running the code below?
```
name = "Bill"
age = 16
location = "New York"

puts "Hi. I'm " + name.upcase + ". I'm from " + location.swapcase + "and in ten years I'm going to be " + (age+10).to_s
```
[-]

?: What would be the difference between the product and the sum?
Set `x` equal to 34679, `y` equal to 566 and `z`equal to 47. Output the product of these three numbers. Then output the sum of the three numbers. Assign each of these to a new variable and then find the difference between the product and the sum.
[-]

???
