What is Michael Feathers definition of "legacy code"?

```
Legacy Code is code that is already in use and you want to ether 
add new features or make the current code better
```



What is the first thing you should do when refactoring legacy code?
```Clean up the code to make it easier to read```

How would you refactor this code?
1.

```lang-ruby
total = total + 1
```

```lang-ruby
total += 1
```

2.

```lang-ruby
  @items = [{name: "Item Name"}]
    for i in 0..(@items.size-1)
      @items[i].name
    end
  ```

```lang-ruby
  @items = [name: "Item Name"]
    @items.each do |i|
      @items[i][:name]
    end
  ```


What do you call the initial tests created by Randy? ```B```

a. Characterization Tests

b. Unit tests

c. Feature tests

d. Integration tests

What does Flog score represent? ```D```

a. Code quality

b. Code complexity

c. none of the above

d. both A, B

<b>True</b> / False - You should always make small changes and while always checking your tests after each change.

<b>True</b> / False - A high flog score is good
