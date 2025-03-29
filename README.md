# Rob Costa's Financial Mathematics and Automated Trading Resource Page

### 📚 Navigation 📊
**[ [Home](README.md) | [About Me](about.md) ]**

Hi everyone, this is Rob's page on quantitative finance and algorithmic trading. A lot of what happens at the hedge funds doing quantitative analysis is [quite secretive](https://www.marketwatch.com/story/renaissance-millennium-settle-trade-secrets-dispute), but I am hoping to work on making some finance models more accessible, while keeping some of the code I develop still private between me and my collaborators. Below is some published literature on portfolio analysis and hedging, lists of research journals, classic economics texts, options and futures video tutorials, and more. Investors should contact [Costa Capital Technologies](mailto:owner@CostaCapital.org), which I'm starting up as a nonprofit to support research and development in quantitative analysis of the stock market, structured with for-profit subsidiaries, following the examples of companies like Patagonia and OpenAI. A prototype of our platform is available [here](https://candlesage.streamlit.app/), and I'm actively fundraising to improve it. For my math and logic interests, see my [Google Drive](https://drive.google.com/drive/folders/0B9bvsojRLzQ4fmVhUGdoby1URFRYYVZmMnh4dDFGLVc2YmdUVW5SdEdzZXl4OGF4ajcxajQ?resourcekey=0-XWGB5GzqOjIy6syC3Ah8qw&usp=sharing). Questions? [Contact me](mailto:owner@costacapital.org).

## Table of Contents
- [Financial Analysis: Start Here](#financial-analysis-start-here)
  - [Video lecture series](#video-lecture-series)
  - [Textbooks and articles on core concepts](#textbooks-and-articles-on-core-concepts)
- [Recent Research](#recent-research)
  - [Articles on Machine Learning, Mathematical Finance, and High-Frequency Trading](#articles-on-machine-learning-mathematical-finance-and-high-frequency-trading)
  - [Unpublished AMS abstracts](#unpublished-ams-abstracts)
- [Classic and Historic Economic Literature References](#classic-and-historic-economic-literature-references)
- [Books on trading psychology and methodology](#books-on-trading-psychology-and-methodology)
- [Mathematicians who have had trading success](#mathematicians-who-have-had-trading-success)
- [Further Video References](#video-references)
  - [Hidden Markov Models & Bayesian Methods](#hidden-markov-models--bayesian-methods)
  - [Long Short-Term Memory (LSTM) & Recurrent Neural Networks (RNN)](#long-short-term-memory-lstm--recurrent-neural-networks-rnn)
  - [Automated analysis and trading in python](#automated-analysis-and-trading-in-python)
  - [Understanding options](#understanding-options)
  - [Understanding futures](#understanding-futures)
- [GitHub repositories](#github-repositories)
- [Medium articles](#medium-articles)

## Financial Analysis: Start Here

### Video lecture series
Here are a few lecture series on financial mathematics, probability, statistics, and machine learning:
- [MIT 18.S096 Topics in Mathematics with Applications in Finance, Fall 2013](https://ocw.mit.edu/courses/18-s096-topics-in-mathematics-with-applications-in-finance-fall-2013/)
- [MIT 15.401 Finance Theory I, Fall 2008](https://ocw.mit.edu/courses/15-401-finance-theory-i-fall-2008/)
- [MIT 15.402 Finance Theory II, Spring 2003](https://ocw.mit.edu/courses/15-402-finance-theory-ii-spring-2003/)
- [MIT 18.650 Statistics for Applications, Fall 2016](https://ocw.mit.edu/courses/18-650-statistics-for-applications-fall-2016/)
- [MIT 6.S191: Introduction to Deep Learning](https://introtodeeplearning.com/)
- [MIT 6.041 Probabilistic Systems Analysis and Applied Probability](https://youtube.com/playlist?list=PLUl4u3cNGP61MdtwGTqZA0MreSaDybji8&si=OxRAXTRH83snkjAP)
- [MIT RES.6-012 Introduction to Probability, Spring 2018](https://youtube.com/playlist?list=PLUl4u3cNGP60hI9ATjSFgLZpbNJ7myAg6&si=j7hlMTqDPHAu0eum)
- [Stanford CS109: Probability for Computer Scientists](https://www.youtube.com/playlist?list=PLoROMvodv4rOpr_A7B9SriE_iZmkanvUg)
- [Stanford CS229: Machine Learning](https://www.youtube.com/playlist?list=PLoROMvodv4rMiGQp3WXShtMGgzqpfVfbU)
- [Harvard Statistics 110: Probability](https://www.youtube.com/playlist?list=PL2SOU6wwxB0uwwH80KTQ6ht66KWxbzTIo)
- [Harvard CS 224: Advanced Algorithms](https://www.youtube.com/playlist?list=PL2SOU6wwxB0uP4rJgf5ayhHWgw7akUWSf)
- [Yale Quantitative Finance](https://www.youtube.com/playlist?list=PL3F00F1C2D402D45C)

### Textbooks and articles on core concepts
This is a selection of good reference articles and books, organized by publication date:

- [Principles of Economics (Marshall, 1890)](https://www.google.com/books/edition/Principles_of_Economics/7yxBAAAAIAAJ?hl=en&gbpv=0)
- [The Theory of Speculation (Bachelier, 1900)](https://www.investmenttheory.org/uploads/3/4/8/2/34825752/emhbachelier.pdf)
- [On the Theory of the Consumer's Budget (Slutsky, 1915)](https://www.jstor.org/stable/43828058?seq=1)
- [Technical Analysis and Stock Market Profits(Schabacker, 1932)](https://themarket101.wordpress.com/wp-content/uploads/2012/12/technical-analysis-and-stock-market-profits.pdf)
- [Security Analysis: Principles and Technique (Graham & Dodd, 1934)](https://glenbradford.com/files/Stocks/security-analysis-benjamin-graham-6th-edition-pdf-february-24-2010-12-08-am-3-0-meg.pdf)
- [Value and Capital (Hicks, 1939)](https://archive.org/details/in.ernet.dli.2015.223876)
- [Theory of Games and Economic Behavior (Von Neumann & Morgenstern, 1944)](https://archive.org/details/theoryofgameseco00vonn)
- [Portfolio Selection: Efficient Diversification of Investments (Markowitz, 1952)](https://www.math.hkust.edu.hk/~maykwok/courses/ma362/07F/markowitz_JF.pdf)
- [Technical Analysis of the Financial Markets (Murphy, 1999)](https://github.com/ShamaUgale/myBooks/blob/master/John%20J%20Murphy%20-%20Technical%20Analysis%20Of%20The%20Financial%20Markets.pdf)
- [Dynamic Asset Pricing Theory (Duffie, 2001)](https://github.com/auscott/books/blob/main/Darrell%20Duffie%20-%20Dynamic%20Asset%20Pricing%20Theory%2C%20Third%20Edition.-Princeton%20University%20Press%20(2001).pdf)

## Recent Research

Here is a list of some top academic journals:
- [Mathematical Finance - Wiley Online Library](https://onlinelibrary.wiley.com/journal/14679965)
- [SIAM Journal on Financial Mathematics](https://epubs.siam.org/journal/sjfmbj)
- [Journal of Mathematical Finance - SCIRP](https://www.scirp.org/journal/jmf/)
- [Mathematics and Financial Economics - Springer](https://link.springer.com/journal/11579)
- [Journal of Asset Management - Taylor & Francis](https://www.tandfonline.com/toc/ramf20/current)
- [Frontiers of Mathematical Finance - AIMS](https://www.aimsciences.org/fmf)

### Articles on Machine Learning, Mathematical Finance, and High-Frequency Trading
Here are some recent articles I found, some of which are from researchers I met presenting on their work at the 2025 Joint Math Meetings.
An older but relevant article that Tufts University president Kumar told me he wrote is [Multidimensional portfolio optimization with proportional transaction costs (Muthuraman & Kumar, 2006)](https://onlinelibrary.wiley.com/doi/pdf/10.1111/j.1467-9965.2006.00273.x).

- [Predicting stock market index using LSTM](https://www.sciencedirect.com/science/article/pii/S2666827022000378)
- [Predicting NEPSE index price using deep learning models](https://www.sciencedirect.com/science/article/pii/S2666827022000706)
- [Hedging via Perpetual Derivatives: Trinomial Option Pricing and Implied Parameter Surface Analysis](https://arxiv.org/abs/2410.04748)
- [The Distribution Builder: A Tool for Inferring Investor Preferences](https://web.stanford.edu/~wfsharpe/art/qpaper/qpaper.html)
- [Analysis of Investment Returns as Markov Chain Random Walk](https://onlinelibrary.wiley.com/doi/10.1155/2024/3966566)
- [Semi-static conditions in low-latency C++ for high frequency trading: Better than branch prediction hints](https://www.sciencedirect.com/science/article/pii/S0743731524001643)
- [Parallel computing in finance for estimating risk-neutral densities through option prices](https://www.sciencedirect.com/science/article/pii/S074373152200243X)
- [A hidden Markov model for statistical arbitrage in international crude oil futures markets](https://arxiv.org/pdf/2309.00875)
- [The High-Frequency Trading Arms Race: Frequent Batch Auctions as a Market Design Response](https://academic.oup.com/qje/article-pdf/130/4/1547/30637414/qjv027.pdf)
- [On the Market-Neutrality of Optimal Pairs-Trading Strategies](https://arxiv.org/pdf/1608.08268)
- [Formal verification of trading in financial markets](https://arxiv.org/pdf/1907.07885)
- [C++ Design Patterns for Low-Latency Applications Including High-Frequency Trading](https://arxiv.org/pdf/2309.04259)

### Unpublished AMS abstracts
These abstracts are all from the 2025 Joint Math Meetings, but were not yet published.

- [Can We See the Next Recession Coming? Deep Learning in Economic Forecasting.](https://meetings.ams.org/math/jmm2025/meetingapp.cgi/Paper/41055)
- [FOREX Prediction Using Deep Learning](https://meetings.ams.org/math/jmm2025/meetingapp.cgi/Paper/43462)
- [Deep Learning Techniques for Equity Portfolio Construction, Optimization, and Performance Analysis](https://meetings.ams.org/math/jmm2025/meetingapp.cgi/Paper/45238)
- [Wavelet Based Reinforcement Learning for Pairs Trading Across Multiple Asset Classes](https://meetings.ams.org/math/jmm2025/meetingapp.cgi/Paper/45119)


## Classic and Historic Economic Literature References

- Sir William Petty's 1662 [A Treatise of Taxes and Contributions](https://www.gutenberg.org/ebooks/61588) discusses principles of taxation and public expenditure, emphasizing the need for equitable and efficient taxation systems.
- Adam Smith's 1776 [An Inquiry into the Nature and Causes of the Wealth of Nations](https://books.google.com/books/about/The_Wealth_of_Nations.html), often abbreviated as *The Wealth of Nations*, is considered his magnum opus and the first modern work that treats economics as a comprehensive system and an academic discipline.
- David Ricardo's 1817 [On The Principles of Political Economy and Taxation](https://www.google.com/books/edition/On_the_Principles_of_Political_Economy_a/cUBKAAAAYAAJ) introduces the theory of comparative advantage, arguing that countries should specialize in producing goods where they have a lower opportunity cost, benefiting from trade even without an absolute advantage.
- John Stuart Mill's 1848 [Principles of Political Economy](https://www.gutenberg.org/files/30107/30107-pdf.pdf) explores the production and distribution of wealth, focusing on labor, capital, and land.
- Francis Ysidro Edgeworth is credited with introducing indifference curves in his 1881 book [Mathematical Psychics: An Essay on the Application of Mathematics to the Moral Sciences](https://historyofeconomicthought.mcmaster.ca/edgeworth/mathpsychics.pdf).
- Alfred Marshall is renowned for his foundational book [Principles of Economics](https://www.google.com/books/edition/Principles_of_Economics/7yxBAAAAIAAJ?hl=en&gbpv=0) (1890), which laid the groundwork for modern microeconomics. Although Marshall did not directly develop indifference curves, his work on utility and consumer behavior influenced later economists.
- Louis Bachelier is credited with being the first person to model the stochastic process now called Brownian motion, as part of his doctoral thesis [The Theory of Speculation (Théorie de la spéculation, defended in 1900)](https://www.investmenttheory.org/uploads/3/4/8/2/34825752/emhbachelier.pdf).
- The Slutsky equation, which decomposes the price effect into substitution and income effects, was first published by Russian-Soviet economist Eugene Slutsky in his 1915 paper ["Sulla teoria del bilancio del consummatore" (On the Theory of the Consumer's Budget)](https://www.jstor.org/stable/43828058?seq=1). Another notable paper by Slutsky is his 1937 publication [The Summation of Random Causes as the Source of Cyclic Processes](https://www.jstor.org/stable/1907241).
- Charles Dow published 255 editorials in the Wall Street Journal analyzing American stock market data using technical analysis, forming the foundations of what is now called *Dow theory*. William Hamilton expanded upon Dow theory in [The Stock Market Barometer](https://stock-market-observations.com/wp-content/uploads/2013/02/the-stock-market-barometer-by-william-hamilton.pdf) (1922).
- Gustav Cassel's [Theory of Social Economy](https://www.google.com/books/edition/The_Theory_of_Social_Economy/Y_iDX2WCf2sC), first published in 1923, is a comprehensive work that outlines his approach to economics. It emphasizes the interconnectedness of economic phenomena and the need for a systematic approach to understanding economic systems. 
- Ragnar Frisch coined the term *econometrics* in 1926 for utilising statistical methods to describe economic systems, as well as the terms *microeconomics* and *macroeconomics* in 1933, was one of the founders of the Econometric Society, and served as the first editor of the *Econometrica* journal from 1933 to 1954. His speech accepting the first Nobel Prize in Economics in 1969 is [From Utopian Theory to Practical Applications: The Case of Econometrics](https://www.nobelprize.org/uploads/2018/06/frisch-lecture-1.pdf). 
- Richard Schabacker continued the work of Dow and Hamilton in [Technical Analysis and Stock Market Profits](https://themarket101.wordpress.com/wp-content/uploads/2012/12/technical-analysis-and-stock-market-profits.pdf) (1932).
- Lionel Robbins' [An Essay on the Nature and Significance of Economic Science](https://www.google.com/books/edition/An_Essay_on_the_Nature_and_Significance/nySoIkOgWQ4C), first published in 1932, defines economics as a science and explores its methodology and scope. 
- John Hicks significantly contributed to economics, particularly with [Value and Capital](https://archive.org/details/in.ernet.dli.2015.223876) (1939), where he popularized the indifference curve approach. This book provided a detailed framework for understanding consumer behavior using indifference curves, marking a shift towards ordinal utility theory.
- Benjamin Graham and David Dodd laid out the foundations of fundamental analysis in [Security Analysis: Principles and Technique](https://glenbradford.com/files/Stocks/security-analysis-benjamin-graham-6th-edition-pdf-february-24-2010-12-08-am-3-0-meg.pdf) (1934). Graham further developed value investing in [The Intelligent Investor](https://yourknowledgedigest.org/wp-content/uploads/2020/04/the-intelligent-investor.pdf) (1949).
- [The General Theory of Employment, Interest, and Money](https://www.files.ethz.ch/isn/125515/1366_keynestheoryofemployment.pdf) (1936) by John Maynard Keynes replaced the neoclassical understanding of employment with Keynes' view that demand, and not supply, is the driving factor determining levels of employment.
- John von Neumann made groundbreaking contributions to economics through [Theory of Games and Economic Behavior](https://archive.org/details/theoryofgameseco00vonn) (1944), co-authored with Oskar Morgenstern. This work established game theory as a major field in economics.
- Alfred Cowles founded Yale's Cowles Commission for Research in Economics, which advanced the field of econometrics in the 20th century. Two of his notable publications in *Econometrica* are [Stock Market Forecasting](https://www.jstor.org/stable/1905433) (1944) and [A Revision of Previous Conclusions Regarding Stock Price Behavior](https://www.jstor.org/stable/1907573) (1960).
- In 1948, Robert Edwards and John Magee published [Technical Analysis of Stock Trends](https://vdthangmeomeo.wordpress.com/wp-content/uploads/2014/08/edwards-magee-technical-analysis-of-stock-trends-9th-edition.pdf) which is widely considered to be one of the seminal works of the discipline.
- The Markowitz model of portfolio management was put forward by Harry Markowitz in 1952 in [Portfolio Selection: Efficient Diversification of Investments](https://www.math.hkust.edu.hk/~maykwok/courses/ma362/07F/markowitz_JF.pdf).
- One of Milton Friedman's most popular works, [A Theory of the Consumption Function](https://www.nber.org/books-and-chapters/theory-consumption-function) (1957), challenged traditional Keynesian viewpoints about the household. He went on to publish [Capitalism and Freedom](http://pombo.free.fr/friedman2002.pdf) (1962), in which he argues for economic freedom as a precondition for political freedom.
- William Sharpe was one of the originators of the capital asset pricing model (CAPM) in his [Capital Asset Prices: A Theory of Market Equilibrium under Conditions of Risk](https://onlinelibrary.wiley.com/doi/10.1111/j.1540-6261.1964.tb02865.x) (1964), despite it originally being rejected for publication. He developed the Sharpe ratio for evaluating returns on risk in [Mutual Fund Performance](http://www.stat.ucla.edu/~nchristo/statistics_c183_c283/sharpe__mutual_fund_performance.pdf) (1966).
- The science of bond analysis was largely founded by Martin Leibowitz and Sidney Homer's [Inside the Yield Book](https://archive.org/details/insideyieldbookn00home) (1972).
- For a modern guide to technical analysis, take a look at John Murphy's [Technical Analysis of the Financial Markets: A Comprehensive Guide to Trading Methods and Applications](https://github.com/ShamaUgale/myBooks/blob/master/John%20J%20Murphy%20-%20Technical%20Analysis%20Of%20The%20Financial%20Markets.pdf) (1999).
- Darrell Duffie wrote a widely referenced [2001 book on Dynamic Asset Pricing Theory](https://github.com/auscott/books/blob/main/Darrell%20Duffie%20-%20Dynamic%20Asset%20Pricing%20Theory%2C%20Third%20Edition.-Princeton%20University%20Press%20(2001).pdf), as well as a [2002 survey of Intertemporal Asset Pricing Theory](https://web.stanford.edu/~duffie/survey.pdf).
- For an overview of the current state of macroeconomics, see Brian Snowdon and Howard Vane's [Modern Macroeconomics](https://www.ricardopanza.com.ar/files/macro2/Modern_Macroeconomics_Snowdon___Vane_05.pdf) (2005) and Sanjay Chugh's [Modern Macroeconomics](https://nibmehub.com/opac-service/pdf/read/Modern%20Macroeconomics.pdf) (2015).

## Books on trading psychology and methodology
- Some good books on trading include *High Probability Trading*, *Option Volatility and Pricing*, *Options Trading: The Bible*, *Get Rich With Options*, and *Mind over Markets*.
- For more historical perspectives on trading, I also enjoyed reading the *Market Wizards* books, *When Genius Failed*, and Michael Lewis's writings from the last few decades such as *Liar's Poker*.
- Also for more general tips, *The Money Game*, *Mastering the Trade*, and *Trading in the Zone*, or memoirs like *How I Made $2,000,000 in the Stock Market* from Nicolas Darvas and *Reminiscences of a Stock Operator* about Jesse Livermore.

## Mathematicians who have had trading success
- Leibowitz of *Inside the Yield Book* had a PhD in math before going into finance.
- Professor Edward Thorp started one of the first hedge funds based on statistical arbitrage. Check out his autobiography *A Man for all Markets*, along with *Beat the Dealer* and *Beat the Market*.
- Alongside Thorp as one of the first "quants" who applied mathematical and algorithmic principals to Wall Street is Jim Simons, known in math for the Chern-Simons form, and famous publicly for his hedge fund Rennaissance Technology and its Medallion Fund. His life is chronicled in the biography *The Man Who Solved the Market*.

## Further Video References

### Hidden Markov Models & Bayesian Methods  
- [Jim Simons Trading Secrets: Markov Process](https://www.youtube.com/watch?v=76B8_aXcBS0) – QuantProgram  
- [Hidden Markov Model Clearly Explained! Part 5](https://www.youtube.com/watch?v=Y66waEr1UXE) – Normalized Nerd  
- [A Friendly Introduction to Bayes Theorem and Hidden Markov Models](https://www.youtube.com/watch?v=H9sFZs7DmJY) – Serrano.Academy  

### Long Short-Term Memory (LSTM) & Recurrent Neural Networks (RNN)  
- [Long Short-Term Memory (LSTM), Clearly Explained](https://www.youtube.com/watch?v=WCUNPb-5EYI) – StatQuest with Josh Starmer  
- [LSTM Top Mistake in Price Movement Predictions for Trading](https://www.youtube.com/watch?v=XbRe_YUKIbc) – CodeTrading  
- [LSTM Networks: Explained Step by Step!](https://www.youtube.com/watch?v=9zhrxE5PQgY) – ritvikmath  
- [An Introduction to RNN and LSTM](https://www.youtube.com/watch?v=aircAruvnKk) – DigitalSreeni  
- [Deep Learning: Long Short-Term Memory Networks (LSTMs)](https://www.youtube.com/watch?v=3mb6XvnfBco) – MATLAB  
- [Illustrated Guide to LSTMs and GRUs: A Step-by-Step Explanation](https://www.youtube.com/watch?v=8HyCNIVRbSU) – The AI Hacker  

### Automated analysis and trading in python

- Full Courses
  - Algorithmic Trading Using Python - 3 hour course. [Video here.](https://www.youtube.com/watch?v=9Y3yaoi9rUQ)
  - Algorithmic Trading Using Python - 4 hour course. [Video here.](https://www.youtube.com/watch?v=xfzGZB4HhEE)
  - How To Build A Trading Bot In Python - 9 hour course. [Video here.](https://www.youtube.com/watch?v=jz3tEsCcie0)
- Demos
  - Stock Option Screener in Python - 16 min demo. [Video here.](https://www.youtube.com/watch?v=aeAoVTu66iU)
  - Introduction to Algorithmic Trading Using Python - 17 min demo. [Video here.](https://www.youtube.com/watch?v=fqltiq5EahU)
  - How To Build A Trading Bot In Python - 18 min demo. [Video here.](https://www.youtube.com/watch?v=WcfKaZL4vpA)
  - How to Code a Trading Bot with QuantConnect - 23 min demo. [Video here.](https://www.youtube.com/watch?v=s8uyLscRl-Q)
  - Coding an Options Trading Algorithm with QuantConnect - 26 min demo. [Video here.](https://www.youtube.com/watch?v=Lq-Ri7YU5fU)
  - Probability Distribution of Stock Returns - 35 min demo. [Video here.](https://youtu.be/a0rcZkJP4RQ?si=m9CgyBVBmF9W1DNS)
  - How to Code an AI Trading bot - 35 min demo. [Video here.](https://www.youtube.com/watch?v=c9OjEThuJjY)

### Understanding options
Options contracts are a type of derivative instrument, because they are *derived* from an underlying asset (a security specified by a stock symbol), a strike price, and an expiration date. A **call** option gives you the right to *buy* 100 shares of a security at the strike price before the expiration date, and a **put** option gives you the right to *sell* 100 shares of a security at the strike price before the expiration date. The current value of an options contract is a function of the time remaining until expiration, the current price of the underlying security, and the volatility. The **intrinsic value** is the amount of money that can be made by exercising the contract at expiration if it were to expire today; if it expires *in the money*, meaning the stock price is currently above the strike price for calls, or below the strike price for puts, then this is given by the difference between the current price of the stock and the strike price, multiplied by 100. Otherwise, it is *out of the money*, and the intrinsic value is just $0 (it has no intrinsic value). The **extrinsic value** (or **time value**) is the value derived from the uncertainty and volatility when there is still time remaining until expiration. The total value is the sum of these. Since the time value exponentially decays down to $0 by the expiration date (a process called "theta decay" or "time decay"), at expiration the total value of the option is just the intrinsic value, which may also be $0. Holders of options contracts often will try to sell before expiration, to avoid the decaying value. Sellers of options profit from time decay, but may still close before expiration to limit risk. Complex options strategies may have multiple *legs*, composed of buying and selling calls and puts at various strike prices and expiration dates, but they are still always either net long or net short on the underlying.

- Pretty much all complex options strategies are made by combining different types of spreads. These all require level 3 options trading. For a basic overview of options, start [here](https://www.youtube.com/watch?v=4HMm6mBvGKE) and [here](https://www.youtube.com/watch?v=MiybniIIvx0). You may also want to start learning about [the Greeks](https://www.youtube.com/watch?v=kCJcEOYuuII).
- Here is a nice video on long vertical spreads, also called debit spreads, which is probably the most similar to buying calls or puts directly. The difference is you somewhat offset theta decay (though also limiting your maximum possible gain) by simultaneously selling an equal number of options. [Here is the video.](https://www.youtube.com/watch?v=1SVswX2V_vE)
- Here is another video, by the same channel, on short vertical spreads, also called credit spreads. This is where you are trying to profit from theta decay and taking on the role of the "option seller." The problem with selling options though, is that your losses can be huge if the options you sold end up in the money, so you can offset those risks by buying an equal number of options that are further out of the money. This limits your total possible losses. [Here is the video.](https://www.youtube.com/watch?v=6_0SbRaHv1U)
- If you want to go more in depth, there's a guy I used to watch who does pretty long detailed videos. [Here's his video on both types of vertical spreads.](https://www.youtube.com/watch?v=mwttDWfDQ9c)
- There is also the wheel, which requires owning the underlying stock. [Here's a video on it.](https://www.youtube.com/watch?v=EcsErh9Airs&t=395s)
- For an explanation of options pricing, see [The Trillion Dollar Equation (Black-Scholes/Merton)](https://www.youtube.com/watch?v=2Utm21VuuJo).
- Once you start watching these videos, you'll find a lot of similar channels with different people's explanations and strategies, so I encourage you to explore and discover new channels that work for you!

### Understanding futures
Futures, like options, are also a type of derivative, whose price is based on an underlying asset, whether it's an index (e.g., for E-mini S&P futures contracts), or commodities like gold, Bitcoin, corn, and oil. While futures have an expiration date, and quite a bit of leverage, their profit and loss settles to the difference with the underlying more linearly, in a way that is more comparable to forex. The margin requirements offset the leverage they provide, and further leverage can be provided by trading options on futures.

- [What are Futures? - the Plain Bagel](https://www.youtube.com/watch?v=1Mhk4UHJsRc)
- [What are futures? - MoneyWeek Investment Tutorials](https://www.youtube.com/watch?v=nwR5b6E0Xo4)
- [Understanding Futures Margin - Charles Schwab](https://www.youtube.com/watch?v=zPyLCUQdh7I)

## GitHub repositories
- [thequantpy](https://github.com/thequantpy)
- [Algorithmic Trading in Python](https://github.com/nickmccullum/algorithmic-trading-python)
- [Deep Learning Portfolio](https://github.com/Alejandro-Duenas/deep-learning-portfolio)
- [Moon Dev AI Agents for Trading](https://github.com/moondevonyt/moon-dev-ai-agents-for-trading)

## Medium articles
- [Advanced Stock Pattern Prediction Using LSTM with Attention Mechanism](https://drlee.io/advanced-stock-pattern-prediction-using-lstm-with-the-attention-mechanism-in-tensorflow-a-step-by-143a2e8b0e95)
- [How to Create a Sentiment Analysis Model in Python](https://kaabar-sofien.medium.com/how-to-create-a-sentiment-analysis-model-in-python-cf03cb9988e0)
- [How I Found a Simple Way to Use Machine Learning in Stock Trading](https://medium.com/@kaveh.kamali/how-i-found-a-simple-way-to-use-machine-learning-in-stock-trading-6c80795cd95f)
- [Top 10 Quantitative Trading Strategies with Python](https://medium.com/@zodiactrading/top-10-quantitative-trading-strategies-with-python-82b1eff67650)
- [Creating a Scalping Strategy in Python with a 74% Win Rate](https://medium.datadriveninvestor.com/creating-a-scalping-strategy-in-python-with-a-74-win-rate-53a17662ff03)
- [Building a Stock Market Engine from Scratch in Rust (Part I)](https://medium.com/@harshiljani2002/building-stock-market-engine-from-scratch-in-rust-i-9be7c110e137)
- [Algorithmic Trading Guide: High-Frequency Liquidity-Taking Strategy](https://databento.medium.com/algorithmic-trading-guide-high-frequency-liquidity-taking-strategy-f1a04172d5d5)
- [Backtesting the Most Underrated SMA Trading Strategy](https://levelup.gitconnected.com/backtesting-the-most-underrated-sma-trading-strategy-which-beats-the-market-b7a2f588a502)
- [Algorithmically Identifying Stock Price Support & Resistance in Python](https://medium.com/@crisvelasquez/algorithmically-identifying-stock-price-support-resistance-in-python-b9095f9aa279)
- [I Have Just Created a Trading EA Monster](https://liamlincoln.medium.com/i-have-just-created-a-trading-ea-monster-c87a523afe7e)
- [3 Secure Trading Strategies for 2024](https://medium.com/@amaltyagi/3-secure-trading-strategies-for-2024-2a922c5aee64)
- [I Built an Algorithmic Trading System in Rust – Here’s What I Regret](https://medium.com/@austin-starks/i-built-an-algorithmic-trading-system-in-rust-heres-what-i-regret-a89f378b22c9)
- [Architecting a Trading System](https://wire.insiderfinance.io/architecting-a-trading-system-57ee3963e52a)
- [Python for Options Trading #3: A Trade with 100% Probability of Profit](https://medium.com/@rgaveiga/python-for-options-trading-3-a-trade-with-100-probability-of-profit-886e934addbf)
- [Rust in Finance: Building a Scalable High-Frequency Trading Platform](https://medium.com/rustaceans/rust-in-finance-building-a-scalable-high-frequency-trading-platform-from-scratch-339cdf9d6f08)
- [An Algo Trading Strategy That Made 8,371% – A Python Case Study](https://levelup.gitconnected.com/an-algo-trading-strategy-which-made-8-371-a-python-case-study-58ed12a492dc)
- [An In-Depth Guide on Mathematically Improving Your Trading Strategy](https://medium.datadriveninvestor.com/an-in-depth-guide-on-mathematically-improving-your-trading-strategy-fa8ac2a0e5da)

© 2025 Robert Costa. All rights reserved.
