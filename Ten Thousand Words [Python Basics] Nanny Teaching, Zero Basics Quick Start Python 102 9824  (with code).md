###  foreword 

After the last time I said that I would publish a series of articles on Python beginners' introductory tutorials, I kept sorting out and coding, and finally wrote out the [Basic Introduction]. 

![avatar]( b8cb799518a44c50b24859d74bf43d9a.png) 

I have already published the content of [Regular Expressions] and [Object Oriented Programming] in advanced programming. If you are interested, you can check out my column. Today's content is [Basic Introduction]. 

>  [Python beginner tutorial column] 

If you don't accumulate a few steps, you can't reach a thousand miles, and if you don't accumulate small streams, you can't make a river or sea. With the accumulation of knowledge one by one, sooner or later you will become the kind of person you envy. Next is the formal content. 

![avatar]( b47a6e1f91f2494ca77ea8c453e9df1b.jpg) 

###  Today's content preview 

Python is a programming language. In the eyes of developers, languages can be divided into three categories: 

Similarly, in the eyes of developers, it can also be divided into high-level programming languages and low-level programming languages. The closer to human languages, the higher the level, such as Python; the closer to machine languages, the lower the level, such as assembly, is a low-level programmer design language. 

Drink water without forgetting to dig wells. Before we officially learn Python, it is necessary for us to understand the past of Python and our ancestors. 

Python was created by Guido van Rossum during Christmas in 1989. Domestic programmers prefer simple but simple names, so they took the first three letters of his name, gui, and were nicknamed Uncle Turtle. The origin of Python's name also originated from Uncle Turtle's preference, because Uncle Turtle at that time preferred the sketch "Monty Python's Flying Circus", so he called the language he created Python. 

![avatar]( 45e3e5649c094ad1bd49f75e471060cf.jpg) 

![avatar]( 2fb0e6df8a8d41d492ed8abe4a786220.png) 

 Uncle Turtle is only 65 years old this year, and he still has a lot of hair, so friends who learn Python don't have to worry too much about baldness. Uncle Turtle, I remember joining the development department of Microsoft last year, and he is still writing code in the front line when he is old, which is really admirable.  

>  I have a lot of technical dry goods in my private stash, and fans can use them for free (click here). 

Python is mainly characterized by concise syntax, powerful class libraries, glue language (calling class libraries in other languages), and less code. This simple understanding is enough, and you will understand when you use it later. 

>  (Whoever uses it knows) 

There are two main mechanisms for running a program: compiled and interpreted. Compiled is to compile code (source files) into machine code files through a compiler, and directly execute machine code files when running, such as C language; interpreted is to translate and run source files line by line through an interpreter. 

Python is an interpreted language. 

Compiled and interpreted languages have their own advantages and disadvantages. 

Disadvantages: Slow execution, Advantages: Can be cross-platform (operating system) 

Disadvantages: cannot be cross-platform, advantages: fast execution 

For beginners learning Python, I suggest installing Python and Pycharm. I will often use these two software when writing code in the future. Both software can be downloaded from the official website. If you don't want to go to the official website to download, I also have a good installation package. After picking it up, you can start the installation process. 

>  Software package download link: https://pan.baidu.com/s/1BtnMGsfYNFIkmJ26wuGjCw Extraction code: al6e 

The installation of Python can be downloaded directly from the official website. Since it is a foreign website, the response and download speed may be a little slow. If you are not in a hurry, just wait. If you want to be faster, use Xunlei to download quickly. 

![avatar]( ebab87d225aa4df9ab65c9a1555f0a04.png) 

 The download address is ttps://www.python.org/downloads/, or you can enter the download page from the official outlet Downloads, select the corresponding version of your computer, mine is a Windows computer, so just click Windows directly.  

Python is currently 3.9.7 version, you can see that there are many versions to choose from to download, I use 3.9.5 this version, and then choose the model according to the computer, my computer is 64-bit, so I download 64-bit software. 

![avatar]( 2b9b1b1c8d594d99800d8023831b0e4d.png) 

- Install Python 

