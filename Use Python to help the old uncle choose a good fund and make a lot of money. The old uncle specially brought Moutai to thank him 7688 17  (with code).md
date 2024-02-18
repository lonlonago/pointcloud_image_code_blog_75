I have an uncle who likes to buy funds very much, because he doesn't want to be cut off, so he didn't enter any group, and he carefully selected them all. 

Looking at one of his notebooks densely written a lot of things, all of which were fund data analytics, it was not easy at a long age, so I decided to help him. 

After talking to him in detail about the situation of buying a fund (because I don't understand this), according to his request, I used Python to directly select the good fund he wanted to buy. 

In the past few days, he specially came to my house to thank me, and he also specially mentioned 2 bottles of wine, because in the list of funds I screened for him, the funds he bought after selecting have already made a profit, and some of the principal is still left in it. 

![avatar]( a35931f78f954a5c9b8422c34270f03c.png) 

If you also have friends who like to buy funds or stocks, you can also provide them with some technical support in this way. 

###  First, the goal 

The purpose is to select the top 20 funds that meet the current conditions from Tiantian Fund Network. I will clarify the specific screening conditions in the following steps. 

###  The development environment 

###  III. Steps 

1. Obtain fund ranking information and use the four-four-three rule to screen the top-ranked funds 

There are fund rankings on Tiantian Fund Network, which can be crawled and screened with a Python crawler. The four, four, three, three rule is to select funds that rank in the top quarter in 3 years/2 years/1 years and in the top third in 6 months/3 months. 

![avatar]( 16a090ed92c14b26aa02ad50a5e32ffa.jpeg) 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574581119
 ```  
The return value is as follows: 

![avatar]( 967dfaf19cfb4196aa9916c0be15f57c.jpeg) 

Tips: The above content actually only needs the value after datas. In this example, you can see that there are 5053 funds in the last year. Then a quarter of the ranking is 25% * 5053 = 1263 funds. (The return data has been sorted from high to low, and the top n funds can be extracted.) 

![avatar]( 115754a53eb442c385d67d7ec13f8184.jpeg) 

This way, the data is extracted. Of course, it is only partial, and it needs to be cycled to complete the data. 

The data in dataframe is like this. 

![avatar]( 25420e136cfe425a9c1a6cf9f046821c.jpeg) 

2. Obtain the basic information and Sharpe ratio of funds online, and screen out funds with high Sharpe ratio. 

A total of 171 funds were selected through the rule of four, four, three and three, and the screening needs to continue. The goal is to select 20 funds from 171 funds, and the rule is that funds with a high Sharpe ratio with more than 100 million funds. 

Also get the capital scale and Sharpe ratio from Tiantian Fund Network. The URL is as follows: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574581119
 ```  
![avatar]( d4797b8ce1e846c3b2722509826a5691.jpeg) 

Then let's look at the printed dataframe (screenshot of some information) 

![avatar]( 1e368648ea8343b883ea6323148063ed.jpeg) 

 ![avatar]( 89ac3d374564451db0c916c8aca7168e.jpeg) 

![avatar]( 67b5dc3fc51444b19b271b5c33640178.jpeg) 

Combine the above two dataframes: 

![avatar]( 13b941362e3b487f8f56266d0fb57272.jpeg) 

Multiply the 3-year/2-year/1-year/6-month/3-month ranking by the weight (0.3/0 25/0.2/0.15/0) to calculate the comprehensive ranking and sort it. Take the top 50 data. 

![avatar]( 8de4ce9d79db43d7917ef5ff5c4af604.jpeg) 

Take the top 20. 

![avatar]( b3cda86488494ef69846a255a2e759b4.jpeg) 

Export to csv format file (Excel-like file) 

![avatar]( 6683c3e57e7e45f0804b007faf55f4a9.jpeg) 

 ![avatar]( 6bfc5b0df30247babe1a092edd5a176f.jpeg) 

After the above steps, the best list of the top 20 funds was successfully selected. I wish you all the best. 

###  Conclusion 

Remind the following everyone that this is only more time-saving, labor-saving and accurate than manual analysis and judgment. After obtaining the data, you must have professional knowledge to analyze it before you can get the answer. 

![avatar]( eb24529a16784346925d243df9109f60.jpeg) 

 I also like Python very much. I have collected a lot of technical dry goods, which can be shared with friends who like my articles. The dry goods include: Click on the business card at the end of the article to take it away. 

![avatar]( 2c7e6d16f04e4df3b3a7ddd7e41c457e.gif) 

