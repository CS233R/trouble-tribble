#Strings
####Quotes
```ruby
#Strings can be surrounded by either single or double quotes
"Hello" #Double quotes will interpret the characters as intended
'Hello' #Single quotes will use the characters as they are literally writen

#Quotes within Quotes
"He said 'Hi!'" #Using both quote types
'He said "Hi!"'
"He said \"Hi!\"" #Using escapes
'He said \'Hi!\''
"That's Lizzy's." #Apostrophes
'That\s Lizzy\'s.'
```
####Variables/Expressions in Strings
```ruby
"#{variable}" #Place the variable in the quotes like this
"Here is the average: #{average}."
```
####Character Encoding
```ruby
$KCODE = "arguement" #Add to the beginning of the code page to change character encoding. Default is ASCII
#arguements:
  #a or n is default
  #e is EUC
  #u is UTF-8
$KCODE = "u" #UTF-8
```
