# Writing Good Documentation
This repo is for the Terraform Beginners Bootcamp

## Step 1 - Using Codeblocks.

Codeblocks in markdown make it *very easy* for tech people to **copy, paste, and share** code. A good __Cloud Engineer__ uses Codeblocks whenever possible.

Because it allows others to copy and paste their code to replicate or research issues.

- In order to create Codeblocks in markdown you need to use three backticks (`)
- Not to be confused with quotation (')
- When you can you should attempt to apply syntax highlighting to your Codeblocks
```ruby
def factorial(n)
  if n == 0
    return 1
  else
    return n * factorial(n - 1)
  end
end

puts "Enter a number to calculate its factorial:"
number = gets.chomp.to_i

if number < 0
  puts "Factorial is not defined for negative numbers."
else
  result = factorial(number)
  puts "The factorial of #{number} is #{result}."
end
```

Make note of where the backtick button is located.
It should appear above the tab key, but it may be based on your keyboard layout.

![Random Picture](https://github.com/jasmine-rios/gitHub-docs-example/assets/93607592/6988fc3b-09d7-4d3e-ab67-bb0e322d8747)

<img width="200px" src="https://github.com/jasmine-rios/gitHub-docs-example/assets/93607592/6988fc3b-09d7-4d3e-ab67-bb0e322d8747" />

```bash
ZeroDivisionError (divided by 0)
```