![avatar]( b9fe178e4466486e9ac151b4ad898fbb.png) 

 Double-click the downloaded file to enter the installation interface. Select Custom Install and check both options to install Python into the PATH. This interface does not change, just click Next. Choose a path you want to install, otherwise it will install you to the C drive, I will install it to the D drive, and then click Install. After the installation is complete, click Close. 

![avatar]( 3ec5fbbe35c84f349b451c0651e86841.png) 

To test whether your Python installation is successful, the WIN + R keys bring up the command window and enter cmd. 

![avatar]( b52b7c687de04e769b556f687fbe3ec7.png) 

 ![avatar]( a6b833b0e1c544a1873775623d34dc15.png) 

  Enter Python in the black window, and then press Enter. If you prompt Python 3.9.6 and other information, it means that the installation has been successful. If there is no prompt, go back and see which environment you made a mistake.  

Download from the official website of Pycharm, choose the system, I am a Windows system, so the default remains unchanged, and then download the community version, and then use the professional version when you become stronger. 

![avatar]( 067e7101e9d541809dd96863f987432f.png) 

  After downloading, double-click to start the installation. 

![avatar]( 7e2e949dc591434db59ba46197260a76.png) 

  Click Next. 

![avatar]( 0cd84d74f171400a9db8fcaa7e6e27d6.png) 

  Customize the installation path, it is recommended to install other disks other than the C drive, and click Next. 

![avatar]( 8bac1518ad434f648f60fe9e19246d1c.png) 

Check all. 

![avatar]( 5eaa44cfc6274b84aa2fc416216969ca.png) 

  After arriving here, the default is enough, and click Install to start the installation. 

![avatar]( 191c5ac5c0a34f2dac4a618de4b61210.png) 

  After waiting for the installation to be completed, click finish to install it. 

![avatar]( 471684c70d2a466485f6aa70d6c088ea.png) 

>  I have a lot of technical dry goods in my private stash, and fans can use them for free (click here). 

We are ready to write our first line of code, the famous Hello World. 

![avatar]( f51043e456f745318e353ff388ff5db9.png) 

 Open Pycharm, click New Project to create a new project, and you can do this for new projects in the future. Open in the middle is to open the project. If you have a written project, you can open it from here.  

The next step is to set the location of the project. If you follow my steps when installing Pycharm, the Base interpreter will automatically detect Python. You can do it without changing it, just click Create in the lower left corner to create it. 

![avatar]( 8e66f9b134644d8d9d712ad2caf64e54.png) 

 ![avatar]( 26bc1489dc7d4290ba76a99da776853b.png) 

 ![avatar]( 3c381717d12144f69ccb7ea1164b91e6.png) 

  Then click on the left. A pop-up box will pop up when entering the page. Just click Close to close it.  

What we created earlier is a project, which is a folder to store the source code. Here we start to create the source code files. (My computer had some projects before, so there are many folders below, which may not be the same as yours.) 

Click on the email pop-up option python_learn create a good project, select New to create a new one, and select Python File to create a Python source file. 

![avatar]( 7b8499e1b4e04fba8aa600a92bed3d69.png) 

 ![avatar]( 4f33ceeb1b464824bda69d91bb742930.png) 

  Then you will be prompted to give your file a name, and then hit enter to complete the creation of the code source file. To start writing code, one of the most commonly used functions, print (), is used to output content. Functions have their syntax. As long as you follow the syntax to write code, the software will know what you want to do. 

The syntax of print is as follows, with a newline by default. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Next, we are going to output our first line of code. Hello world is a string. You need to add "" to be the correct format, otherwise an error will be reported. We will discuss the string in detail later. Here, you only need to know that you have to write code in this format to achieve the desired result. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
![avatar]( c1e0cee747324be78d6891b67a6e9c4d.png) 

 After writing the code, you need to run it to get the result. You can right-click the pop-up option box and select Run 'learn_1 'to start running. Run means run, learn_1 is the name I gave this source file just now. In addition to right-clicking to run, you can also directly use shortcut Ctrl + Shift + F10 to execute the result: 

![avatar]( 12e5ebcdfcc143ed9a9ff8ed6d4d5820.png) 

  Congratulations, you have exported your first line of code and officially started your Python journey! 

Before you can write code in Python, you must have a basic knowledge of Python, otherwise you may struggle with it. Basic knowledge includes input and output, variables, data types, expressions, and operators. 

