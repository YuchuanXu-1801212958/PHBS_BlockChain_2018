# PHBS_BlockChain_2018
## **Regression Analysis of Factors Affecting Bitcoin Price**
### Yuchuan Xu      ID：1801212958 
  




## **1 Introduction**

As a very important role in human history, money has been accompanied by the development of human civilization, even to a certain extent, a milestone in the development of human civilization. From physical money to weighing money, from paper money to electronic money and digital money, money itself is constantly evolving. On October 31, 2008, a white paper on the design of bitcoin titled "Bitcoin: A Peer-to-Peer Electronic Cash System" was published at the Cryptography Forum by a person who assumed the alias Satoshi Nakamoto. The source code for the implementation of Bitcoin was released in 2009, and the world’s first Bitcoin was born on January 3, 2009, which is also the beginning of the new world of Internet digital currency. Despite many controversies, block chains and Bitcoins, which represent block chains, are still milestones in the development of information technology.

Bitcoin is a digital currency based on the Proof of work Mechanism (PoW). Miners who do bitcoin mining need to use computer CPU/GPU computing power to continually crack one specific problem to obtain rewards. That is a certain amount of bitcoin, this is the mining process of Bitcoin [2]。In the process of solving problems, computing power has become a decisive factor in the calculation speed. The greater the computing power is, the greater the possibility of miners to have priority in the calculation results. Therefore, it will cost a lot of money to participate in mining with PoW mechanism. This also guarantees the security of Bitcoin network to a certain extent, because deliberate attackers have to pay a huge cost, and the cost will increase with the total amount of computing power of miners in Bitcoin network. Because of the algorithm, there are about 21 million special solutions, so the upper limit of Bitcoin is about 21 million. This is very similar to gold mining in real life, and the amount of gold in the earth is limited. At the same time, the difficulty of obtaining special solutions can be changed to control the number of Bitcoins that can be excavated efficiently and conveniently. Because the computing power determines the possibility of mining success, the competition between miners mainly focuses on the performance and quantity of mining machine. In today’s mining market with considerable scale, the mining efficiency of independent miners is not enough. In this case, the pool of joint mining emerges as the market requires. Bitcoin mining has also risen from personal work to group cooperation [3].

In Bitcoin trading, both parties need to have "Bitcoin Wallet" and "Bitcoin Address". At present, due to the existence of the Bitcoin Exchange, both sides of the transaction can use mobile phones or personal computers to log on to a Bitcoin trading platform for trading. Online purchase through Bitcoin trading platform is an important channel to acquire Bitcoin. Most of the functions of purchase and discovery can be realized in Bitcoin trading platform. From the data of the major trading platforms in the country, the current amount of Bitcoin transactions is 100,000 per day, which is a good proof of the transaction value of Bitcoin and the possibility of Bitcoin being used as currency in daily life [4,5]. Nowadays, the price trend analysis of the stock, bond, futures, real estate and other investment targets has been relatively comprehensive and mature, but in contrast, the market price of digital currency such as Bitcoin still has a lot of room to explore. Recently, the price of digital currency has also received great attention of the whole society, and the analysis of the price of digital currency has become an urgent need of today’s society, and will also give great help to investors of digital currency. The price analysis of digital currencies, such as Bitcoin, refers specifically to the analysis of changes in asset markets and the factors affecting their prices. However, the existing problem is that at this stage, we are all based on "positivism" to analyze the price of digital currencies, such as Bitcoin, namely "technical analysis". Some people used economic analysis tools such as formula mathematic model, trend extension line and so on, which are similar to stock analysis. But in fact, in the digital currency market, the accuracy of price prediction by price mathematic model is not high [6].

In the society, speculation is inevitable, and speculation is accompanied by the long history of capitalism. Historically, speculative assets have a common feature, that is, the difficulty of valuation. The South Sea Co bubble and the tulip bubble in Holland reflect the impact of human greed on speculative speculation. At the same time, it is difficult to determine the objective value of assets, and all speculative activities are reflected in the hyperexponential growth of time series [7]. Recently, due to human speculation, the price of digital currencies such as Bitcoin has fluctuated dramatically. If we ignore the human factors in the price analysis as before, it will make it impossible for us to really analyze the price changes of digital currency. I will combine "positivism" and "anthropology" to represent the digital currency market with Bitcoin. It makes a rational and comprehensive analysis of the changes of Bitcoin market and the influencing factors of its price. Firstly, I will analyze the price fluctuation of Bitcoin through investigation, and summarize the main price basis of Bitcoin in the emergence stage. Secondly, we study the current situation of Bitcoin market and present our thinking and hypothesis about the price of Bitcoin. Finally, through empirical analysis of a large number of data to draw regression-related conclusions.


## **2 Research status of bitcoin**

Bitcoin, or block chain technology itself, is the greatest help to human society is to solve the problem of trust between people, people’s distrust of the government and people’s distrust of the economic system, which is particularly evident under the stimulus of the 2008 financial crisis. And Nakamoto put forward a de-centralized point-to-point electronic currency, without a third party, and constructed a new trust system. So, for Bitcoin, the main problem at present is whether it can be regarded as a universal currency, which is mainly determined by whether it has the basic function of currency and the relationship between Bitcoin and other currencies.

Whelan (2013) argues that Bitcoins are similar to the dollar because they do not seem to have real intrinsic value, or only limited value, but are used in life as a medium of exchange. Lo and Wang (2014) and Baur et al. (2017) consider the function of money. The basic function of money includes the medium of exchange, the unit of account and the storage of value. Bitcoin has some deficiencies in these aspects, such as the convenience of its transaction is not enough to meet the standard of general currency. In Bariviera et al. (2017), Bitcoin does not have the basic function of money, because it fluctuates greatly, even more than the currencies of some small countries. Roverds and Velde (2014) analogized Bitcoin to the old gold and silver bills and bills of exchange, which existed as money during the financial revolution of 1688-1756.If Bitcoin is regarded as a currency, it should also be affected by interest rates, similar to other currencies, so it has been examined from this level.

