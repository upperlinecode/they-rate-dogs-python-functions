# They Rate Dogs

If you've spent time on Twitter, you've may have come across an account called "We Rate Dogs" that does just that: They rate dogs on a scale from 1-10.

However, the best part about it is that the author really loves dogs, and so they pretty much give every dog at least a 10 - and sometimes the dog is so cute it breaks the scale and gets an 11, a 12, or a 13.

![Picture of a double dog!](ratedog.jpg)

## The Goal

Write some functions that take in some information about a dog and return a rating for that dog.

Follow the challenges in the file named dog_rater.py. When you're ready to test it, run it using the python command in the console:

```bash
python dog_rater.py
```

Be sure to *call* your functions somewhere in the dog_rater.py program in order for them to run, and if you want to actually *see* the results, be sure to print the return values.

```python
# Non-example: call your function (but do nothing with the return):
example_function()

# Option 1: call your function and print the return:
print(example_function())

# Option 2: call your function, store the return, and print that stored value:
result = example_function()
print(result)
```

(It's okay to give really good ratings)

## BONUS: Random Numbers

You may find yourself wanting to make certain parts of the dog rater functions a little more wild and random. If so, you may want to know this cool Python function:

```python
# At the top of your program, import the function
from random import randint

# Then, use the randint function to generate random integers. 
x = randint(5, 10)
```

This code will pick a random integer between 5 (inclusive) and 10 (exclusive) and store it in the variable x, and then you can use it later.

If you DO use the randint() function, you must remember to put the line `from random import randint` at the top of your program. This tells the computer where to find the definition for the randint() function, just like how you used `import budget` or `import diet` to allow your tests to access functions defined in other files earlier today.