Python has many functions, which we will discuss in detail later, but here are the two most basic functions: input and output. 

The output function print (), which we have used before, has the following syntax: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
The input function is input (), the function is to receive user input, and the syntax is: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Example: Receive a password entered by a user and print it 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
In Python, "#" indicates a comment, and the things after "#" will not be executed. After the code runs, "Please enter your password:" appears first, and then enter it at will, such as entering 123, and the execution result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Successfully receives user input and prints it out. 

A variable is a name that needs to be assigned before use. Variables must conform to the naming convention of identifiers (names). This is a hard requirement. Identifiers are equivalent to names, including variable names, function names, class names, etc. 

>  Keywords: if while for as import reserved words: input, print range 

>  1. Package name: all lowercase, such as time;

  2. Class name: the first letter of each word is uppercase, other lowercase, short for big hump naming, such as HelloWorld;

  3. Variable name/function name: the first letter of the first word is lowercase, and the first letter of the following word is uppercase, which is abbreviated as a small hump name, such as helloWorld;

  4. Constants: all caps, such as Hello. 

Data types can be divided into the following six categories: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
When writing code, we often need to convert different data types. The main data type conversion methods are as follows: 

(1) string to integer 

The method is int (str), and the string must be a number, for example: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Execution result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
(2) Floating point type to integer type 

The method is int (float), for example: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Run result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
(3) string to float, the method is float (str), the string must be the sum of numbers, for example: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Run result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
(4) Integer type to floating point type, the method is float (int), for example: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Run result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
The floating-point string method is str (float), for example: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Here, regardless of the nesting of the print () and type () functions, we will run the result as long as we know that they are outputting the data type of ff: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
(6) The integer to string method is str (int), for example: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
(1) The type () syntax is type (object), which returns the type of the object. We have also used it before, but it is returned internally. If you don't output it, you can't see it, so it is often nested with the output function print (). 

Example: Get the data type and output it. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Run result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Class means type, and it can be seen that f is data of type int. 

(2) isinstance () isinstance () is often used to determine the data type, it returns a boolean value (True or False), and the syntax is isinstance (object, class). 

Example: Determine whether 30.5 is an integer. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Run result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
In Python, expressions are combinations of numbers, operators, numeric group symbols (parentheses), variables, and other objects called expressions. Expressions have fixed literal values. For example, the value of the expression "10 + 20" is 30, and the value of the expression "10 > 30" is False. 

Operators can be divided into four categories. 

(1) General Operators 

>  +，-，*，/（ true division),//(floor division, fractional part is rounded),% (remainder), ** (exponentiation) 

(2) Assignment operator 

>  The commonly used assignment operator is =, and the value to the right of the equal sign is assigned to the left of the equal sign 

>  Enhanced assignment operator ：+=，-=，*=，/=,%=,**= 

Example: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Execution result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
>  Continuous assignment: a = b = c = d = 10 

(3) Boolean arithmetic 