Dyhrberg (2016) based on GARCH model tests whether there is a correlation between Bitcoin returns and the Federal Fund Interest Rate. Because the dollar will appreciate as fund interest rates rise, this will lead to an increase in imports, and because of Bitcoin’s advantages in Transnational Online transactions, the demand for Bitcoin will increase, so the return on Bitcoin investment will increase. At the same time, it also reflects that Bitcoin performs well in the function of trading media, which means that Bitcoin and currency have certain similarities.

Secondly, another characteristic of money is that it is influenced by other countries’ currencies. Szetelaet al. (2016) inspected the relationship between Bitcoin and the currencies with great influence, such as US dollar, Euro, British pound and RMB. Based on ARMA and GARCH model, the conditional mean and conditional variance of Bitcoin were selected as data. It was found that conditional mean and conditional variance had nothing to do with other currencies, but conditional variance had a certain correlation, which indicated that Bitcoin was not complete. From this point of view, we can prove the monetary attribute of Bitcoin, which is totally independent of other currencies.

Bouoiyouret al. (2016) believes that the price of Bitcoin is affected by many factors, including supply and demand, exchange volume, circulation rate and Bitcoin output. Others argue that in the long run, supply and demand are the most important factors affecting the price of Bitcoin (Buchholz et al. (2012)).Van Wijk (2013) believes that the price of Bitcoin is closely related to the development of the global financial market, and the prosperity of the financial market determines the change of the price of Bitcoin. In addition, Ciaianet al. (2016) and Bouoiyou and Selmi (2015) found that real transactions and exchanges made Bitcoin holdings more meaningful, which caused the price of Bitcoin to rise. Ciaianet al. (2016) considers many factors as data at the same time, including traditional factors such as supply and demand, and the specific factor of Bitcoin’s attractiveness to investors. Using data from 2009-2015 and using time series analysis, the results of the study found that the power of supply and demand, the attractiveness of Bitcoin to investors and users all have a significant impact on bitcoin prices, but the impact also changes over time.

In the short term, Bitcoin prices fluctuate greatly. It is generally believed that there are many factors that affect its price, such as Twitter, Google search and other factors. Bouri et al. (2017) found that in terms of the impact of news on Bitcoin, the impact of positive shocks was greater.

Thereafter, the study on the price of Bitcoin should focus on the following aspects:

+ (1) The unique trading mechanisms of Bitcoin and other digital currencies, including 24-hour continuous trading and the co-operation of several large exchanges, may lead to different measurement methods in the study. At the same time, the frequency of data selection should also be carefully considered. At present, most studies use Bitcoin daily data to study in terms of date, but because of the 24-hour continuity of its transactions, such segmentation may lead to the loss of internal information. At the same time, choosing different intervals may lead to different results.

+ (2) Although current research shows that the price of Bitcoin has nothing to do with the overall situation of the financial market, because Bitcoin currently mainly covers the field of science and technology, it may be related to the development of specific sectors related to science and technology. In the current financial market, under the background of the hot concept of the block chain, the stock prices of companies involved in the block chain have risen considerably. Most of them are technology companies. Therefore, even if it has nothing to do with the overall financial market, it can not be ruled out that Bitcoin is related to technology and other related sectors.

+ (3) As a kind of digital currency, Bitcoin still occupies a large proportion of the market share in the current situation of a large number of digital currencies, but it still has the possibility of interacting with other kinds of digital currencies, so it is necessary to study this aspect.

+ (4) Bitcoin has developed many other applications from the most important application of block chain technology as the foundation, and the emerging technology of block chain technology combined with other technologies has invaded the proportion of special currency in digital currency. This situation Bitcoin is facing is bound to have a negative impact on special currency, but this situation is in the process of development. 

+ (5) Because many investors are hoarding Bitcoin and other digital currencies and waiting the price of these digital currencies to rise, because the total amount of Bitcoin is limited, this will inevitably lead to deflation effect, which is obviously not conducive to the continued development of Bitcoin. Therefore, it is necessary to build a more complete life cycle asset allocation scheme to break the current unhealthy investment mode. With the continuous expansion of market value of digital currencies such as Bitcoin, this phenomenon needs our attention and urgently needs to be solved.

+ (6) At present, digital currencies such as Bitcoin have also developed some derivatives, such as Bitcoin futures trading. The ecology of these derivatives is also worth studying, and the impact of these derivatives on digital currencies such as Bitcoin itself is also a question worthy of careful consideration.

## **3 Bitcoin price fluctuation analysis**

The three main characteristics of money are the medium of exchange, the value of storage and the unit of account. According to economic history, money is closely related to power and politics. At first, money was made of metal, and the value of metal itself was the value of money. Later, money was printed on paper, and its value was somewhat related to the amount of gold and endorsed by the government.[8,9] Money itself has value, so it can serve as a measure of value. There is a lack of research on the value of Bitcoin in the market. At the same time, Bitcoin has not formed a consensus in the current society. Therefore, we can regard Bitcoin as a commodity to analyze its price and the factors affecting its price.

### **3.1 Bitcoin price estimates and constraints**

First of all, we must think of the most fundamental technology of Bitcoin. Block chain technology essentially solves the classical Byzantine general problem well, and achieves the consensus of the whole network without any central nodes, i.e. under the distributed situation [10,11]. Block chain technology solves the trust problem in distributed scenarios. The PoW mechanism is the main algorithm and means to achieve efficient consensus. PoW mechanism [12] makes block chain transactions non-fictitious and non-tampering. The core idea of PoW mechanism is to calculate a special solution through competition among distributed nodes (miners). This solution is a complicated but easy to verify SHA256 mathematical problem. The miners who solve this special solution fastest have the right to account for the block, and will get a certain amount of bitcoin reward. At the same time, the block will be counted into the longest blockchain[13-15]. This also means that the miners involved in the PoW mechanism will pay a lot of calculation costs.

The cost of Bitcoin mainly comes from the price of mining equipment, the power cost and the consumption of manpower. At the same time, the cost of Bitcoin is not unchanged. With the continuous optimization of the performance of mining machines, the operation cost is decreasing. However, due to the increase in the number of mining equipment and the upgrading of technology, the difficulty of Bitcoin mining needs to be adjusted. The production speed of bitcoin holders has led to a decrease in the number of new coins dug out by unit equipment. From an economic point of view, the mining cost of Bitcoin has only a little threshold value. In the long run, the cost factor of Bitcoin can only be used as a reference for the bottom line of valuation. So cost is not the decisive factor in the price of Bitcoin. The price of Bitcoin still depends on the social recognition of Bitcoin, or the consensus formed.

