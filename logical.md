#Logical Operators
```ruby
#Not (Highest precedence)
not ! #Returns the oposite of what the condition would normally return

#And
and && #Returns true if both conditions are true

#Or (Lowest precedence)
or || #Returns true if either condition is true
```
####Using multiple in a single argument
```ruby
if ((this && that) || (those && these)) #Its a good idea to use parenthesis to make it clear
#if (this AND that == true) OR (those AND these == true) returns true if either AND is true
```
