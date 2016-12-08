# Ruby Diagnostic

## Instructions

1. Fork this repo
2. Clone your fork
3. Fill in your answers by writing in the appropriate area.
4. Add/Commit/Push your changes to Github.
5. Open a pull request.

**Note**: Only place your answer between backticks. Don't modify the backticks,
or the language specified after them.

### Question 1
What command you would use to run a script at `example.rb`?

 ```text
 ruby example.rb
 ```

### Question 2
What is the alternative command to `irb` you would use to run and debug Ruby in the REPL?

 ```text
 Pry
 ```

### Question 3
How would you assign a `star wars` variable with a value of `Rogue One: A Star Wars Story`?

 ```ruby
star_wars = "Rogue One: A Star Wars Story" or
@star_wars = "Rogue One: A Star Wars Story" if you wanted an instance variable
 ```

### Question 4
Use string interpolation to tell the world the below character `is really a Sith Lord`.
```ruby
character = "Jar Jar Binks"
```

Write your code below:

```ruby
is_sith = "is really a Sith Lord"
character = "Jar Jar Binks #{is_sith}"
```

###  Question 5
#### Part 1:
What is the type of object in Ruby for decimal numbers?

 ```text
1.3.class => Float
 ```
#### Part 2:
What is the type of object in Ruby for integer numbers?

 ```text
 1.class => Fixnum
 ```

###  Question 6
Write an example of a decimal and an integer in Ruby. Replace the array values with your examples.

```ruby
numbers = [1.3, 5]
```

### Question 7
What are the values that evaluate to "falsy" in Ruby?

 ```text
nil, false
 ```

###  Question 8
Examine the following code.

 ```ruby
batman = "Bruce Wayne"

if batman
  "The Dark Knight"
else
  "Just your average billionaire"
end
```
What will be the return value? Why?

 ```text
 "The Dark Knight"
 ```
###  Question 9
What keyword would you use for "else if" clauses in Ruby?

 ```text
 elsif
 ```

###  Question 10
Does Ruby require an explicit return from methods? Explain.

 ```text
 Nope, Ruby is one of the cutesy languages that makes life easier for the programmer and has an implicit return, wherein the last line type is a function is returned. This is of course of the word return is NOT present
 ```

###  Question 11
 Instantiate a `person` hash with `age` and `first_name` as symbols and a number age and a first name as their respective values.
Use shorthand to make this on one line.

 ```ruby
 person ={age: 27,first_name: "Ash"}
 ```

### Question 12
#### Part 1:
How would you remove the last two elements from the below array?

 ```ruby
arr = [12, 34, 56, 67]
 ```

Write your code below:

```ruby
arr.pop()
arr.pop()e
```

#### Part 2:
Taking the result from the part 1, what are the `arr` values if:
```ruby
arr[arr.length + 2] = 99
```

Write your answer below:

```text
arr = [12, 34, nil, nil, 99]
```

#### Part 3:
Using `.each` and `puts`, produce the output of the array values:

 ```ruby
arr.each do |arrItems|
  puts arrItems
end
 ```
