# Github Writing Good Documentation By *NegroDrama*

## Step 1 - Using Codeblocks.

Code blocks is markdown make it *very easy* for tech people to **copy, paste, share** code.
A good _Cloud Engineer_ uses Codeblocks whenever possible.

Because it allows others to copy and paste their code to replicate or research issues.


- In order to create codeblocks in markdown you need to use three backticks (')
- Not to be confused with qoutation (')

```
#def factorial(n)
  if n <= 1
    return 1
  else
    return n * factorial(n - 1)
  end
end

puts "Enter a number: "
number = gets.chomp.to_i

result = factorial(number)
puts "The factorial of #{number} is #{result}"
```

- When you can you should attempt to apply syntax highlighting to your codeblocks

```ruby
#def factorial(n)
  if n <= 1
    return 1
  else
    return n * factorial(n - 1)
  end
end

puts "Enter a number: "
number = gets.chomp.to_i

result = factorial(number)
puts "The factorial of #{number} is #{result}"
  end
end
```

- Make note of where the backtick button is located.
- It should appear above the tab key,
- but it may vary based on your keyboard layout.



Good Cloud Engineers use codeblocks for both Code and Errors that appear in the console.



```bash
Traceback (most recent call last):
  example.rb:2:in `<main>': undefined local variable or method `undefined_variable' for main:Object (NameError)
```

> Here is an example of using a codeblock for an error that appears in bash.

## Step 3 - Use Github Flavoured Markdown Task Lists

Github extends Markdown to have a list where you can check off items.

- [x] Finish Step 1
- [x] Finish Step 2
- [ ] Finish Step 3
- [ ] Finish Step 4


## References 

- [GitHub Flavored Markdown Spec](https://github.github.com/gfm/) 
- [Basic writing and formatting syntax (Github Flavored Markdown)](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- [GFM - Task Lists](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists)<sup>[1]</sup>