At present, with Bitcoin as the leader, various digital currencies are gradually being recognized and familiar with, and even Bitcoin has gradually begun to form a consensus. But in the foreseeable future, there is little chance that Bitcoin will completely replace the mainstream currency. Assuming that Bitcoin can replace the current currency, we can compare the cash in circulation (M0) with 21 million Bitcoins to estimate the price of each Bitcoin, but in fact, such valuation of Bitcoin can only be used as a reference for the upper limit of valuation.

Generally speaking, it is inaccurate to evaluate the special currency by the above two methods, which can only be used as a reference for the upper and lower limits. In reality, the price of Bitcoin is still in a very unstable situation, sudden ups and downs are possible. The instability and unpredictability of the price of Bitcoin are mainly due to the following factors: first, the price of Bitcoin is mainly determined by people’s recognition of its value, that is, the degree of consensus formation, which leads to the influence of news public opinion, even far more than the influence of the cost factor of Bitcoin on its price change; second, Bitcoin is a new thing, although it is gradually acknowledged, but not generally accepted, and most buyers do not really understand the technology of Bitcoin. They decide whether to buy Bitcoin or not based on market changes and news propaganda. At the same time, the government’s policies on BTC are still changing, the price of Bitcoin is constantly changing with the introduction of new government policies. Thirdly, the price volatility makes BTC a new target of speculative markets all over the world. At present, large amount of capital will have a greater impact on the price of Bitcoin, so its price changes are more difficult to predict.

### **3.2 Historical Price Fluctuation and Analysis**

According to the historical data and the events related to Bitcoin, we can regard price changes as the human response to the outcome of the event. By analyzing the rise and fall of Bitcoin price with anthropology, we can have a profound understanding and prediction of the causes or development of Bitcoin market turbulence.

Bitcoin price analysis needs to be combined with positivism and anthropology. We regard part of the reason of Bitcoin price fluctuation as the result of human activities. The demand for bitcoins is undoubtedly determined by human behaviour. Public opinion news is a description of recent human activities, so the development of public opinion news will have a great impact on human psychology and the price of Bitcoin.In a word, public opinion news has a breakthrough impact on the trend of Bitcoin price. Public opinion news describes the actions and reactions of individuals to Bitcoin market. News coverage of human activities will cause a chain reaction of Bitcoin market prices, because news public opinion will have an impact on the actions of other individuals. The most influential events, such as national policy, security and market recognition, will exert the greatest influence on Bitcoin prices.

In order to better understand the causes of Bitcoin price fluctuations, I will analyze the impact of several major events on Bitcoin prices in recent years to explore the factors affecting Bitcoin prices. From 2009 to 2010, Bitcoin has just emerged and developed slowly. The market is in the early stage of recognition. Bitcoin is not well accepted, and each Bitcoin does not exceed $1.

2011 In June, a hacker attacked the Bitcoin trading website and transferred 25,000 Bitcoins into its own account. Because of the anonymity and untraceability of the Bitcoin trading network, the transaction has never been traceable. The hacker attack on the Bitcoin trading website caused a great sensation in the Bitcoin community, shaking the confidence of Bitcoin investors, and the price of Bitcoin has fallen all the way, falling by more than 90% compared with the highest price in June.

2012 Linode, as a website trustee, lost more than 40,000 bitcoins because of the leak of its server’s super management password. The price of bitcoin dropped to about 4 dollars all the way. This is another drop in the price of bitcoin caused by a hacker problem. According to the Bitcoin mining cut by half every four years, on November 28, 2012, the number of Bitcoin mining reduced by half from 7,200 to 3,600. Because of the supply cut by half, the quantity of Bitcoin is in short supply, which makes the price rise.

2013 In February, Reddit issued an announcement that Bitcoin was acceptable for payment. Earlier, WordPress had announced acceptance of digital bitcoin payments. In March 2013, a serious banking crisis broke out in Cyprus, freezing the transfer rights of 1.1 million people, imposing taxes on bank accounts and gradually closing stock markets and banks. With the outbreak of the Cyprus economic crisis, the price of Bitcoin has tripled. On March 12, 2013, the failure of the Bitcoin network caused the price of Bitcoin to fall sharply. On April 12, 2013, after a sharp decline in Bitcoin, the online currency exchange announced a temporary suspension of trading. On June 8, 2013, the Hong Kong Government officially approved the Electronic Money Trading Center (GBL) to allow virtual currency transactions, including Bitcoin. On December 5, 2013, the Central Bank of China and other five ministries jointly issued a report notice on Bitcoin, aiming at strengthening the prevention and control of Bitcoin risk. Bitcoin prices dropped by 35% after the news. On December 7, 2013, Baidu announced that it would stop using Bitcoin as a means of payment. As soon as the news came out, Bitcoin fell to $697.The next day, Lamborghini dealers announced that Bitcoin could be used as a payment tool for Tesla electric vehicles, after which the price of Bitcoin recovered to more than 900 dollars.

In the first quarter of 2014, Bitcoin was in a cooling trend: on February 7, 2014, Mt. Gox suspended the Bitcoin redemption business due to a technology bug, and the trading service will still be available. The news has led to a drop in the price of Bitcoin, and although there has been a slight recovery, the impact of this event is particularly far-reaching. On April 24, 2014, the Central Bank held talks with third-party payment platforms and commercial banks in the hope of cutting off the funding chain on Bitcoin and deploying Bitcoin prevention and control work. On the second day, Alipay announced that it would not provide any services for bitcoin. On August 10, 2014, George Osborne, the British Finance Minister, signaled that Britain wanted to legalize digital currencies such as Bitcoin [16].

