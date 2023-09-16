# Writing Good Documentation

## Step 1 - Using Codeblocks

Codeblocks makes it *very easy* to **copy, paste and share** code.

It's considered __good practice__ for __Cloud Engineers__ to use Codeblocks as it allows others to copy and paste their code
for replication or research issues.

- In order to create codeblocks in markdown you need to use 3 backticks:
**(`)**, 
- not to be confused with single quotation marks:
**(')**
  
```
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n - 1)

result = factorial(5)
print("Factorial of 5:", result)
```

- When applicable, apply syntax highlighting to your codeblocks

```Python
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n - 1)

result = factorial(5)
print("Factorial of 5:", result)
```

![byakuya_kuchiki_final_bankai](https://github.com/AldoA7/github-doc-example/assets/130854391/e0160ce0-d8c6-4b20-ac5b-673c08d217e1)

- Good Cloud Engineers use __codeblock__ for both __code and errors__ that appear in the console

> Below is an example of a codeblock of an error that appears in bash
```bash
Traceback (most recent call last):
  File "example.py", line 3, in <module>
    result = 10 / 0
ZeroDivisionError: division by zero
```
## Step 2 - Use GitHub Flavoured Markdown Task Lists  
Github extends Markdown to have a list where you can check off items. <sup>[1]</sup>
- [ ] Finish Step 1
- [ ] Finish Step 2
- [ ] Finish Step 3

## Step 3 - Use  Emojis(Optional)

Github Flavoured Markdown (GFM) supports emoji shortcodes

Here are some examples:
|Name|Shortcode|Emoji|
|---|---|---|
|cloud|`:cloud:`|:cloud:|
|cloud|`:`

## References
- [GitHub Flavored Markdown Spec](https://github.github.com/gfm/)
- [Create sophisticated formatting for your prose and code on GitHub with simple syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)<sup>[1]</sup>
- [emoji-cheat-sheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md)
