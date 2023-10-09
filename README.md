# Writing Good Documentation

## Step 1 - Using Codeblocks.

Codeblocks in markdown make it *very easy* for tech people to **copy, paste, share** code.
A good __Cloud Engineer__ uses Codeblocks whenever possible.

Because it allows others to copy and paste their code to replicate or research issues.

- In order to create codeblocks in markdown you need to create three backticks (`)
- Not to be confused with quotation (') 

```
# Python program to check if the input number is odd or even.
# A number is even if division by 2 gives a remainder of 0.
# If the remainder is 1, it is an odd number.

num = int(input("Enter a number: "))
if (num % 2) == 0:
   print("{0} is Even".format(num))
else:
   print("{0} is Odd".format(num))
```

 - When you can you should attempt to apply syntax highlighting to your codeblocks

```python
# Python program to check if the input number is odd or even.
# A number is even if division by 2 gives a remainder of 0.
# If the remainder is 1, it is an odd number.

num = int(input("Enter a number: "))
if (num % 2) == 0:
   print("{0} is Even".format(num))
else:
   print("{0} is Odd".format(num))
```
Oh! Here's a cat!

![cat](https://github.com/xhelma/github-docs-example/assets/97184575/6c1d32af-cfe6-4c83-8137-19b711ccb4e7)

<img width="100px" src="https://github.com/xhelma/github-docs-example/assets/97184575/6c1d32af-cfe6-4c83-8137-19b711ccb4e7" />

Good Cloud Engineers use Codeblocks for both code and errors that appear in the console.

```bash
Traceback (most recent call last):
  File "<stdin>", line 4, in <module>
RuntimeError: Failed to open database
```
> Here is an example of using Codeblocks for an error that appears in bash

## Step 3 - Use Github Flavored Task Lists

Github extends markdown to have a list where you can check off items.[<sup>[1]</sup>](#references)

- [x] Finish step 1
- [ ] Finish step 2
- [ ] Finish step 3

## Step 4 - Use emojis (optional)

Github Flavored Markdown (GFM) supports emoji shortcodes
Here are some examples:

| Name | Shortcode | Emoji |
| ---  |     ---   | --- |
|Cloud  | `:cloud:`  | :cloud: |
|Cloud with lightning  | `:cloud_with_lightning:`  | 🌩️ |

## Step 5 - how to create a table

You can use the following mardown format to create tables: 

```md
| Name | Shortcode | Emoji |
| ---  |     ---   | --- |
|Cloud  | `:cloud:`  | :cloud: |
|Cloud with lightning  | `:cloud_with_lightning:`  | 🌩️ |
```
Github extends the functionality of markdown tables to provide more alignement and table cell formatting options.[<sup>[2]</sup>](#references)

## References

- [Basic writing and formatting syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- [GitHub Flavored Markdown Spec](https://github.github.com/gfm/) 
- [Task list items (extension)](https://github.github.com/gfm/#task-list-items-extension-) <sup>[1]</sup>
- [Emoji Sheet Cheat](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md)
- [GFM - Tables](https://github.github.com/gfm/#tables-extension-) <sup>[2]</sup>