2015 In July, the RMB depreciated to a great extent, and investment bank capital turned its attention to the Bitcoin market. In October 2015, investment bank capital entered the Bitcoin market. Through exploring the bottom of the market on Huobi and OKCoin trading platforms, Bitcoin rebounded and its price doubled [17]. On October 22, 2015, according to the ruling of the European Court of Justice, Bitcoin and other virtual currencies in European countries should be treated equally with traditional currencies, introducing a VAT-free policy .According to EU law, transactions between legal currencies (including banknotes and coins) are exempt from VAT. The Swedish government has shown that Bitcoin, unlike traditional legal currencies, should not be exempted from VAT, but the European Court of Justice has taken a different attitude, encouraging supporters of Bitcoin and virtual currencies [18].

2016 In 2008, the Bitcoin market was booming, and more and more people realized the value of Bitcoin. At the beginning of 2016, the Central Bank of China held a seminar on digital currency, aiming at introducing national legal digital currency and discussing the application of digital currency in different scenarios, which greatly encouraged the practitioners and investors of digital currency in China, and the price of bitcoin should also rise. On June 24, 2016, Britain broke away from the European Union, and British Prime Minister Cameron resigned, causing the pound to fall, but the price of Bitcoin rose by nearly 20%.On July 10, 2016, Bitcoin undertook the second half-cut in the four-year mining cycle, resulting in a shortage of supply and demand for Bitcoin and a rise in price [19].

2017 Bitcoin’s annual price trend really deduces what is called the roller coaster market. On January 11, 2017, Bitcoin’s lowest price was 789 dollars. On December 18, Bitcoin reached its highest price of 18,674 dollars, up nearly 1700%, but in June and July, Bitcoin’s price fell 36%. For Bitcoin itself, a crucial event occurred in 2017. On August 1, 2017, Bitcoin Cash appeared. It is a new digital currency generated by the coin forking on the original main chain of Bitcoin. Bitcoin prices fell during the forking period. After the forking, the Bitcoin market rebounded and rose in September. On September 4, 2017, the People’s Bank of China declared that ICO was classified as an illegal financial activity, and the short-term impact on the price of Bitcoin was sustainable [20].

2018 On January 17, 2001, the price of Bitcoin fell by as much as 25%. The reason is that the multinational government strengthened its control over the digital currency, including South Korea, where the trading market is booming. The relevant departments of the Chinese government also ordered the closure of some mining businesses [21].

### **3.3 Analysis of the Main Price Basis of Bitcoin**

The market of Bitcoin is like a roller coaster, but we can still find that every great change in price is caused by a certain reason, so we can summarize the following factors that will have a greater impact on the price of Bitcoin:

+ (1) From the events that affect the price fluctuation of Bitcoin, we can see that the security issue is the primary factor affecting the price of Bitcoin, but the negative events of hackers attacking the network or trading platform of Bitcoin can’t be predicted, and once such events occur, the price of Bitcoin will inevitably drop dramatically. For example, in June 2011, a hacker attack on the Bitcoin trading website caused a great sensation in the Bitcoin community, shaking the confidence of Bitcoin investors, and the price of Bitcoin fell all the way. In 2012, Linode, as a website trustee, lost more than 40,000 bitcoins due to the leak of its server’s super management password, and the price of bitcoins fell to about $4. On February 7, 2014, Mt. Gox suspended the Bitcoin redemption business due to a technology bug. The trading service will still be available, but the price of Bitcoin will fall. According to the Comprehensive Report on Information Security of China in the First Half of 2013 issued by the Information Security Research and Service Center of the National Information Center of China, the primary target of hacker attacks and network fraud in China is Bitcoin [22].Bitcoin is limited in total quantity and rising in value. Because of its high anonymity, it is difficult to trace once it is stolen. This feature has attracted widespread attention of hackers. Because of the high reward of attacking Bitcoin and the high anonymity that is difficult to trace, Bitcoin has become the darling of hackers and underground transactions. Since hacking is unpredictable, and hacker attacks directly challenge the most basic part of the Bitcoin system, it means that security events in Bitcoin transactions will inevitably lead to price volatility, which is also an important factor in bitcoin prices.

+ (2) Bitcoin price fluctuation is partly due to the introduction of relevant policies at the regulatory level in various countries. Since Bitcoin began to reach a relatively large scale shortly, and as a digital currency, there has been no similar precedent before, so the governments have not formulated perfect policies on it, especially leading to its regulatory loopholes. However, with the expansion of Bitcoin market in recent years, the influence and trading volume of Bitcoin are also increasing. Governments of various countries have also attached great importance to new digital currencies such as Bitcoin. Various countries have introduced laws and regulations related to Bitcoin and other digital currencies, but due to different attitudes towards Bitcoin, it is difficult to predict the trend of national policies, which will make the price of Bitcoin more sensitive. For example, on October 22, 2015, according to the ruling of the European Court of Justice, Bitcoin and other virtual currencies in European countries should be treated equally with traditional currencies, and the introduction of VAT-free policies has greatly encouraged supporters of Bitcoin and virtual currencies. On January 17, 2018, the price of Bitcoin fell by as much as 25%, due to the increased control of digital currency by multinational governments, including South Korea, where the trading market is booming, and the closure of some miners by the relevant departments of the Chinese government.

+ (3) Bitcoin consensus in the formation stage of Bitcoin consensus is not only the degree of social recognition of Bitcoin, but also an important factor affecting the price of Bitcoin at the present stage. For example, from 2009 to 2010, Bitcoin has just emerged and developed slowly. The market is in the early stage of recognition. Bitcoin is not well accepted, and each Bitcoin does not exceed $1.In December 2013, Lamborghini dealers announced that Bitcoin could be used as a payment tool for Tesla Electric Vehicles. The acceptance of Bitcoin payment by large enterprises reflects the social recognition of Bitcoin, which represents an increase in people’s recognition of Bitcoin, so the price of Bitcoin has risen. More and more people realized the value of Bitcoin in 2016. At the beginning of this year, the Central Bank of China held a seminar on digital currency, hoping to launch its own legal digital currency, and discussed the application of digital currency in different scenarios. This gave Chinese digital currency practitioners and investors great confidence, and the price of Bitcoin should also rise. From the historical perspective, the market recognition and acceptance of Bitcoin is an important factor to promote the price of Bitcoin.

