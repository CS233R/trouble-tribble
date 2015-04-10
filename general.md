#General
####Define Variables
```ruby
puts "What is your age?"
age = gets
puts "Your age is #{age}."

#Multiple/Parallel Assignment
a, b, c = 10, 20, 30 #a == 10, b == 20, c == 30

#Parallel Variable Swapping
a, b = b, c #a == b and b == c
```
####Variable Naming/Conventions
```ruby
#Variable names should be easy to understand
#Varibles cannot begin with numbers
2Bad4U #Not valid
#Symbols should not be used (except for underscores)

#Constants begin with a capital letter
  #Conventionally, they are typed in all capital letters
Avariable
A_VARIABLE
#Constants are not conpletely unchangeable in Ruby unlike other languages,
  #they can still be altered, but Ruby wil warn you.
```
####Run Ruby Program
```ruby
Name file with extension ".rb"
Navigate to/run file "ruby file.rb"
```
####Comments
```ruby
#Single-line comment

=begin
  Multi-line comment
=end
```
