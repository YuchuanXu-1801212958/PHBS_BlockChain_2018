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

!(https://raw.githubusercontent.com/YuchuanXu-1801212958/tupian/master/dif.png)

P1: Bitcoin Historical Mining Difficulty

!（https://github.com/YuchuanXu-1801212958/tupian/raw/master/price.png)

P2: Bitcoin Historical Price

As for the reasons that the impact of cost is not significant, it can be concluded that the mining cost of Bitcoin is mainly for miners, and for users who regard Bitcoin as money or investors, the cost is not their main consideration. At the same time, as a digital currency that needs to build social consensus, Bitcoin mainly relies on currency users and a large number of investors at present. The result of price change is that cost has no significant effect on price.

### **4.2 Relationship between Bitcoin Search Volume and Bitcoin Price**

We mentioned earlier that the degree of building social consensus has an impact on the price of Bitcoin, but the degree of building social consensus is a difficult concept to quantify. Fortunately, the quantitative data of search engines can reflect the social awareness of the concept of Bitcoin from the side. We can use Google Trend to get the search volume data of any key words. Here we are Using the search volume of the keyword "Bitcoin" between September 2014 and April 2019 as reference data, P3 and 4 are as follows:

!()

P3: Google Trends - Bitcoin

!()

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
