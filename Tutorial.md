

# Tutee


* Some limited prior online courses
    * But limited motived prior experience

* Goal: Professional Development...
    * Use python for data analysis...
    * Current job: consultant 
* Prior Experience: 
    * Consulting on strategy, technical org.
    * University: Astrophysics, MA Management 
    * Very basic things in jupyter 

* Lessons Front-Loading
    * 75min: 15-20 sessions


## Outline

* Python Programming 
    * Fundamentals: High Level Overview Below
        * Python Setup & Background
        * Data Types, Objects, Variables, Values, Operators
        * Lists, Strings, Dictionaries
        * Iteration, Looping
        * Functions
    * Projects
        * Data structures in detail
            * dictionaries, lists
        * Regex, Text Processing
        * Image Processing
        * Object-Objected Programming: class
        * Libraries
            * in-built python libraries
        * Web Development
* Data Analysis in Python
    * Numerical Programming
    * Statistics
    * Data Exploration
    * Visualization


## Lesson 1: What is Python?

* Anaconda.com
    * https://www.youtube.com/watch?v=UTqOXwAi1pE&pp=ygUZYW5hY29uZGEgaW5zdGFsbCB0dXRvcmlhbA%3D%3D


* COmputers do not understand/execute plangs
* Programming Languages
    * Compiled: C
        * compiler which translates the program ahead of time
        * then you run the program yourself
    * Interpreted: Python
        * compiles *and runs* the program line-by-line
        * lacks features for, eg., controlling memory/speed/etc.

* Why interpreted languages?
    * More efficient for developers
    * Easier to change, run again, debug

* Why compiler languages?
    * Much faster to read over the whole program
    * Generate specific code
    * Optimize 
    * often more complex syntax, with more features for speed


* History:
    * 1989, became bigger in 2000s
    * augmented with data analysis, scientific tools
    * very fast for analysis...

```python
i = 0
for i in range(10):
    total += i

print(i) # prints 10
```


```python
# import = include external libraries
import numpy as np # numerical python

print(np.range(10).sum()) # prints 10
```



### High Level Overview of Syntax


```python

import numpy as np

name = "Michael"
location = "London, UK"
hobbies = ["arguing", "shouting", "disagreeing"]
likes = np.range(0, 10, 7) # 7 numbers from 0,10

person = {
    "name": "Bob",
    "city": {
        "name": "London",
        "pop": 10_000_000
    }
}

if "UK" in location:
    print("Welcome to the UK")
else:
    print("COme back!")

if len(hobbies) < 1:
    hobbies.append("A random hobby")

print(hobbies)
print(likes)
print(person["name"], person["city"])

for hobby in hobbies:
    print("Your hobby is {hobby}")

# the code above, *just means* ... this:
hobby = hobbies[0]
print(hobby)

hobby = hobbies[1]
print(hobby)

hobby = hobbies[2]
print(hobby)

hobby = hobbies[3]
print(hobby)

def report(name, location, hobbies):
    print("""
        YOUR NAME: {name}
        YOUR LOCATION: {location}
        YOUR HOBBIES: {hobbies}
    """)


report("Alice", "Leeds", ["Hiking", "Smiling"])
```

### Challenge: 

### Further Learning

* Youtube
*... 
## Lesson 2: 