+ (4) Bitcoin fork. Bitcoin cash emerged on August 1, 2017. Bitcoin cash is a new digital currency generated by coin forking on the original main chain of Bitcoin. Bitcoin prices fell during the forking period. After the forking, the Bitcoin market recovered and rose in September. Bitcoin market volatility will decline in the short term, but in the long run the trend is upward, because it solves the capacity expansion problem of Bitcoin, more people will receive Bitcoin and Bitcoin cash, and Bitcoin holders will get the same amount of Bitcoin. The new fork currency differentiates capital flows and market concerns, so it will lead to a fall in the price of Bitcoin in the short term. The impact of fork on Bitcoin is short-term. In the long run, the price of Bitcoin will rise [23].  Because of the open source nature of Bitcoin itself, there are many counterfeit currencies issued and listed, such as Wright coins and so on.The idea of counterfeit currencies comes from Bitcoin, and the technology comes from Bitcoin, which can be said to be the overissue of Bitcoin. At present, there are many counterfeit currencies, Bitcoin does not have absolute technological advantages. The market only sees the high price of Bitcoin, the difficulty of mining, the cheaper price of counterfeit currencies, and the easier speculative manipulation. Therefore, the existence of counterfeit currencies will certainly share the market of Bitcoin and affect the price of Bitcoin. 

In summary, security issues, the introduction of national policies, market acceptance, bifurcation and counterfeit currencies will all have an impact on the price of Bitcoin, causing price changes, but at the same time, it will also bring media reports to help the formation of Bitcoin consensus.

## **4 Analysis of Influencing Factors of Bitcoin Price**

In the last chapter, we have analyzed the impact of Bitcoin mining cost, security, national policy, social consensus, bifurcation and counterfeit currency on Bitcoin price. I will use positivism to analyze other influencing factors in data and make a mathematical regression model analysis.

### **4.1 Relationship between Mining Difficulty and Bitcoin Price**

Considering the price of Bitcoin as a commodity, cost is the first easy factor to think about. As a digital currency, Bitcoin is mined through what we call Proof of Work mechanisms. Therefore, the mining cost of Bitcoin mainly consists of the purchase cost of mining machines, the electricity cost of mining power consumption and the cost of manpower. The input of mining machines and manpower belongs to the fixed consumption, while the average power of digging out a Bitcoin is mainly related to the difficulty of solving special solutions and its own computing power. When assuming computing power as constant, the change of calculating difficulty of solving special solutions can reflect the changing trend of Bitcoin cost.

In order to prove whether the price of Bitcoin is correlated with the difficulty of mining calculation, we selected the historical data of Bitcoin price and the historical data of difficulty to analyze the period from September 2014 to April, 2019. As shown in P 1 and 2, we can see that although the difficulty of calculation is similar to the general trend of price, it cannot be reflected in price fluctuations.

