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
pry
 ```

### Question 3
How would you assign a `star wars` variable with a value of `Rogue One: A Star Wars Story`?

 ```ruby
star wars = "Rogue One: A Star Wars Story"
 ```

### Question 4
Use string interpolation to tell the world the below character `is really a Sith Lord`.
```ruby
character = "Jar Jar Binks"
```

Write your code below:

```ruby
"#{character} is really a Sith Lord"
```

###  Question 5
#### Part 1:
What is the type of object in Ruby for decimal numbers?

 ```text
Float
 ```
#### Part 2:
What is the type of object in Ruby for integer numbers?

 ```text
Fixnum
 ```

###  Question 6
Write an example of a decimal and an integer in Ruby. Replace the array values with your examples.

```ruby
numbers = [1.4, 3]
```

### Question 7
What are the values that evaluate to "falsy" in Ruby?

 ```text
 False and nil
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
"The Dark Knight" --> batman evaluates to true because it has a value.
 ```
###  Question 9
What keyword would you use for "else if" clauses in Ruby?

 ```text
elsif
 ```

###  Question 10
Does Ruby require an explicit return from methods? Explain.

 ```text
 Ruby DOESNT require an explicit return because it implicitly returns the last
 in the method. "return" is used so that programmers that arent familiar with
 the language will understand what the method is exactly returning.
 ```

###  Question 11
 Instantiate a `person` hash with `age` and `first_name` as symbols and a number age and a first name as their respective values.
Use shorthand to make this on one line.

 ```ruby
 person = {name: 27, first_name: "Alyssa"}
 ```

### Question 12
#### Part 1:
How would you remove the last two elements from the below array?

 ```ruby
arr = [12, 34, 56, 67]
 ```

Write your code below:

```ruby
arr.slice(0,2)
```

#### Part 2:
Taking the result from the part 1, what are the `arr` values if:
```ruby
arr[arr.length + 2] = 99
```

Write your answer below:

```text
[12, 34, nil, nil, 99]
```

#### Part 3:
Using `.each` and `puts`, produce the output of the array values:

 ```ruby

arr.each do |i|
  puts i
end
 ```
