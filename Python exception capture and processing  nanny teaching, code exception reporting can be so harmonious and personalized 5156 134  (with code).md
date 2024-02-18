###  👀foreword 

It is normal for the code to have an exception and report an error, but why handle an exception? 

Due to the existence of exceptions, a large number of red font prompts will appear when the code is running, which is good for programmers. They are used to reporting errors in red, but if you develop something for others to see, then people who do not understand the code will be confused and have a bad impression of the product. 

For example, we often lose a simple webpage, which is actually an abnormality in the execution of the webpage code, but some webpages are still very personalized, and the prompt information may be more user-friendly. For example, CSDN has deleted your favorite articles in the background, causing the code that jumps directly to this interface to fail to execute. The error message at this time is as follows: 

![avatar]( 2efbc66ce5fb4a329dd7c3fd8f70d441.png) 

But some products are not so thoughtful during development, without understanding the user's feelings. As a result, a certain program malfunctions, and users can see a bunch of error codes, causing their popularity to plummet. 

![avatar]( 2474d993e7f24ba698d240a5cc9fd7f5.png) 

First of all, the exceptions mentioned in this article do not refer to teaching you how to make the code not report errors. Code exceptions must be debugged to solve them. This is not our focus here. Today's focus is on optimizing and personalizing where the code may report errors, so that the errors look more harmonious. 

Secondly, this is also an important part of the Python beginner tutorial series, which can lay a good foundation for exception handling in future development. There will always be exceptions in the code, but some exceptions do not seem to violate others. This is all due to having a solid foundation in exception capture. 

![avatar]( d00a27a76e824c4a9f1807f4f93c8086.png) 

###  ⚡First, the definition of an exception 

An exception is an event that occurs during the execution of a program and affects the normal execution of the program. In general, an exception occurs when Python cannot handle the program properly. 

For example, I only wrote one variable a in the code, and when I run the program, pycharm cannot recognize this variable, so an error is reported, indicating an exception. 

![avatar]( 8adc7d465fbd4c0bb2e8ceea29f1a878.png) 

###  🙊Handling of exceptions 

Therefore, we need to master the methods of handling exceptions. There are many ways to handle exceptions. Let's take a look at them one by one. 

It can process the code that may be wrong, and the red font that reports an error after processing will be converted into a short, normal font, which is used as follows: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574520728
 ```  
Example: Direct printing of variable a will generate an error. 

![avatar]( 6c531a7ed4c843c6b2460d778fc0246c.png) 

After tyr-except processing: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574520728
 ```  
Run it again to see the effect: 

![avatar]( 468ad28097274201a57c698debd24f06.png) 

The red error message has become shorter and the color is normal. Does this abnormality seem more comfortable? 

Here, tyr-except does not affect the execution of the code. If your code does not report an error, even if you write tyr-except, it will only execute the try line of code. If there is no error in that line of code, it will not execute the code inside except. 

For example, let's take a normal one: 

![avatar]( 9e011e9756a545d8b5644cbbf33c853a.png) 

This method is similar to the previous try-except writing method, except that an except is added later, which can be used to determine a variety of possible error situations. 

For example, there are two lines of code that might report an error, two different types of exceptions, but don't want it to go viral. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574520728
 ```  
Run result: 

![avatar]( 5b766e0b98924f0abdc82426c29abaee.png) 

Although the error is reported, there is no red. Here, pay attention to the two ways of writing except. 

The try-except writing method is very flexible. We can also use tuples to include exception types that may report errors to avoid writing multiple lines of except, for example: 

![avatar]( 70ff6fd15fe5432db08b0e8ba3ec6205.png) 

If there is no exception, execute the code in else, for example: 

![avatar]( b5048b15d48440da8180452e195a8d67.png) 

No matter whether the code has an exception or not, the code in finally will be executed at the end. For example: 

![avatar]( f310461c763648de917ff645cd8d1d2a.png) 

In fact, you can not add the error type after except, because the system will default that the error behind is of type Exception, which is a top-level class that contains all error types. 

![avatar]( 4cb0a47e6ae14b8781ea9af7bed1ab65.png) 

###  🙈III. Custom exceptions 

Have you found that when we went to do basic exception capture earlier, we had to write a try-except every time there was a possibility of error. What if there were multiple possible errors? Do we need to write multiple try-except? Or theoretically, the code can run, but I want to set a rule that any behavior that does not meet my rules will cause an exception. For example, if the password length exceeds the length specified by me, I want the program to cause an exception. 

Custom exceptions can be used to raise an exception (throw an exception), which is raised by the keyword raise. 

For example, to simulate the situation where a user enters a password, the password entered by the user cannot be less than 6 digits. Customize an exception to detect whether the password entered by the user meets the regulations. If it does not meet the requirements, an exception will be raised, indicating that the current password length and minimum password length cannot be less than 6 digits. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574520728
 ```  
Run result: 

![avatar]( f0f44fd55d2642c7ab58374a3b2dfc21.gif) 

From the above code, we have used the knowledge of classes and instance objects in the previous object oriented section. If you forget it, please review it quickly. In addition, we also combine the previous try-except and our keyword raise to cause exception capture. 

##  💤Conclusion 

The above is the basic method of exception capture and handling, which can be combined with more knowledge to more flexibly capture and optimize exceptions. Nowadays, it is rare to see products that report errors in code but are presented to users intact, indicating that everyone still attaches great importance to exception handling, so this piece of knowledge is also a must for developers. 

>  My official account has finally come out after some preparation. The official account will have all my technical and experience articles, because the types of articles supported by each platform are different, so some articles may not have been seen by you. Welcome to check them out. 

