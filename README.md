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
star_wars = "Rogue One: A Star Wars Story"
 ```

### Question 4
Use string interpolation to tell the world the below character `is really a Sith Lord`.
```ruby
character = "Jar Jar Binks"
```

Write your code below:

```ruby
puts "#{character} is really a Sith Lord"
```

###  Question 5
#### Part 1:
What is the type of object in Ruby for decimal numbers?

 ```text
 float
 ```
#### Part 2:
What is the type of object in Ruby for integer numbers?

 ```text
integer
 ```

###  Question 6
Write an example of a decimal and an integer in Ruby. Replace the array values with your examples.

```ruby
numbers = [5.0, 5]
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
 "The Dark Knight", I tried it
 ```
###  Question 9
What keyword would you use for "else if" clauses in Ruby?

 ```text
 elsif
 ```

###  Question 10
Does Ruby require an explicit return from methods? Explain.

 ```text
 no, implicit (last line) works too
 ```

###  Question 11
 Instantiate a `person` hash with `age` and `first_name` as symbols and a number age and a first name as their respective values.
Use shorthand to make this on one line.

 ```ruby
 person = {'age' => 36, 'first_name' => 'Ara'}
 ```

### Question 12
#### Part 1:
How would you remove the last two elements from the below array?

 ```ruby
arr = [12, 34, 56, 67]
 ```

Write your code below:

```ruby
arr.pop(2)
```

#### Part 2:
Taking the result from the part 1, what are the `arr` values if:
```ruby
arr[arr.length + 2] = 99
```

Write your answer below:

```text
arr = [12,34,56,67,99]  is that right????????
```

#### Part 3:
Using `.each` and `puts`, produce the output of the array values:

 ```ruby
arr.each do |i|
  puts arr[i]
end
Is this right????????????
 ```
