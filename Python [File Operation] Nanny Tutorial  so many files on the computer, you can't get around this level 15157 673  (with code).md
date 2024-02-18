###  😏foreword 

When writing code and doing projects in Python, we often need to operate on multiple files. How to import other files in the current source code file? How to operate on other files? This is a common problem, especially for crawlers. Where is the data crawled to? How to call it out when used? 

This involves Python's file manipulation knowledge. We can't always do all the operations on a single source file. This is also a knowledge section that must be mastered. 

At the same time, my Python beginner tutorial series is almost complete, and everyone is welcome to subscribe. 

>  Python Beginner Tutorial Series Article Column 

![avatar]( 60d9532e954748d9a71306873f8c43d3.png) 

###  💼First, the definition and operation of the file 

Computer files usually refer to the collection of information stored on the computer's hard disk as a carrier, mainly in the form of video, audio, pictures, and documents, such as executable files.exe, document file.txt, web file.html, and so on. 

![avatar]( fa8b9443bedc46acab1a7623bdf75635.jpg) 

>  I have a lot of technical dry goods in my private stash, and fans can use them for free (click here). 

###  💼Second, the basic operation of the file 

In reality, our operations on files can be roughly summarized as "open → operate (read, delete, modify, etc.) → save → close", which is still the case in Python. Before starting file operations in Python, let's learn a few methods. 

1.open (name, mode) ---- Open file 

This is the Python method of opening a file, which is used to open a file and return a file object. 

Name refers to the file name, which must be written in full. What is written in full? It is to write clearly, storage path + file name + suffix. 

Why do you need to write so much? Because even under the same storage path, there may be more than one file with the same file name. As long as the suffix is different, the computer allows the existence of files with the same name, so if you don't write it all, the computer doesn't know who you are referring to 

Mode is the mode to open the file. The default is r, which is the read-only mode. There are many modes of mode, such as reading, writing, etc., which we will talk about later. 

2. write ("content ") ------ write 

As the name suggests, it is to write content to the file object. 

3.read () ------- read 

To write content to the file, you can write numbers in parentheses or not. If you don't write, the default is to read the entire content. Writing numbers means reading X characters. For example, read (6) reads 6 characters of the file object. 

4. close () ------ close the file 

The method of closing the file, if you do not close the file after the file operation, the file will always be open and operated on, which will consume memory. 

5. Cases 

After understanding these 4 basic methods, let's start with a small case: create a new project, then create a Python file named "file" for writing code, and then we write "hello world" to a .txt file called "file 1" by writing. The code is as follows: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574526944
 ```  
As mentioned earlier, the open () method returns a file object, so let's use f to receive it. This is the pre-run interface: 

![avatar]( d64a8cb2968b4ab58c15f0fbe2932ff9.png) 

After running: 

![avatar]( 55c5386c2faa4583a1b32ff4bae272c7.png) 

>  I have a lot of technical dry goods in my private stash, and fans can use them for free (click here). 

After running, a new file named "File 1.txt" is generated, and after opening it, we can see what we entered. When writing, if the file does not exist, one will be created by default. 

Similarly, we can also perform read operations on this file: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574526944
 ```  
Run result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574526944
 ```  
This is the most basic file operation process. 

It should be noted here that when open (name, mode) is written at the beginning, mode already determines what operations you can do, that is, if you start writing code with: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574526944
 ```  
Then if you want to write () later, an error will be reported, because the r read-only mode is declared in mode, so you do not have write permission. Please pay attention to this. 

6. other modes of operation 

There are many operation modes in mode, let's take a look at them in a table: 

The pointer can be understood as a cursor here. Where it is, your operation begins. 

For example, create a new .txt file named "test", write aaa to it for the first time, and write bbb to it for the second time. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574526944
 ```  
Run result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574526944
 ```  
###  💼III. Methods and properties of the file 

1. Object properties of the file 

There are three commonly used methods for viewing the properties of file objects: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574526944
 ```  
Example: Operate on the file (at will), check the file name, operation mode, and whether to close it. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574526944
 ```  
Run result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574526944
 ```  
2. Object method of file 

There are many file methods, such as read () and write (), but there are still some common methods to master, such as the following: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574526944
 ```  
Example: Write aaabbbccc to the test.txt file and output the contents of the file as a list. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574526944
 ```  
Run result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574526944
 ```  
###  💼IV. OS module 

The os module is a module used to access the operating system, and it is often used when performing file operations. Modules need to be imported before use. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574526944
 ```  
1. Regarding the function of the file 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574526944
 ```  
Example: Existing file test1.txt, modify it to test20.txt. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574526944
 ```  
Run result: 

![avatar]( 62246f9d25b64e0e9674be061771ca3b.png) 

2. Functions of folders 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574526944
 ```  
Example: Create a new folder in the existing folder venv. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574526944
 ```  
Run result: 

![avatar]( b0baa7788daa48cab2871b139e230dfa.png) 

###  🎓Conclusion 

There are actually many methods for files. When using it, you can go to the Internet to check the information to gain a deeper understanding. For example, there are other methods in the os module. We can ctrl + left mouse button to enter the module to view, for example, not only the os module, but also the os.path module is also a more commonly used file operation module. 

Then today's sharing will stop here first. After reading it, you can collect it and practice more, and the file operation will no longer be difficult. 

>  I have a lot of technical dry goods in my private stash, and fans can use them for free (click here). 

