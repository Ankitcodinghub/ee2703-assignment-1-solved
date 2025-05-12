# ee2703-assignment-1-solved
**TO GET THIS SOLUTION VISIT:** [EE2703 Assignment 1 Solved](https://www.ankitcodinghub.com/product/ee2703-assignment-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;90817&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EE2703 Assignment 1 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Assignment 1 Introduction to Python

Applied Programming Lab (EE2703)

1 Introduction

In the first three semesters, you learned about C programming, some VERILOG and some as- sembly language programming. In this lab, you are going to learn to code in Python. Python is one of the most popular programming languages of today. It’s simplicity in syntax, availability of a large number of open source libraries and the amazing open source community support makes it the favorite for scientists.

In this lab, we will learn how to use Python 3 for scientific computing.

1.1 Introduction to Python

Let’s start by trying to appreciate why python is so widely used. Let’s look at a small example code to compute the Fibonacci series. Let’s revise the algorithm first:

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>n=1
nold=1
print 1, nold
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>print 2, n
repeat for k=3,4,...,10
</pre>
<pre>    new=n+nold
    nold=n
    n=new
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>    print k,new
end loop
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Here is the code for the same in C:

</div>
</div>
<div class="layoutArea">
<div class="column">
1 #include&lt;stdio.h&gt;

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>#define kmax 10
int main(void){
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>int n,nold,new,k;
n=1;nold=1;
printf("%2d: %d\n",1,1);
printf("%2d: %d\n",2,1);
for( k=3;k&lt;=10;k++ ){
</pre>
new=n+nold;

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
} }

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>nold=n;
n=new;
printf("%2d: %d\n",k,new);
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
2 3 4 5 6 7 8 9

10 11 12 13 14

Let’s see how the same code will look in Python:

1 2 3 4 5 6 7 8

Most of it is trivial to read and understand!

2 The Python Language

When it comes to programming languages, there has been a long history of both compiler based languages and interpreter based languages. On the compiler side, there was Fortran followed by Cobol and after quite a while, there was Pascal and then finally C. With each new language new features were added. Of course the older languages did not stay put and so there is a Fortran2003 which has many of the features of C++ that are relevant to scientific programming.

Similarly, on the interpreter side, there were early attempts which included Flex and Basic, as well as the language of the command shell. When UNIX came on the scene, the shell came with a sophisticated programming language. But UNIX was special in that it added special power to this shell via other utilities such as awk, sed, yacc etc. These were utilities of power never before seen by casual users, and many inventive uses were found for them. Around the same time, on the IBM side, an interesting language called REXX also appeared which first invented one of the most important modern data structures, namely associative arrays.

With so many utilities and options things were a jumble and soon users began to demand a more integrated language that had all these features built in. This ushered in the modern set

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>print("1 1")
print("2 1")
n=1;nold=1
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>for k in range(3,11):
    new=n+nold
</pre>
<pre>    nold=n
    n=new
    print("%d %d" % (k, new))
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
of languages of which the premier one is PERL. PERL introduced many things into interpreted languages, so many that it is hard to enumerate them. But it tried to do too much and it is a sprawling language, one in which an expert can do magic, but one which requires quite a lot of studying to master.

Following PERL were some competitors of whom I consider Ruby and Python the best. Both are lovely languages from the user’s point of view and both are very similar in their features. Ruby has developed into a terrific language for database programming. Python has become the premier language for science and engineering. This is why we will focus on Python in this course. A third direction in which languages developed was the scratch pad type of language. It started in the sixties with early versions such as the Online Math System of UCLA. In the seventies, a powerful scientific development package called Basis was introduced. In the early eighties, IBM had introduced scientific spreadsheets for laboratory use. This branch has led to modern tools such as Matlab, Mathematica, and Labview.

Recently, a surprising development has taken place. People have developed modules (extra functionality) for Python that enables it to do most of the things that Matlab, Labview and Mathematica can do. This has created a special status for Python as far as technical users are concerned.

In this course, we will study Python. Along the way, most of the capabilities of Matlab will be demonstrated in Python, so that you can become a competent user of Matlab as well very quickly. In this assignment, the focus is on Python basics.

2.1 Hello World

Without breaking our tradition, let’s start with a hello world program. Open a file and write print(“Hello World”) and save it as hello.py.

1 print(“Hello World”)

Listing 1: “hello.py”

Now, open the terminal and issue the command python3 hello.py. In this command, we are invoking python with the file hello.py. Python interpreter will read through the file and execute it on the fly. Try adding more print statements to the file and see the output.

In python, you need not put a semicolon to end a statement. Newline will be contextually identified as the end of the statement. Yet, to have multiple statements in the same line, you may use a semicolon.

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>print("Statement 1")
print("Statement 2"); print("Statement 3")
print("Statement 4")
</pre>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
1 2 3

</div>
</div>
<div class="layoutArea">
<div class="column">
Listing 2: “hello.py”

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
3 IPython

</div>
</div>
<div class="layoutArea">
<div class="column">
One of Python’s most useful features is its interactive interpreter. It allows very fast testing of ideas without the overhead of creating test files. Issue command python3 in your terminal to start the interactive interpreter. In the prompt that you get, try our “Hello World” print statements. You will see something like this:

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>user@host:~$ python3
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>Python 3.6.7 (default, Oct 22 2018, 11:32:17)
[GCC 8.2.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
&gt;&gt;&gt; print("Hello World")
Hello World
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>&gt;&gt;&gt; print("Hai")
Hai
&gt;&gt;&gt; quit()
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
While this is very useful, the interpreter supplied with the standard Python distribution is somewhat limited for extended interactive use. IPython or “Interactive Python” provides a much more sophisticated interactive interpreter. Use quit() to exit the interpreter and try ipython3 to start IPython.

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>user@host:~$ ipython3
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>Python 3.6.7 (default, Oct 22 2018, 11:32:17)
Type "copyright", "credits" or "license" for more information.
</pre>
<pre>IPython 5.5.0 -- An enhanced Interactive Python.
?         -&gt; Introduction and overview of IPython’s features.
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>%quickref -&gt; Quick reference.
help      -&gt; Python’s own help system.
object?   -&gt; Details about ’object’, use ’object??’ for extra details.
</pre>
<pre>In [1]: print("Hello World")
Hello World
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>In [2]: quit()
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Apart from the color coding that you notice, IPython has a lot of useful features that we will see soon.

</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
4 Types and Operators 4.1 Basic Types

Python is a strongly typed language. It recognizes a variety of types but doesn’t require the user to declare any of them explicitly. They include:

• Integers

• Floats

• Complex numbers

• Boolean values

• Strings

• Tuples and Lists (these are arrays)

• Dictionaries (these are associative arrays)

Python does not expose pointers to the user, all the memory management is handled invisibly. Python has the ability to define other types as well, such as matrices through the use of classes. Let’s try some examples. Start IPython in your terminal and try these examples:

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
In [1]: a = 21 # define integer variable a and assign the value 21

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
In [2]: b = 2.1 # define float variable b and assign the value 2.1 In [3]: c = “21” # define string c and assign the value “21”

In [4]: c = ’21’ # You can use ” as well as ’ to define strings

In [5]: d = 10

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>In [6]: a/d
Out[6]: 2.1
</pre>
In [7]: a//d # floor division of a by d Out[7]: 2

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
# comment is the syntax for comments in python. Notice here that we did not explicitly mention the types of variables. Python takes care of it for us.

Note that in this example, -2 is simply ⌊−3⌋. 2

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>In [8]: i = -3; j = 2;
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>In [9]: i//j
Out[9]: -2
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
<pre>In [10]: z = 1 + 2j
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
Python handles complex numbers as native types. This is enormously useful to scientists and

</div>
</div>
<div class="layoutArea">
<div class="column">
engineers which is one reason why it is popular with them. Note that j is identified as by context. So the following code will give peculiar answers:

</div>
<div class="column">
√

</div>
<div class="column">
−1

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>In [11]: j = -2
In [12]: 1 + 2j
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>Out[12]: (1+2j)
In [13]: 1 + j
</pre>
<pre>Out[13]: -1
In [14]: 1 + 1j
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>Out[14]: (1+1j)
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
In the first complex assignment(1+2j), Python knew that you meant a complex number. But in the second case, it thought you meant the addition of 1 and the variable j. Also, note that if you assign the answer to a variable IPython does not print the answer. But if you do not assign it, the value is printed out.

True and False (capitalized as shown) are the fundamental boolean values. They can be as- signed to variables and they are also the result of logical expressions.

This is a peculiar expression. We have seen strings already. But any string can be a printf string that follows C syntax. This must be followed by a % sign and a list of values. Note that this is the general string, and can be used anywhere, not just where printing is going to happen. Following is another (relatively new) way of creating strings:

format() function is capable of doing much more. You can explore it online. In [19]: “””This is a multi

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>In [15]: v = True
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>In [16]: j &gt; 2 or v
Out[16]: True
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>In [17]: "This is the %dth sentence of %s." % (4, "the text")
Out[17]: ’This is the 4th sentence of the text.’
</pre>
</div>
</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>In [18]: "This is the {}th sentence of {}.".format(4, "the text")
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>Out[18]: ’This is the 4th sentence of the text.’
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
6

</div>
</div>
</div>
<div class="page" title="Page 7">
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
…: line string”””

Out[19]: ’This is a multi\nline string’

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>In [20]: print(_)
This is a multi
line string
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Sometimes we might want embedded newlines in strings. Then the above syntax helps us. Everything between the triple quotes is part of the string. Note the print command. It prints “ ” which is Python’s variable that holds the last computed value that was not assigned to a variable. Naturally, there is a large collection of built-in functions to work with strings.

Home work

Explore the following functions on strings:

1. split() 2. count() 3. find()

4. isalnum() 5. isalpha() 6. strip() 7. zfill()

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>In [21]: str(123)
Out[21]: ’123’
In [22]: float("12.3")
Out[22]: 12.3
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>In [23]: int("abc")
---------------------------------------------------------------------------
ValueError                                Traceback (most recent call last)
&lt;ipython-input-12-2dda1cc00c48&gt; in &lt;module&gt;()
----&gt; 1 int("abc")
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>ValueError: invalid literal for int() with base 10: ’abc’
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
While data conversions are very simple with python, unexpected inputs will result in errors. We should “catch” these errors to make the program robust. We will see how to do the same in the next lab.

4.2 Operators

Python provides all the common operators like add, subtract and multiply. Note that operators for Boolean operations are not symbols but operator names themselves!

</div>
</div>
<div class="layoutArea">
<div class="column">
In [24]: 1 + 2

</div>
</div>
<div class="layoutArea">
<div class="column">
7

</div>
</div>
</div>
<div class="page" title="Page 8">
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Out[24]: 3

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>In [25]: 1 == 2
Out[25]: False
</pre>
In [26]: True or False # Boolean OR In [27]: True

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
In [28]: True and False # Boolean AND In [29]: False

In [30]: not False # Boolean negation In [31]: True

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
In [32]: 2**4 # 24 Out[32]: 16

In [33]: 2 in [1, 2, 3] # Does [1,2,3] have element 2? Out[33]: True

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>In [34]: a = 2; b = a; a is b
Out[34]: True
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Note that is is different from ==. For example:

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>In [35]: a = 2; b = 2.0; a is b
Out[35]: False
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>In [36]: a==b
Out[36]: True
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
4.3 Lists

Lists store items in order so that they can be accessed via their index. This is the python equivalent of C arrays. The indexing follows the C indexing (i.e., starts from 0). Unlike C, the elements of a list do not have to be identical in type.

Arrays can be created by just specifying the elements as in the first example above. The “constructor” is a set of comma separated values enclosed in square brackets.

In [39]: arr = range(10); list(arr)

8

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>In [37]: arr = [1, 2.1, 3, "string"];
In [38]: arr
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>Out[38]: [1, 2.1, 3, "string"]
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
</div>
<div class="page" title="Page 9">
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>Out[39]: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9]
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>In [40]: arr = range(2,5); list(arr)
Out[40]: [2, 3, 4]
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
A common use for arrays is to create a sequence of uniformly spaced points. This can be done with the range() function. Without a second argument, it returns a sequence of integers starting with zero up to the given argument (but not including it). With two arguments, the sequence starts at the first argument and goes up to the second. Given three arguments, the third argument is the step. Note that range expects integer arguments.

One thing to notice here is the use of list(). It is simply doing a type conversion of output of range() to List (Similar to earlier examples of str(), int(), float() etc…). In python 3, the range() function does not return a pure list. Instead, it returns a sequence object. Sequence objects can be used to loop through the sequence it is representing. list() here converts the sequence object to a list. The ability to work with sequence objects or sequence generators is another powerful feature of python. In fact, the potential comes from python being lazy! In this case, since python is only creating the sequence object and not the sequence itself, it saves a lot of space. Moreover, the sequence is not computed until you use it, thus saving the computation time as well. See how laziness saves us space and time!

In IPython, &lt;entity&gt;? will give you the details of the entity. The entity here could be a function, variable, modules etc… (We will discuss about modules soon)

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>In [41]: range?
Init signature: range(self, /, *args, **kwargs)
Docstring:
range(stop) -&gt; range object
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>range(start, stop[, step]) -&gt; range object
</pre>
<pre>Return an object that produces a sequence of integers from start (inclusive)
to stop (exclusive) by step.  range(i, j) produces i, i+1, i+2, ..., j-1.
start defaults to 0, and stop is omitted!  range(4) produces 0, 1, 2, 3.
These are exactly the valid indices for a list of 4 elements.
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>When step is given, it specifies the increment (or decrement).
Type:           type
</pre>
<pre>In [42]: a = [1,2,3]
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>In [43]: a?
Type:        list
String form: [1, 2, 3]
Length:      3
Docstring:
list() -&gt; new empty list
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>list(iterable) -&gt; new list initialized from iterable’s items
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
9

</div>
</div>
</div>
<div class="page" title="Page 10">
<div class="layoutArea">
<div class="column">
4.3.1 List indexing

</div>
</div>
<div class="layoutArea">
<div class="column">
The list indexing in Python is quite advanced compared to C.

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>In [44]: arr=[1, 2, [4,5,6], "This is a string"]
In [45]: arr[0]
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Out[45]: 1

<pre>In [46]: arr[2]
Out[46]: [4, 5, 6]
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>In [47]: arr[3]
Out[47]: ’This is a string’
</pre>
<pre>In [48]: arr = list(range(10)); arr[1:7:2]
Out[48]: [1, 3, 5]
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
We can refer to a portion of an array, using what is known as a slice. 1:7:2 means start with index 1, increment by 2 up to but not including index 7.

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>In [49]: arr[2][1]
Out[49]: 5
</pre>
<pre>In [50]: arr[3][2]
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Out[50]: ’i’

<pre>In [51]: arr[-1]
Out[51]: ’This is a string’
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
These syntaxes are quite intuitive if read correctly. arr[2] is a list. In arr[2][1], you are then indexing the result of arr[2]. Visualize this as (arr[2])[1]. arr[3][2] is also similar. Note that in Python strings are index-able just like lists. The last command here is interesting. The negative number given is indexing the list backward. Note that there is no negative zero, so -1 refers to the last element.

Can you combine negative indexing with slicing? Try out all the combinations you can think of.

4.3.2 Homework

Refer and find

1. How to create an empty list

2. How to add/remove an element to/from a list

</div>
</div>
<div class="layoutArea">
<div class="column">
10

</div>
</div>
</div>
<div class="page" title="Page 11">
<div class="layoutArea">
<div class="column">
3. How to replace an element in the list

</div>
</div>
<div class="layoutArea">
<div class="column">
4. How to combine two lists

5. How to sort a list of integers.

What happens if the list you sort has strings too?

There is another type of list in Python called the tuple. It merely means a constant list, i.e. a list whose values cannot change. It follows the same syntax except its values are enclosed in round brackets.

4.4 Dictionaries

Python also has associative arrays whose values are indexed not just by numbers but by any hashable objects. For now, let’s not worry about what is a hashable object. Keep in mind that integers, floating point numbers, string etc… are all hashable. But a list is not hashable. Note that a tuple is hashable.

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
In [52]: hash = { “a”: “Argentina”, “b”: “bolivia”, “c”: [1,2,3] } # initializing a dictionary

<pre>In [53]: hash["a"]
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>Out[53]: ’Argentina’
In [54]: hash["c"]
</pre>
<pre>Out[54]: [1, 2, 3]
In [55]: hash[0]
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>---------------------------------------------------------------------------
KeyError                                  Traceback (most recent call last)
&lt;ipython-input-27-df0d218756dd&gt; in &lt;module&gt;()
----&gt; 1 hash[0]
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>KeyError: 0
In [56]: hash[0] = "zero"
</pre>
<pre>In [57]: hash
Out[57]: {0: ’zero’, ’a’: ’Argentina’, ’b’: ’bolivia’, ’c’: [1, 2, 3]}
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>In [58]: hash[0]
Out[58]: ’zero’
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
The first attempt of hash[0] fails since the elements of dictionary are not accessed by an index. The error message says that 0 is not a key found in the dictionary. A dictionary consists of an unordered set of key-value pairs. Each pair has an object(string, integer, etc…) called the key and some value. The value could be any object. In the above example string “c” is a key and the list [1, 2, 3] is the value corresponding to “c”.

</div>
</div>
<div class="layoutArea">
<div class="column">
11

</div>
</div>
</div>
<div class="page" title="Page 12">
<div class="layoutArea">
<div class="column">
5 Basic Programming

</div>
</div>
<div class="layoutArea">
<div class="column">
The basic structures in Python are the if block, the for block and functions. There are others, but these are the important ones.

5.1 if Blocks

Note that blocks start with a statement ending in a colon. Unlike C, python does not use curly brackets to identify blocks. Instead, the extent of indentation is how python knows which block the statement belongs to. Thus the code in the block must be indented evenly. The above code is the standard if block. The general structure is

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>In [59]: if j &gt; 2 or v:
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>    ...:     print("Too many inputs: %d" % j)
</pre>
<pre>    ...:
Too many inputs: 3
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>if condition:
    commands
</pre>
<pre>elif condition:
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>    commands
elif condition:
</pre>
commands …

<pre>else:
    commands
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
There is no switch command in Python, and this construction has to do the job of the switch- case statement as well.

5.2 for Loops

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>In [60]: sum = 0
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>In [61]: for  i in range(20):
    ...:     sum+=i
</pre>
<pre>    ...:
In [62]: print("The sum of 0, 1, ... 19 = %d" % sum)
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>The sum of 0, 1, ... 19 = 190
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
The for block in Python iterates over an array of values. Here it is iterating over a set of integers.

</div>
</div>
<div class="layoutArea">
<div class="column">
12

</div>
</div>
</div>
<div class="page" title="Page 13">
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>In [63]: words = ["Water", "water", "everywhere", "but", "not", "a", "drop", "to"
   , "drink"]
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>In [64]: for w in words:
    ...:     print("%s" % w, end=" ")
    ...:
</pre>
<pre>Water water everywhere but not a drop to drink
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
This for block prints out all the values of array words. Note that the print() function is given a second argument named end which replaces the carriage return at the end with the given string.

5.2.1 List Comprehension

Equipped with the knowledge of for loops, let’s jump back to our lists for a while. Let’s attempt to create some lists using for loops.

Here, ** is the operator for power. i.e. 2**i is nothing but 2i. While we are able to generate our list, this is not the pythonic way of doing it.

This method will also give the same result as before. Notice that this is short as well as more readable for a “Python-guy”. This method of creating lists is called list-comprehension.

Home Work

<ol>
<li>Write corresponding for loop for the following commands:
Note that &lt;value&gt; if &lt;condition&gt; else &lt;value&gt; is nothing but the ternary operator of python.
</li>
<li>Write the command to generate prime numbers in single line. Don’t worry about the efficiency of your command.</li>
</ol>
</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>In [65]: l = []
In [66]: for i in range(4):
</pre>
<pre>    ...:     l.append(2**i)
    ...:
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>In [67]: l
Out[67]: [1, 2, 4, 8]
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>In [68]: l = [ 2**i for i in range(4) ]; l
Out[68]: [1, 2, 4, 8]
</pre>
</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>[ i for i in range(10) if i%2==0 ]
[ str(i)+" is "+("even" if i%2==0 else "odd") for i in range(1, 5)]
</pre>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
13

</div>
</div>
</div>
<div class="page" title="Page 14">
<div class="layoutArea">
<div class="column">
5.3 while Loops

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>In [69]: sum = 0; i = 0
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>In [70]: while i &lt; 20:
</pre>
<ul>
<li>…: &nbsp;i += 1</li>
<li>
<pre>    ...: &nbsp;    if i%3 == 0:
</pre>
</li>
<li>
<pre>    ...: &nbsp;        continue
</pre>
</li>
<li>…: &nbsp;sum += i</li>
</ul>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
…:

<pre>In [71]: print("The sum = %d" % sum)
The sum = 147
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
The while construct is self-evident. It iterates till the condition fails. The if command skips to the next iteration every time a multiple of 3 is encountered. Also, note that the continue statement can be placed on the if line itself if desired. This is not actually recommended though.

5.4 Functions

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
In [72]: def factorial(n=0):

…: “”” Computes the factorial of an integer “””

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<ul>
<li>…: &nbsp;fact = 1</li>
<li>
<pre>...: &nbsp;    for i in range(1, n+1):
</pre>
</li>
<li>…: &nbsp;fact *= i</li>
<li>
<pre>...: &nbsp;    return fact
...:
</pre>
</li>
</ul>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>In [73]: factorial(5)
Out[73]: 120
</pre>
In [74]: factorial() # use the default value of n Out[74]: 1

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>In [75]: factorial(3.5)
---------------------------------------------------------------------------
TypeError                                 Traceback (most recent call last)
&lt;ipython-input-62-24f344214769&gt; in &lt;module&gt;()
----&gt; 1 factorial(3.5)
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>&lt;ipython-input-58-3f057ea44b00&gt; in factorial(n)
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
2

3 —-&gt; 4

</div>
<div class="column">
<pre>""" Computes the factorial of an integer """
</pre>
<pre>fact = 1
for i in range(1, n+1):
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>5         fact *= i
6     return fact
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
14

</div>
</div>
</div>
<div class="page" title="Page 15">
<div class="layoutArea">
<div class="column">
<pre>TypeError: ’float’ object cannot be interpreted as an integer
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
Functions are also defined using indented blocks. Arguments are like C and can have default values. Here the default value of n is zero, which is the value assumed for n if no argument is passed. If a float is passed, an error is generated. This is not an argument mismatch error – python is very forgiving about those. From the error message, it is evident python has triggered function call and has also executed the statements till line 4. The error has occurred only at line 4 while invoking range() function since it requires integer arguments.

The tripple quoted string under function name shows the self-documenting nature of Python functions. Anything entered as a triple-quoted string at the beginning of a function is retained as documentation for the function.

6 File Handling

There are many commands for file management. I will walk you through some of them. Reading up the remaining is your job. Let’s create a dummy file named test.txt and add some text in it for testing purpose.

The first line opens the file for reading and assigns it to the file pointer f. The next line reads in the entire file into data as one long string. You should always close the file after reading it.

f.readlines() will return a list of strings corresponding to each line in the file. A more “pythonic” way of doing the above tasks is by using with keyword.

Here, open() is executed and the result is aliased with f. Using with will free you from things like closing the file. It will be Python’s responsibility to create and destroy the file streams in a clean manner.

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>f = open("test.txt")
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>data = f.read()
f.close()
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>f = open("test.txt")
lines = f.readlines()
f.close()
print("1st line is %s" % lines[0])
</pre>
</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>with open("test.txt") as f:
    lines = f.readlines()
    print("1st line is %s" % lines[0])
</pre>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
15

</div>
</div>
</div>
<div class="page" title="Page 16">
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>In [76]: with open("file.txt", "w") as f:
    ...:    f.write("First line\n")
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<ul>
<li>
<pre>...: &nbsp;   f.write("Second line\n")
</pre>
</li>
<li>
<pre>...: &nbsp;   f.write("Last line\n")
</pre>
</li>
</ul>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
This is the syntax to write to a file. You can replace “w” with “a” for appending to the file.

7 Modules

Python comes with a huge variety of helper functions bundled in modules. For now, all we need to know is that modules are collections of functions that have their own “namespace”. You import a module by using the import command:

Now that we have imported the module os, we can use the functions defined in it. system() is a function defined under the module os. Read about both the module as well as the function using ? symbol in IPython.

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>In [77]: import os
</pre>
</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>In [78]: os.system?
Signature: os.system(command)
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>Docstring: Execute the command in a subshell.
Type:      builtin_function_or_method
</pre>
In [79]: os.system(“ls”)

Out[79]: # This output will be specific to your computer.

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
The command os. is helping us to use the functions that are defined in the namespace of os. ls is the bash command used to list contents of a directory in Linux.

You can also import all/specific functions inside a module using the following syntax:

You may visualize this hierarchy like a file-system. Think about os as a directory and system() as one inside it.

7.1 Commandline arguments

IPython is only an environment where you can test your ideas. Large projects need to be written in a file and executed using the command python &lt;file&gt;. Sometimes, we need to

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
In [80]: from os import * # import everything inside os

In [81]: from os import system # import function system() from module os

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
16

</div>
</div>
</div>
<div class="page" title="Page 17">
<div class="layoutArea">
<div class="column">
supply some arguments to the program in the commandline. You should be already familiar with this from C.

In Python, we take the help of sys module to access the commandline arguments.

1 2 3 4

8 Exception Handling

Exceptions are events that occur as a result of unexpected cases in code. For example,

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
import sys

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>arg0 = sys.argv[0]
arg1 = sys.argv[1]
print("number of arguments received by %s = %d" % (sys.argv[0], len(sys.argv)))
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
In [82]: age = input(“What’s your age? “) # This is how to accept input

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>What’s your age?  2.3
</pre>
In [83]: type(age) # This is how to find type of a variable Out[83]: str # age is string data type

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
In [84]: age = int(age) # Let’s convert the age to int data type ————————————————————————— ValueError Traceback (most recent call last) &lt;ipython-input-4-9d45e9e78105&gt; in &lt;module&gt;()

<pre>----&gt; 1 age = int(age)
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>ValueError: invalid literal for int() with base 10: ’2.3’
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Here, I did not foresee that the user might enter a value which cannot be converted to integer. The int() function is raising a ValueError which is causing my program to crash. The right way to tackle this problem is to validate user input and make sure that it can actually be converted to integer before you invoke int() function. For example, age.isdigit() will return True if age represents a whole number.

Another approach would be to get alerted when the function is complaining about an error. We shall call this complaint as exception. We, getting alerted about the exception is called catching the exception.

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>In [85]: try:
    ...:     age = int(age)
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>    ...: except Exception:
</pre>
<pre>    ...:     print("Invalid age")
Invalid age
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
17

</div>
</div>
</div>
<div class="page" title="Page 18">
<div class="layoutArea">
<div class="column">
As soon as the code inside try block causes an exception, the control is transferred to the code inside except block. You can now handle the error case here. I have simply printed an error message, but you can do better. Note that the program is not crashing in this case.

There are many kinds of exceptions of which Exception is the super set of all of them. If you read through the error message from int() carefully, you will see that it says ValueError. This is a subset of Exception (For those of you familiar with OOP concepts, ValueError is inherited from Exception). It’s a good practice to use the smallest subset instead of using Exception.

The raised ValueError is caught and aliased as e here.

9 Spice – Part 1

I think the best way to learn a language is to do a project in it. So, we will attempt to build a slightly complex program in python and learn the language on the way. Let’s try and build a spice program in python. We will learn more about python on the way.

9.1 Introduction

In this experiment, let’s attempt to write a program that can solve electrical circuits for us. We will build this in 3 parts. This week, we will create the first part where we will read the input file to construct the circuit. The circuit has only simple devices. Over the coming weeks, we will analyze the input that was read and solve the circuit.

9.2 Spice netlist

A spice netlist consists of lines of the following forms:

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>In [86]: try:
    ...:     age = int(age)
    ...: except ValueError as e:
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>    ...:     print(e)
invalid literal for int() with base 10:  ’2.3’
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
….

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>.circuit
name n1 n2 value # comment
name n1 n2 n3 n4 value # comment
name n1 n2 vname value # comment
.end
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
18

</div>
</div>
</div>
<div class="page" title="Page 19">
<div class="layoutArea">
<div class="column">
….

</div>
</div>
<div class="layoutArea">
<div class="column">
When reading, we are to neglect lines till we meet a dot command, i.e., a line starting with a dot. If the dot command is .circuit, the following lines define the circuit. The circuit definition ends with a line containing .end. Note: These dot commands must have . in the first character of the line. This distinguishes them from lines where a . comes in the middle of the line.

The circuit definition consists of lines, each of which defines a branch of the circuit. For instance,

is a branch representing a dependent source, where n1, n2 , n3 and n4 are symbolic names representing nodes, name is the name of the element. The first letter of the name defines the type of element, as follows:

value is the value of the element in Ω, H, F, Amps or Volts, respectively. In the case of current controlled sources, the controlling current must be the current through a voltage source. This is not a limitation since all we need to do is to add a zero volt voltage source where we want and use its current as the controlling value.

Incidentally note that zero volt voltage sources are frequently used in spice to measure current in a branch of interest. This is because the equations automatically solve for the current through voltage sources so that they become available for further analysis.

The line can optionally be followed by a comment. This is defined as anything that follows a # character.

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>name n1 n2 n3 n4 value # comment
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
19

</div>
</div>
</div>
<div class="page" title="Page 20">
<div class="layoutArea">
<div class="column">
Each impedance line in the file translates into an equation:

</div>
</div>
<div class="layoutArea">
<div class="column">
Vn1 − Vn2 = In1,n2 Rn1,n2 V −V =L dIn1,n2

</div>
</div>
<div class="layoutArea">
<div class="column">
n1

</div>
<div class="column">
n2

</div>
<div class="column">
n1,n2

= C

</div>
<div class="column">
dt

d(Vn1,n2 − Vn1,n2) dt

</div>
</div>
<div class="layoutArea">
<div class="column">
I

</div>
</div>
<div class="layoutArea">
<div class="column">
n1,n2

</div>
<div class="column">
n1,n2

</div>
</div>
<div class="layoutArea">
<div class="column">
Each source line in the file becomes

Vn1 − Vn2 = εn1,n2

In1,n2 = In1,n2

Vn1 −Vn2=E(Vn3 −Vn4) Vn1 − V n2 = F Ik

In1,n2 = G(Vn3 − Vn4) In1,n2 = HIk

where Ik is the current through the controlling voltage source.

9.3 Assignment

Write the pseudo code to do the following

<ol>
<li>Accept the name of netlist file as commandline.</li>
<li>Check if the user has actually provided the filename or not and give appropriate error message if needed.

It is always a good practice to validate the number of arguments given to the program. Note that a good program never crash. It will check for all the carelessness that can happen with the input and take necessary actions.</li>
<li>Determine the section that contains the circuit definition (i.e., the portion that started with a .circuit line and ended with a .end line)</li>
<li>Parse each line of the section and extract the words (tokens).</li>
<li>Analyze the tokens and determine the from node, the to node, the type of element and the value. If it is a dependent source, you also need to extract additional information. Note that node names are alphanumeric.</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
20

</div>
</div>
</div>
<div class="page" title="Page 21">
<div class="layoutArea">
<div class="column">
6. When all the lines have been read in, close the file.

</div>
</div>
<div class="layoutArea">
<div class="column">
7. Traverse the circuit definition from last element to first and print out each line with words in reverse order.

Eg: if the netlist is

Print

Now write the code to do the same in Python. You should submit this code on Moodle.

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>.circuit
R... n1 n2 value
E... n1 n2 n3 n4 value
.end
</pre>
</div>
</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>value n4 n3 n2 n1 E....
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>value n2 n1 R...
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
21

</div>
</div>
</div>
