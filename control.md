#Control Structures
####if, elsif, else
```ruby
#If
if (this == true)
  doThis
end

#Else and Elsif (Note the lack of second "e")
if (this == true)
  doThis
elsif (thisOne == true)
  doThisOne
else #takes no arguement
  doThat
end

#Ternary Operator (Single line "if" statement)
condition ? ifTrue : else
```
####case
```ruby
case arguement
  when arguement1
    doThis
  when arguement2
    doThat
  else
    doStuff
  end
```
###unless
```ruby
#Do this if a condition returns false
doThis unless thisIsFalse
```