>  == (equal to),! = (not equal to ） >= <= > < 

(4) Logical operators 

>  There are three main categories: not, and and or, also known as non, and or and: if both before and after are true, it is true or: if one is true, it is true not: not true, not false 

Example: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Execution result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
>  I have a lot of technical dry goods in my private stash, and fans can use them for free (click here). 

Flow control is commonly used in the if/else statement of the conditional branch process and the while statement of the loop control. 

Code that only triggers when certain conditions are met. 

(1) Grammar 1 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
The Boolean expression has only two results, either true or false. If it is true, then the code block in the if statement is executed, otherwise it is skipped. 

Example: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Execution result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
From this, it can be seen that the boolean expression (a < b) in the first if statement is true, so the code block print ("true") inside is executed, while the boolean expression (a > b) in the second if statement is false, so the code block inside is not executed, so the word "false" is not output. 

(2) Syntax 2 The commonly used if/else statement has the following syntax: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
The logic of the judgment is that if the boolean expression is true, the code block inside the if is executed, and if it is false, the code inside the else is executed. 

Example: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Execution result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
(3) Grammar 3 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
The logic is that if the boolean expression is true, the code inside the if is executed, and if it is false, the code inside the else is executed. This syntax applies to multiple consecutive conditional judgments. 

Example: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Feel free to enter numbers within 100. The results of numbers in different intervals are different, such as 92. The execution result is: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
(4) Syntax 4 Here we can use the previously mentioned if/elif/else nested to achieve our desired purpose. 

example 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Enter any number, such as 55, and execute the result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
The function of the flow control statement we talked about earlier is still relatively limited. For example, it can only be executed once, and it is a bit troublesome to write a few more to execute multiple times. Therefore, we need to learn the loop statement in the loop process. Its function is to run some code repeatedly. 

(1) While cycle 

Grammar: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
The code block inside is executed as long as the condition (Boolean expression) is true. 

Example: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
After running, you can enter the score multiple times and never stop. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Of course, there is a drawback here. After the code is executed, it falls into an infinite loop, while the code inside is executed all the time, because 4 < 5 is always true. 

So here we can improve the code, don't let it execute forever, let it loop a few times on it, here you can use a variable as a condition to judge, change 4 < 5 to a < 5, and let the self-adding function be implemented in the while. Every time the code is executed in the while, when it is executed to its line, it adds 1, so that it will jump out when it is executed twice. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Execution result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Here I will give you another example to understand the use of the while loop. For example, enter an integer and calculate the sum of each bit, for example, enter 321, then the sum of each bit is 6. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
I entered 2345, and the execution result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
(2) The for loop and the while loop are both loop statements, but the difference is that the for loop is a technical loop. 

Grammar: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Example: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Execute: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
L is a list. We will talk about it later. There are three elements in the list. Every time a for loop is executed, the elements in the list will be assigned to n. Until there are no elements in the list to assign, n will jump out of the list. At this time, the for loop will not be established and the code block in the for will not be executed. 

(3) The range for loop is often used with range, which is an iterable object. The syntax of range is as follows: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
The start value is the start subscript. All elements in the range sequence have subscripts, and the subscript of the first element is 0, so the default is 0. 

Stop is the end position. The end position subscript is (number of elements -1). For example, if there are 4 elements in the range, the end subscript is up to 3, and if it is greater than 3, it will jump out of the range. 

Step is the step size. If step is 2, then each element will be separated by 1. The default step size is 1, that is, each element will be fetched. 

Example: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Execution result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
From the first for loop, it can be seen that the subscript of the first element of range () starts from 0, not from 1; range () can not write the start subscript and step size, but must have an end position; the second for loop can see that the step size can be negative, used for decrement. 

(4) The function of continue continues is to skip this loop and continue the execution of subsequent loops, for example: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Execution result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Obviously, when i is equal to 5, the for loop is skipped, and the code inside is no longer executed this time, returning to a new loop. 

Similarly, there is also the function of terminating all loops, that is, break, which is the same usage as continue, but the effect is different. I will not give an example here. You can try it and find out. 

Lists can hold any data, including integers, floats, strings, booleans, etc., and are one of the commonly used data types. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
The list is subscripted, and the subscript starts from 0. Elements refer to each data in the list. For example, there are 5 elements in l = [5, 4, 3, 2, 1], but the subscript of 5 is 0, and the subscript of 1 is 4. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
For example, get the element subscripted to 1 in the l list: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
The execution result is: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
For example, take all the elements in [1, 2, 3, 4, 5] and output them again: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
The execution result is: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
For example, the elements in [1, 2, 3, 4, 5] with subscripts 2 and 3 are exchanged for data: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Execution result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
![avatar]( 8d865242a3624578b8454d83bf5a974f.png) 

 There are three commonly used methods for adding elements: Uniform usage is: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Example: Add list [6, 7] to another list [1, 2, 3, 4, 5] 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Execution result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
![avatar]( b5c554e3b35945af9d213f148c35aec7.png) 

 Common methods for deleting elements from a list include: Example: Delete the element 4 from the list [1, 2, 3, 4, 5]. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
The execution result is: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
The method of modifying the elements in the list is actually very simple, just use this method directly: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
For example: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Execution result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Slice, as the name implies, is to divide a list into multiple lists. The syntax is as follows: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
For example 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Execution result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
When doing slicing operations, pay attention to the following points: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Execution result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Execution result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
The logical operator and not or is similar to the comparison operator in that it returns Boolean values (True/False). You can try it yourself here. 

The concatenation operator is +, which is often used to concatenate two lists, for example: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Execution result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
The repeat operator is *, which is often followed by a number, indicating that the elements in the list are copied several times, for example: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Execution result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
The membership operators are mainly in and not in, which are used to determine whether an element is in the list and return a boolean value, for example: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Execution result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
![avatar]( 576d011f014a4747a8a2c419f050fc65.png) 

 Other methods commonly used in lists include the following: for example, flipping all the elements in a list 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Execution result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Bubble sort is one of the more famous sorting methods in the list. For example, all the elements in the list [5, 4, 3, 2, 1] are sorted from small to large using the idea of bubble sort. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Execution result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Selection sort is to let elements in the list, and fix the position of one element to be compared with other elements that do not meet the criteria for interchange. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Execution result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
The list can also hold multiple lists, such as the list [[1, 2, 3], [4, 5, 6], [7, 8, 9]], which is composed of a list of two dimensions, one dimension is itself, and the other dimension is the three lists [1, 2, 3], [4, 5, 6], [7, 8, 9], so it constitutes a two-bit list. 

For a binary list, the syntax is: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
For example, output the element with subscript 1 in the first list in a binary list: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
The execution result is: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Here we can see that the outer list in the binary list also has subscripts, and the subscripts are also from the beginning. 

Let's iterate through the binary list again: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Execution result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
>  Fan benefits, click to view 

Progenitor is also one of the common data types in Python. It can be used to store any data type, but it also has its own characteristics: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Example to create a tuple and perform element access and slicing operations on the tuple: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
The execution result is: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
As mentioned earlier, tuples are immutable types and cannot be modified, but they can be modified and deleted by converting the tuple into a list, and finally converting the list into a tuple to complete the modification and deletion of the tuple. 

For example, modifying the elements in a tuple 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Execution result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Deleting elements in a tuple can be done with the del t [subscript] method, provided that the tuple is converted to a list first, for example: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Execution result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Tuples also have operators, and the methods are the same as those of lists. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Example: Determine whether 5 is in the tuple. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Execution result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
![avatar]( 04ff350e743142a4ae790baea1e65f4d.png) 

 The method of tuples is the same as the method of lists introduced earlier. Here is a review of the common methods of lists: the use of these methods is still the variable name. method mentioned when following the method of lists. In addition to the above, there are 2 more methods worth adding: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Example: Count the subscript of 3 for the first occurrence in a tuple (1, 2, 3, 4, 5, 3). 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Execution result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
In Python, there is no difference between a character and a string. Some students may have learned other languages, for example, Java, in Java, the single quotation mark'a 'represents the character'a', and the double quotation mark "abc" represents the string "abc", but in Python, they are all referred to as strings. 

String has the following characteristics: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
![avatar]( 7cced20a978f401da1a172c71de43b62.png) 

 Common methods for string are as follows: Example: Capitalize the first letter of the string "hello world". 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Execution result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Formatting output refers to the output of strings in a certain format, commonly used methods are format and $%. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Example: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Example: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Execution result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Example: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Execution result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Example: Outputting a multiplication table with% s combined with a loop statement 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Execution result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
It is worth noting here that\, which has many clever uses, for example, when you have more things to write on the same line, it is not visually beautiful. You can use backslashes to visually wrap the line, but the previous line and the next line are logically the same, for example: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Execution result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
>  Fan benefits, click to view 

A dictionary is used to store data, and the data in the dictionary is stored in a mapping relationship. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
For example: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Execution result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
This is a tuple, where one is the key, 1 is the value, and'one ': 1 is the key-value pair. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
For example: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Execution result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
For example: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Execution result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
The main methods commonly used in dictionaries are as follows: 

![avatar]( 30fca7d4fa124210a4de42a41ae88794.png) 

  Example: Returns all values in the specified dictionary 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Execution result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Regarding dictionaries, there are some small points for you to add: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
A function is a set of code that performs a specific function. 

The syntax for creating a function is as follows: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Parameters are equivalent to variables. Parameters can be one or more, separated by commas, and can also have no parameters, equal to no parameters. Code blocks are implementations of functions, also known as function bodies. 

function call 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Functions operate according to the following mechanism: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Example: Use a function to print the ancient poem "Climbing the Stork Tower" line by line, and add a dividing line composed of multiple identical symbols below each line. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
Execution result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
As can be seen from the above example, functions have the following characteristics: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
The parameters of a function must first understand the following three concepts: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
![avatar]( 3b929823004c4b299a63b080ebc1b994.png) 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
![avatar]( 4d475d61479e4d52a9ed48d71a2fa284.png) 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
![avatar]( 235f4d32832d4ca6afa0dc59dcd3e67a.png) 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
![avatar]( f0bca07a00ae432eae1dc0a1a87b7feb.png) 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
![avatar]( 53aa2afa53234a1cb2dabfd1ea775cd1.png) 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
![avatar]( c36f9399adc94c06ba274875f7dd25a8.png) 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
![avatar]( 5f2979693c4f4f3b8f4f6f95c1c7c6d9.png) 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
![avatar]( df5ae828c8b746268cffa3139c7382d5.png) 

When writing code, we often need to write documentation. We have mentioned that #and three quotation marks can be used to comment the code, but here we want to introduce a new method, which is also a commonly used function documentation format when writing code: In the first line of the function body, use “”" “”" to document, which is a standardized function documentation. 

For example: 

![avatar]( 789c89b532e2483cb25d62a8cb0dde58.png) 

  After you have the function documentation, you can obtain the documentation content of the function by: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
![avatar]( 4718b4ff7edf4ecd900046738213e9b1.png) 

 For example, in addition to this, you can also use help (function name) to view the function documentation, for example: 

![avatar]( 692ba8af3449468d8604591fedf55830.png) 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
First, you need to understand two concepts: local variables and global variables. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
![avatar]( 2c467e4671124fb186ad729fc9f541eb.png) 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
![avatar]( 13e75edcca8b45159f10b75293071632.png) 

The function defined inside a function is called an inline function (or an inner function), and the scope of the inner function: from the beginning of the definition to the end of the code block contained to him cannot perform operations such as a += 1, a = a + 1 in the inner function. The solution is nonlocal and global. 

![avatar]( 970fedf74e0f4420bca37b9a07a2210e.png) 

 For example:  

Closures are an important syntax structure of functional programming. 

Programming paradigm: A programming paradigm that refines and abstracts code to make it more reusable 

If the inner function calls a local variable of the outer function, and the outer function returns the function object (function name) of the inner function, for example: 

![avatar]( a28ccbfa7d404a828b7baae6db1ea003.png) 

  This results in closures, which can pass fewer parameters and more arguments - safer, more indirect access to internal functions, such as: 

![avatar]( 387865931a7848b782ca5a8f3b922c76.png) 

  Of course, closures are conditional. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
After learning these basics, what do you think of your level? Did you just float over like this? To be honest, there are not many things you can do after learning these basics. The fun things can only be made after getting started. 

But here in Uncle Long, there are still comprehensive projects. According to the basic knowledge of loops, lists, functions, etc., as I mentioned above, you can try to write a comprehensive project to test your knowledge. You can try to write a simple business card management system. 

1. The program starts, displays the welcome interface of the business card management system, and displays the function menu 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515798
 ```  
2. The user selects different functions with numbers 3. Perform different functions according to the function selection 4. The user's business card needs to record the user's name, phone number, QQ, and email 5. If the specified business card is found, the user can select, modify, or delete the business card 

After roughly understanding the requirements of this operating system, let's not busy looking at the code first. Let's take a look at the effect of the code after it runs. This is what we need to do: 

I won't put the video here. The article with the video will automatically play when you open it. This is a bit speechless, especially for long articles like mine. Where can't you find the video after searching for a long time? Hahaha... So let's put the link to the video demonstration for everyone! 

Video effect link: https://www.bilibili.com/video/BV1aZ4y1F7n6/ 

Next time I will publish a special article about this business card management system project. Now you can try to write it yourself for the time being. You can also ask me for a private chat with the source code. 

>  [Python beginner tutorial column] 

![avatar]( 33fa428e5d4b418fb3f15930f1bfcda9.png) 

