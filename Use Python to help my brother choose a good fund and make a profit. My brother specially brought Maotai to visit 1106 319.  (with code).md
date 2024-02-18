A few days ago, a brother who liked to buy funds was worried about how to buy funds. He had no tools and no skills. He was afraid of being harvested as a chive when he entered the fund group, but he felt itchy if he didn't buy it. After buying it for more than ten years, it was risky to choose by himself... 

Looking at one of his notebooks, he wrote a lot of things densely, all about fund analysis. It was not easy at a long age, so he decided to help him. After talking to him in detail about buying funds (because I didn't understand this), according to his request, I used Python to directly select the good fund he wanted to buy. 

In the past few days, he specially came to my house to thank me, and he also specially mentioned 2 bottles of wine, because in the list of funds I screened for him, the funds he bought after selecting have already made a profit, and some of the principal is still left in it. 

![avatar]( 20210604140450713.jpg) 

Today, I will share with you how to choose a good fund with Python, hoping to help some friends who like to buy funds. 

###  I. development environment 

![avatar]( a861862e6c82f81b4b1b20eb20d47958.png) 

 ###  

###  Steps 

1. Obtain fund ranking information and use the four-four-three rule to screen the top-ranked funds 

There are fund rankings on Tiantian Fund Network, which can be crawled and screened with a Python crawler. The four, four, three, three rule is to select funds that rank in the top quarter in 3 years/2 years/1 years and in the top third in 6 months/3 months. 

![avatar]( e0a9e8ebb18c7d3348522e8b01c9cdaf.png) 

The return value is as follows: 

![avatar]( 63da4754837944840b83433aae797d1a.png) 

Tips: The above content actually only needs the value after datas. In this example, you can see that there are 5053 funds in the last year. Then a quarter of the ranking is 25% * 5053 = 1263 funds. (The return data has been sorted from high to low, and the top n funds can be extracted.) 

![avatar]( adc229057e74bd8dc838b264e64b38a6.png) 

![avatar]( 25abce1bb685e675a7da0347e2f69133.png) 

This extracts the data. Of course, only part of it. You need to loop to complete the data. The data in dataframe is like this. 

![avatar]( 20fa73912da6284ffffb9dd111470dfc.png) 

2. Obtain the basic information and Sharpe ratio of funds online, and screen out funds with high Sharpe ratio. 

A total of 171 funds were selected through the rule of four, four, three, three. Continued screening is required. The goal is to select 20 funds from 171 funds. The rule is funds with a high Sharpe ratio with more than 100 million funds. 

Also get the capital scale and Sharpe ratio from Tiantian Fund Network. The URL is as follows: 

http://fund.eastmoney.com/f10/006279.html 

http://fund.eastmoney.com/f10/tsdata_006279.html 

![avatar]( a08aa76b192f4057dc04c9b067607ae9.png) 

![avatar]( e0960c6778642229e9ab59ea34daf2c9.png) 

![avatar]( 77503876a5be6ebe5add8d22fad01943.png) 

![avatar]( fed20abaf331a87f95465557d3f83c92.png) 

![avatar]( fa4ec76086570d4a564907b2aeece89f.png) 

Splice the above two dataframes 

![avatar]( 6207b0c802870b24766b350ef1b1b59f.png) 

Multiply the 3-year/2-year/1-year/6-month/3-month ranking by the weight (0.3/0 25/0.2/0.15/0) to calculate the comprehensive ranking and sort it. Take the top 50 data. 

![avatar]( f2059199c0078521f4aadaf032f658cc.png) 

Take the top 20. 

![avatar]( b6486f74c1dafbc0213dd612e33199d7.png) 

Export to csv format file (Excel-like file) 

![avatar]( 4bf37be11cc204b7ce56d5383479cf83.png) 

![avatar]( 53caa5b2e8b47bd3b505b1d1b508e4cc.png) 

After the above steps, the best list of the top 20 funds was successfully selected. I wish you all the best. 

However, I still have to remind everyone that this is only more time-saving, labor-saving and slightly more accurate than manual analysis and judgment, but it is not ruled out that the data will also deceive people. It is difficult to say that what you see is arranged by others. Investment is risky, and you need to be cautious when entering the market. 

![avatar]( 20210511152217670.jpg) 

This is the end of the article. Thank you for watching. I just have something to say to my readers. 

I have been learning how to write articles since I retired. To be honest, every time I see some readers' responses in the background, I feel very relieved. I am a newcomer to self-media, and I am still a middle-aged uncle. To thank the readers, I would like to contribute some of my collection of programming dry goods to you and give back to every reader. I hope it can help you. 

Dry goods mainly include: 

① More than 2,000 Python e-books (both mainstream and classic books should be available) 

② Python standard library information (the most complete Chinese version) 

③ Project source code (40 or 50 interesting and classic practice projects and source code) 

④ Videos on Python basics, crawling, web development, and big data analytics (suitable for Xiaobai learning) 

⑤ Python learning roadmap (bid farewell to undercurrent learning) 

If you can use it, you can take it away directly. In my QQ technical exchange group (technical exchange and resource sharing, advertising will break your legs), you can take it away by yourself. The group number is 553274211. 

![avatar]( 20210511152327755.png) 