![base64图片](https://raw.githubusercontent.com/YuchuanXu-1801212958/tupian/master/dif.png)

P1: Bitcoin Historical Mining Difficulty

![base64图片](https://raw.githubusercontent.com/YuchuanXu-1801212958/tupian/master/price.png)

P2: Bitcoin Historical Price

As for the reasons that the impact of cost is not significant, it can be concluded that the mining cost of Bitcoin is mainly for miners, and for users who regard Bitcoin as money or investors, the cost is not their main consideration. At the same time, as a digital currency that needs to build social consensus, Bitcoin mainly relies on currency users and a large number of investors at present. The result of price change is that cost has no significant effect on price.

### **4.2 Relationship between Bitcoin Search Volume and Bitcoin Price**

We mentioned earlier that the degree of building social consensus has an impact on the price of Bitcoin, but the degree of building social consensus is a difficult concept to quantify. Fortunately, the quantitative data of search engines can reflect the social awareness of the concept of Bitcoin from the side. We can use Google Trend to get the search volume data of any key words. Here we are Using the search volume of the keyword "Bitcoin" between September 2014 and April 2019 as reference data, P3 and 4 are as follows:

![base64图片](https://raw.githubusercontent.com/YuchuanXu-1801212958/tupian/master/google.png)

P3: Google Trends - Bitcoin

![base64图片](https://raw.githubusercontent.com/YuchuanXu-1801212958/tupian/master/price.png)

P4: Bitcoin Historical Price

## **5 News Emotional Tendency Data**

### **5.1 The Influences of News Emotional Tendency on Price**

In the short and medium term, news media outbursts of positive and negative news have a great impact on the psychology of Bitcoin holders or investors. Almost every major price change is accompanied by hot events. These hotspots basically include the actions that affect the price of Bitcoin analyzed in the previous chapter (security, policy introduction, market recognition, coin bifurcation and counterfeit currency, etc.). Human behavior can undoubtedly determine the demand for Bitcoin. News media coverage is a description of the latest individual activities. So the big factor affecting prices is the development of this news media content. Robert Shillerr believes that the trend of bitcoin prices is particularly consistent with the definition of speculative bubbles. People are rushing to hold bitcoins, hoping to gain wealth through bitcoin appreciation. Bitcoin investment has gradually become familiar and popular, and the media played an important role in this process [24]. Therefore, the emotional tendencies of news reports are bound to have an impact on people’s attitudes towards Bitcoin, which further affects people’s purchase or investment demand for Bitcoin, and then has an impact on prices.

### **5.2 News Data Sources**

For the part of emotional tendency analysis, because the purpose is to judge the influence of emotional tendency on price, the data of emotional tendency need not be very accurate, so a representative news website can be chosen as news source. We chooses the website www.ccn.com as the source of news reports. The main reasons for choosing the website are as follows:

+ (1) Selecting English news websites can cover more parts of the world, and English is more conducive to accurate emotional orientation analysis than Chinese.

+ (2) The website mainly reports on the news related to digital currency. Bitcoin is the main area of Bitcoin. The professionalism and authority of the website are guaranteed.

+ (3) The website has special pages for several major currencies (Bitcoin, Wright coin, ETF), so when crawling the corresponding news reports, it omits the part of classifying news content, which is conducive to high code efficiency and reduce the incidence of errors.

+ (4) According to Alexa’s website query, the website ranks around 6000 among all the websites in the world, and has more than 100,000 daily visits. It has a relatively large influence and is sufficiently representative in similar websites.

### **5.3 News Reporting Web Crawler Code**

#### **5.3.1 Page analysis**

As mentioned earlier, a news section about Bitcoin has been set up in ccn.com. Its page address is www.ccn.com/news/. Looking at the HTML code of this page, we find that all news headlines and links are located under the D4 tag. 

![base64图片](https://raw.githubusercontent.com/YuchuanXu-1801212958/tupian/master/code.png)

P5: News Link HTML Code

When you open the page, you find that only the latest 16 news items are displayed. If you want to get earlier news, you need to click the "Load More Posts" button at the bottom of the page. P6 below shows that more 16 news items will be loaded on the same page after clicking. Therefore, if you need to get enough news links, you need to click the button several times to load enough news items. More news items, and then crawl one by one.

![base64图片](https://raw.githubusercontent.com/YuchuanXu-1801212958/tupian/master/button.png)

P6: The Load More Posts button at the bottom of the page

#### **5.3.2 Reptilian Code Description**

Because the page turning method mentioned above is to load by clicking the button, we use Python’s Selenium library to simulate mouse clicks. First, by looking at the HTML code of the web page, we can get the XPath value of the button. We can use Selenium’s find_element_by_xpath method to locate the button for click operation. The first step of the program is to open the web page www.ccn.com/news/, using the Chrome browser through webdriver.Chrome() method, and then continue to simulate the mouse input button as described above until enough news reports are loaded, and then use Python’s Beautiful Soup library to retrieve the news content links under the D4 tag, so that the program will not be in the wrong situation. Next can only be re-run, after this step is completed, all links to news content will be saved in a TXT file for the direct use of follow-up procedures.

Driver = webdriver. Chrome () # Open Chrome Browser

Driver. get (url) # access URL address

Driver.find_element_by_xpath("/html/body/div[1]/div/main/div[2]/section/div/div/button"). click () # click buttonsoup = Beautiful Soup (driver.page_source,’html.parser’) # use Beautiful Soup to get the full code of the web page

For link in soup.find_all(‘h4’): # Circulate all H4 Tags

See Appendix 1 for the complete code.

After completing the above part, all the links of Bitcoin news have been saved in a TXT file. Next, we need to get the content of each news in turn, and analyze the emotional orientation of the content, save the time and emotional orientation of the news in the file for data analysis. Use request to open news, in which the header part is intended to disguise as a browser to open news in case it is blocked by the anti-crawler mechanism:

Response = requests. get (url_news, headers = headers, timeout = 10) # Open the news and use BeautifulSoup to get the page code:

Sop_news = Beautiful Soup (response. content,’html. parser’) # Get the page code and use the find method to get the time and content:

Newstime = soup_news.find (‘time’, {class":"update"). get (‘datetime’) get time link = soup_news.find (‘div’, {class": "entry-content"}) text = link.get_text () find the content of the article

The emotional analysis part is accomplished by TextBlob, which is an existing Python library. Although the emotional analysis function of TextBlob library is not for Bitcoin news reporting, it is only expected to make a coarse-grained emotional tendency judgment, so the function of TextBlob library is sufficient to meet the requirements. In TextBlob, polarity attribute is emotional tendency, ranging from -1 to 1.The closer we approach 1, the more positive we are, and vice versa.

Blob = TextBlob (text) F. write (str (blob. polarity) # Record emotional tendencies. See Appendix 2 for the complete code.

### **5.4 Emotional Tendency Data Processing**

In order to facilitate the analysis of emotional tendency data, it is necessary to save the data in CSV file, and because the price and other data are based on the week, we also need to calculate the emotional tendency of each week. We use the average value of all news emotional tendency of each week to represent the emotional tendency of each week. The complete code of the data processing section is shown in Appendix 3 shows the contents of these data processing process files.

## **6 Multivariate Regression Model of Bitcoin Price**

The three independent variables of Bitcoin mining calculation difficulty, Bitcoin search volume and Bitcoin news report sentiment tendency are set as x1, x2 and x3 respectively. Considering the appropriate detection factors and the dependent variable Bitcoin price, a multivariate regression model is established.

### **6.1 Mining difficulty**

According to Metcalfe’s law, the value of the network increases with the square of the number of users, that is, the value of the network is proportional to the square of the number of users. By analogy with the Bitcoin network, the increasing number of mining equipment and the increasing number of miners in the Bitcoin network, the difficulty of mining is increasing, and the value of the Bitcoin network will increase. Therefore, we can introduce the square of the computational difficulty of Bitcoin mining, namely x12, into the multiple regression model as a detection factor.

### **6.2 Search Volume and Emotional Tendency**

Search volume and emotional inclination, these two variables have a common impact on Bitcoin price. A larger search volume of Bitcoin means that news reports during this period will have an impact on more users. Therefore, the product of search volume and emotional inclination, x2x3, can be introduced into the multiple regression model as a detection factor. However, because of the range of emotional inclination (-1,1), there exists a situation where emotional inclination is zero. In this case, the product may be zero, resulting in the change of search volume can not be reflected in the model. To avoid this kind of situation, we can add all emotional inclination to 1, so that the range of values becomes (2,0).Therefore, the product of search volume and emotional inclination plus one is introduced as a detection factor, that is, x2 (x3 + 1).

In order to verify the correlation between this factor and the price of Bitcoin, we first make a regression analysis between the factor and the price of Bitcoin, and get the following tables: Table 1, 2, 3.

| Multiple R |0.91569041|
|:----:|:----:|
| S Square | 0.91569041 |
| Adjusted R Square|0.837601503|
| Standard Error|1516.957586|
| Observation Value|184|

Table 1: x2 (x3 + 1) regression statistics

|   |df|SS|MS|F|Significance F|
|:----:|:----:|:----:|:----:|:----:|:----:|
|Regression Analysis|2|2174269090|2174269090|944.8577197|5.69528E-74|
|Residual|182|41881177.8|2301160.317| | |
|Total|183|2593080268| | | |

Table 2: x2 (x3 + 1) variance analysis

| |Coefficients|Standard Error|T Stat|P-value|Lower 95%|Upper 95%|
|:----:|:----:|:----:|:----:|:----:|:----:|:----:|
|Intercept|207.6845438|130.4561617|1.591987233|0.113122926|-49.7164316|465.0855193|
|X Variable 1|295.1202312|6.67306399|30.73853802|5.69528E-74|191.9537149|218.2857475|

Table 3: x2 (x3 + 1) Variance regression analysis

From Table 1, we can see that Multiple R measures the degree of correlation between the price of Bitcoin and X2X3. R equals 0.916, indicating that the price of Bitcoin is highly correlated with x2 (x3 + 1) and has a positive correlation. RSquare is used to measure the fitting effect, and its value R2 is equal to 0.8385. It shows that the ability of this variable to explain the price of Bitcoin is 83.85%, and the fitting effect is strong. Adjusted R-Square, the value of which is equal to 0.8376, shows that x2 (x3 + 1) can explain 83.76% of the price of Bitcoin, and 16.24% of the price of Bitcoin needs to be explained by other factors. Table 2 shows that the regression effect of Bitcoin price and X2 (x3 + 1) regression model is determined by Significance F. The P value of Bitcoin price and X2 (x3 + 1) analysis is 5.695*10-74, which is much less than the significant level of 0.05. It shows that the regression effect of the regression model of Bitcoin price and X2 (x3 + 1) is more significant. Table 3 shows that the P value of x2 (x3 + 1) is 5.695*10-74, which is much less than the significant level of 0.05. This shows that the regression coefficient of this variable is very significant. There is a correlation between x2 (x3 + 1) and the price of Bitcoin.

 ### **6.3 Bitcoin price multiple regression model**

According to the above, we can get three independent variables of Bitcoin price multivariate regression model. Bitcoin mining difficulty x1, Bitcoin search volume x2 and Bitcoin news report emotional tendency x3. The two detection factors are the square of calculation difficulty (x12), the product of search volume and emotional tendency plus1 (x2 (x3+1)). We can get Bitcoin price multiple Regression analysis. 

| Multiple R |0.961355277|
|:----:|:----:|
| S Square | 0.924203969 |
| Adjusted R Square|0.923097458|
| Standard Error|1044.715586|
| Observation Value|140|

 Table 4: Regression statistics
 
|   |df|SS|MS|F|Significance F|
|:----:|:----:|:----:|:----:|:----:|:----:|
|Regression Analysis|2|1823215820|911607910.1|835.2412541|1.80212E-77|
|Residual|137|149525999.9|1091430.656| | |
|Total|139|1972741820| | | |

Table 5: Variance Analysis

| |Coefficients|Standard Error|T Stat|P-value|Lower 95%|Upper 95%|
|:----:|:----:|:----:|:----:|:----:|:----:|:----:|
|Intercept|66.74853396|103.2313214|0.646591878|0.518977886|-137.384303|270.8813709|
|X Variable 1|5.41742E-22|4.54306E-23|11.92460473|6.26463E|4.51906E-22|6.31578E-22|
|X Variable 2|173.9328199|6.068134027|28.66331218|9.75895E-60|161.9335023|185.9321376|

Table 6: Variance regression parameter table

According to the above univariate analysis, we take the mining difficulty, search volume and the emotional tendency of news reports as independent variables, the square of difficulty and search volume*(emotional tendency+1) as detection factors, and the price of bitcoin as dependent variable for multivariate regression fitting analysis. And we leave some data for later testing. At the same time, in order to evaluate the model, we took the data of the first week of each month as the test set. Table 4 shows that the correlation coefficient Multiple R is 0.9614, which indicates that the correlation between independent variables and dependent variables is strong and positive. R-Square is 0.9242, and the fitting effect of these variables is very good. Adjusted R-Square is 0.9231, which indicates that the two detection factors can explain 92.31% and 7.69% of the dependent variable Bitcoin price by other factors. Table 5 uses Significance F to determine the regression effect of multivariate regression model. The P value of the analysis is 1.8021*10-77, which is much less than the significance level of 0.05. It shows that the regression effect of multivariate regression model is more significant. Table 6 shows that the P value of the product of search volume and emotional tendency plus one is 9.75895*10-60, and the P value of difficulty square is 4.51906*10-23, which is far less than the significant level of 0.05, indicating that the regression coefficients of the two variables are significant. So the predictive ability of this model is tested.

To sum up, we use mining computational difficulty X1 and search quantity x2 and emotional tendency X3 as independent variables, and Bitcoin price Y as dependent variable to get multivariable regression linear equation:

Y=5.41742*10-22X12+173.9328199X2(X3+1)+66.74853396+μ

We add a random perturbation term μ to the regression equation. The random perturbation term includes the neglected factors in the three independent variables of the difficulty and the search volume and the emotional tendency of news reports, the observation errors of the three independent variables, the setting errors of model relations and other random factors.

## **7 Summary**

The value of the traditional legal currency (paper money) originates from the credit endorsement of the country, which solves the problem of distrust through the national credit. However, because of its decentralization mechanism, digital currency such as Bitcoin has no third-party credit endorsement, but its value does exist. Firstly, the basic value of digital currency such as Bitcoin comes from its mining value, which includes the input cost of mining machines, electricity consumption and labor costs. Cost guarantees the basic value of digital currency and can be used as the lower limit of the valuation of digital currency. Secondly, the value of gold is also based on the public recognition of gold, and it is difficult to break. Analogous to the value of digital money, with the growing size of the digital money market such as Bitcoin and the gradually formed user system, the value consensus of digital money such as Bitcoin has gradually deepened.

In conclusion, we should analyze the trend of bitcoin prices in the form of “human behavior” and “positivism”. First, according to the mainstream news media report analysis, including security events, national policies, market recognition, forks and altcoins. Secondly, use the mining difficulty, keyword search volume and news report sentiment tendency to analyze the price trend of Bitcoin. 

## **Reference**

[1] 贾丽平.比特币的理论、实践与影响[J].国际金融研究 12(2013):14-25.)

[2] 罗强,张睿.比特币[M]. 机械工业出版社, 2014

[3] 孙佳音.比特币的性质、定价与监管研究[D].上海： 上海交通大学,2014

[4] Li X,Wang C A.The technology and economic determinants of cryptocurrency exchange rates[M]. Elsevier Science Publishers B. V. 2017

[5] J.A. Feigenbaum, P.G.O. Freund. Discrete scale invariance in stock markets beforecrashes[J]. Internat. J. Modern Phys. B 10 1996:3737–3745

[6] Bariviera A F, Basgall M J, Hasperué W, et al. Some stylized facts of the Bitcoinmarket[J]. Physica A Statistical Mechanics & Its Applications. 2017:484:82-90

[7] Dyhrberg A H. Bitcoin, gold and the dollar – A GARCH volatility analysis[J]. Finance Research Letters.2015:16:85-92


[8] Castro M, Liskov B. Practical byzantine fault tolerance and proactive recovery[J].ACM Transactions on Computer Systems. 2002: 20(4): 398-461

[9] Bentov I, Lee C, Mizrahi A, Rosenfeld M. Proof of activity: extending Bitcoin’s proof of work via proof of stake[J]. ACM SIGMETRICS Performance Evaluation Review.2014:42(3): 34-37

[10] Consensus in Bitcoin: one system, many models [EB/OL].https://freedom-to-tinker.com/blog/randomwalker/consensus-in-bitcoin-one-system-many-models/

[11] Huberman G, Leshno J D, Moallemi C C. Monopoly Without a Monopolist: An Economic Analysis of the Bitcoin Payment System[M]. Social Science Electronic Publishing. 2017

[12] 陈豪. 比特币的经济学分析[D]. 浙江： 浙江大学, 2015

[13] 比特币盘面与投行潜伏资金_玩币族[EB/OL].http://www.wanbizu.com/jingyan/201606127038.html

[14] 10 coins community events in 2016![EB/OL]https://www.btctrade.com/bitcoin/1323.html

[15] 汇通网 2017 比特币 2017 年如何疯狂？细数过山车行情及重磅事件[EB/OL].http://finance.sina.com.cn/money/forex/hbfx/2017-12-31/doc-ifyqchnr7874160.html

[16] 2013 年上半年中国信息安全综合报告 - 瑞星网[EB/OL]. http://www.rising.com.cn/about/news/rising/2013-07-10/14047_3.html

[17] 硬分叉会如何影响比特币的价值储存有用性？ _巴比特_服务于区块链创新[EB/OL]http://www.8btc.com/hard-fork-affect-bitcoins-usefulness-store-value

[18] 凌清，比特币的技术原理与经济学分析[D].上海： 复旦大学, 2014. 


## **Appendix 1**

-# -*- coding: utf-8 -*-

import requests

import unittest

from selenium import webdriver

from selenium.webdriver.common.keys import Keys

from selenium.webdriver.support.wait import WebDriverWait

from selenium.webdriver.support import expected_conditions as EC

from selenium.webdriver.common.by import By

import urllib2

import time

import sys

reload(sys)

sys.setdefaultencoding('utf-8')

from bs4 import BeautifulSoup

from textblob import TextBlob

url=https://www.ccn.com/news/

headers = {

'User-Agent':'Mozilla/5.0 (Windows; U; Windows NT 6.1; en-US; rv:1.9.1.6) Gecko/20091201

Firefox/3.5.6'

}# Disguised as a browser

driver=webdriver.Chrome()

driver.get(url)

page=0

i=0

f=open('demodata.txt','w')

urlnews=open('btcnews.txt','w')

button=driver.find_element_by_xpath("/html/body/div[1]/div/main/div[2]/section/div/div/button") 

while page<1080:

try:

button.click()

page=page+1

except:

print("error",page)

if page<10:

print(page)

if page%50==0:

print(page)

time.sleep(2)

soup=BeautifulSoup(driver.page_source,'html.parser')

print('next')

for link in soup.find_all('h4'):

i=i+1

for child in link.children:

try:

url_news=child.get('href')

urlnews.write(url_news)

urlnews.write("\n")

except:

continue

urlnews.close()

f.close()

driver.close() 

## **Appendix 2**

-# -*- coding: utf-8 -*-

import sys

reload(sys)

sys.setdefaultencoding('utf-8')

import requests

import unittest

from selenium import webdriver

from selenium.webdriver.common.keys import Keys

import urllib2

import time

from bs4 import BeautifulSoup

from textblob import TextBlob

headers = {

'User-Agent':'Mozilla/5.0 (Windows; U; Windows NT 6.1; en-US; rv:1.9.1.6) Gecko/20091201

Firefox/3.5.6'

}# Disguised as a browser

urlfile=open('btcnews.txt','r')

f=open('demodata.txt','w')

i=0

data=urlfile.readlines()

for url_news in data:

try:

response=requests.get(url_news,headers = headers,timeout=10) #Open news

except:

continue

try:

soup_news=BeautifulSoup(response.content,'html.parser') #Get the webpage code

except:

continue

try: 

newstime=soup_news.find('time',{"class":"updated"}).get('datetime') #Get time

except:

continue

try:

link=soup_news.find('div',{"class":"entry-content"})

except:

continue

try:

text=link.get_text() #Find article content

i=i+1

except:

continue

f.write(newstime)

blob = TextBlob(text)

f.write(str(blob.polarity))

f.write('\n')

if i%100==0:

print(i,newstime)

urlfile.close()

f.close() 

## **Appendix 3** 
-# -*- coding: utf-8 -*-

import csv

import sys

import time

txtfile=open('demodata.txt','r')

csvfile=open('newspolarity.csv','w')

datefile=open('date.csv','r')

reader=csv.reader(datefile)

writer=csv.writer(csvfile)

fileheader=["date","polarity"]

writer.writerow(fileheader)

data=txtfile.readlines()

daterange=datefile.readline()

sum_polarity=0

count=0

for lines in data:

d1=lines[0:4]+"-"+lines[5:7]+"-"+lines[8:10]

d2=lines[25:]

alist=[]

if cmp(d1,daterange)>-1:

sum_polarity=sum_polarity+float(d2)

count=count+1

else:

alist.append(daterange)

if count==0:

alist.append("0")

else:

alist.append(sum_polarity/count)

writer.writerow(alist)

daterange=datefile.readline() 

sum_polarity=0

count=0

txtfile.close()

csvfile.close()

datefile.close() 


