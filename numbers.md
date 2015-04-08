#Numbers
####Different Types
```ruby
#Fixnum (Whole numbers)
5

#Bignum (Large Whole number)
100000000000000000000000000000000000

#Floats (Decimals)
3.14

#Rational (Fractions)
1/2
```
####Operators
````ruby
#Addition
5 + 5

#Subtraction
10 - 3

#Multiplication
4 * 8

#Division
3 / 4

#Modulus
5 % 2

#Exponents
2 ** 2

#Range Operators
1..10 #Range of 1 - 10 (Inclusive)
1...10 #Range of 1 - 10 (Not including 10)
````
####Assignment Operators
```ruby
#Calculates operation, then reassigns the result to the variable
+=
-=
*=
/=
%=
**=
```
####Order of operations
```ruby
#PEMDAS
()
**
*/%
+-
```
####Numbers/Strings conversion
```ruby
#Convert number to string
3.to_s

#Concatinate number and string
5.to_s + " cats"
"#{5} cats" #Also works, and is technically faster. Also avoids errors with floats

#String to number
"1".to_i #Convert to integer
"3".to_i(base) #Convert to integer of base (2 - 36)
"3.14".to_f #Convert to float
"2".to_r #Convert to rational and simplify (2/1)
"5/10".to_r ==  1/2

  #Possible issues
  "973h2".to_i  == 973 #Ignores everything after it finds a non-number
  "Hi52".to_i == 0.0 #Letters in front
```
