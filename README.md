# Course 4 - Python for Data Science
## IBM Data Science Professional Certificate 

At the bottom of each lab is instructions to share them on GitHub. Since the labs are comprehensive, I'm using this repository in lieu of notes.

* Module 1 - Python Basics 
  - PY0101EN-1-1 Expressions and variables
    * int, float, str
    * converting type
    * bool, True, False
    * basic math
    * variables
  - PY0101EN-1-2 Strings 
    * index, negative index
    * contatenate
    * slice
    * stride
    * escape sequences
    * operatons
* Module - Python Data Structures
  - PY0101EN-2-1 tuple=()
    * index, negative index
    * concatenate
    * slice
    * len
    * immutability
    * nesting
  - PY0101EN-2-2 list=[]
    * slice
    * concatenate
    * extend
    * append
    * mutability
    * del
    * split
    * aliasing
  - PY0101EN-2-3 - dict{key:value}
    * two column table w/uniqe keys
    * querying value - dict[key]
    * adding - dict[key]=value
    * deleting - del(dict[key])
    * verifying - 'KeyName' in dict
    * listing contents - dict.keys() or dict.values()
  - PY0101EN-2-4 - set={}
    * lists with only unique elements
    * typecast list to set - set(list)
    * set.add()
    * set.remove()
    * set1.intersection(set2) or set3=set1&set2
    * set1.union(set2)
    * set1.diference(set2)
    * set3.issubset(set1)
    * set1.issuperset(set2)
* Module - Python Programming Fundamentals
  - PY0101EN-3-1 Conditions and Branching
    * ==, !=, <, >, <=, >=
    * strings compared by ascii value, characters judged in order
    * if, else, elif (else if)
    * and, or
  - PY0101EN-3-2 Loops
    * impression: 
      - lab/lesson inconsistencies in required program steps and syntax for () starting to drive me batty.
      - don't forget to include statement to ensure loop stops if all compares are valid
    * range(start, stop, [step]) - results never include stop value, stop is only required value
    * for
    * while
  - PY0101EN-3-3 Functions
    * built-in
    * created
      - def functionname(arg1, *args)
        - statement/internal variable/"""help description"""
      - global variable
  - PY0101EN-3-4 Exception Handling
    * try/except
    * else
    * finally
  - PY0101EN-3-5 Objects and Classes
    * Not sure learned what was supposed to here. After being given tons of examples of "create a class with these two attribute variables and then create a function to modify one of the variables," we're given a complex exercise to create a class based on manipulating and filtering text... 
    * Objects & Classes
    * Creating classes
    * Attributes
    * Methods/functions
* Module 4 - Working with Data in Python
  - PY0101EN-4-1 Reading Files with Open
  - PY0101EN-4-2 Writing Files with Open
    * use with open(file/object, "r"/"w"/"a") as object: to ensure file object is closed at end of block
    * r+ / w+ / a+
    * .tell() / .seek(offset,from)
  - Python_Basics Pandas with IBM Watson Studio
    * Ending quiz required functions that were not covered, so had to research each task. Still, happy in that I figured it out without looking at the solution first.  I can dooos it. Lab link to GitHub worked this time, so posted directly.
    * pandas.read_csv / read_excel...to_csv(x.csv)
    * file.head()
    * df=pd.DataFrame(dictionary_key)
    * df1=df[['column1','column4']]
    * df['column'].unique()
    * df1=df[df['column']>=another_column_value]
    * df.iloc[[/df.loc]]
    * df.copy()
    * df.index
  - PY0101EN-4-4 One Dimensional Numpy
    * np.array()
    * array addition, subtraction, multiplication 
    * Hadamard product, producting same dimension matrices: a &#8728; b
    * Dot product, producing scalar number to determine sameness: np.dot()
    * plotting vectors using matplotlib.pyplot and defined functions
  - PY0101EN-4-5 Two Dimensional Numpy
    * np.array(a) where a is a nested list
    * ndim, shape, size
    * addition, hadamard product(array multiplication), dot product (matrix multiplication)
    * sine, transpose
* Module - APIs and Data Collections
  - PY0101EN-5-1 Introduction to API
    *  Using Pandas API
    *  REST API basics
    *  Quiz on Tuples
  - PY0101EN-5-2 Watson Speech to Text and Language Translator API
  - PY0101EN-5-3 Access REST APIs & Request HTTP
  - PY0101EN-5-4 Webscraping
  - PY0101EN-5-5 Working with Different File Formats

