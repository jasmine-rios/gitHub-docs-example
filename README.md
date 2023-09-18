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

- Make note of where the backtick character is located.
- It should appear above the tab key, 
- but it may be based on your keyboard layout.

Good Cloud Engineers use Codeblocks for both code and errors that appear in the console.

```bash
ZeroDivisionError (divided by 0)
```
> Here is an example of using a Codeblock for an error that appears in bash.

## Step 2 - How to take screenshots

A screenshot is when you capture a part of your screen from your laptop, desktop, or phone.

This is not to be confused with taking a photo with your phone.

**DON'T DO THIS**

![Example of Phone Picture](Example of Phone Picture.jpg)

This is what a screenshot from your computer should look like

**DO THIS INSTEAD**

![Screenshot example](Example of Screenshot.png)

## Step 3 - Use Github Flavored Markdown Task lists

Github extends Markdown to have a list where you can check off items. [<sub>[1]<sub/>](#External-References)

- [x] Finish Step 1
- [ ] Finish Step 2
- [ ] Finish Step 3

## Step 4 - Use Emojis (Optional)

GitHub Flavored Markdown (GFM) supports emoji shortcodes.
Here are some examples:

| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` | :cloud: |
| Cloud with lightning | `:cloud_with_lightning:` | :cloud_with_lightning: |

:cloud:
[<sub>[2]<sub/>](#External-References)

## Step 5 - How to Create a Table

You can use the following markdown format to create tables:

```markdown
| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` | :cloud: |
| Cloud with lightning | `:cloud_with_lightning:` | :cloud_with_lightning: |
```
Github extends the functionality of Markdown tables to provide more alignment and table cell formatting options. [<sub>[3]<sub/>](#external-references)

- Make note of where the pipe character is located.
- It should appear above the enter key, 
- but it may be based on your keyboard layout.

## External References

- [Github Flavored Markdown Spec](https://github.github.com/gfm/)
- [Basic Writing and Format Syntax (Github Flavored Markdown)](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) 
- [GFM - Task Lists](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists)<sub>[1]<sub/>
- [GFM - Emoji CheatSheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md#emoji-cheat-sheet)<sub>[2]<sub/>
- [GFM - Tables with Extensions](https://github.github.com/gfm/#tables-extension-)<sub>[3]<sub/>
