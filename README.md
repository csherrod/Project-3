# Project-3

## Before I get to answering some of the question regarding the project
* Along with the research of creating a good game and figuring out what tech stack would work best for this type of application we really need to more clearly define what kind of features we need to have to obtain our “MVP”. I think defining that really supersedes everything. I don’t want to get bogged down in doing unnecessary research while we haven’t crystalized what we want the end product to be. 

* First off, the real stock market is enormously complex. Basically you have stocks, bonds, commodities, options and futures and each one of these categories has thousands upon thousands of investment options within them.

* There’s more than one exchange that lists these investment products for sale to the public.

* Let’s just look at a stocks for a second. 

* Stocks can have different share classes. Same company just 2 different share classes with 2 different prices. These shares are used to create other financial products like mutual funds and ETFs which in turn are sold on one of these exchanges. Mutual funds also have different share classes. 

* When you purchase a stock you do so using one of four order types. Some of these order types will create different purchase prices for your ONE order. Want to sell that stock, you got options there that will give you different prices there too. You can even combine some of these order types in a bracket order.

* Some stocks produce dividends based on the corporation’s performance. These dividends are given to shareholders in cash or more shares. Sometimes you don’t have enough shares to warrant a full share in the company so you can actually get a fraction of a share. Which means that you can buy/sell fractions of shares.

* This is just some of the basics of vanilla stocks. You also have short selling, REITs, MLPs, Mortgage Back Securities (financial crisis of 2008), Corporate Bonds, Municipal Bonds, and Options. Call options, Put options, Strike Price, Long Call Option, LEAPs, Spread Options, Straddles, Butterfly Option, American Option, European Option, Exotic Options. You have derivatives, currencies, margin, leverage, penny stocks, dark pools, and just on and on with stuff and things with different names, strategies, financial requirements, tax obligations and tax implications.

* I can’t even wrap my brain around how much data we’re talking about here

* That’s why I think we really need to define our stock market game a little better.

## My Suggestions:
* Instead of worrying about being realistic let’s think more educational, fun, informative, and the best UI out there.

* Let’s start by just eliminating bonds, commodities, options and futures from the game. Most people don’t start learning about the stock market there anyway. Ideally I’d start with just companies in the S&P 500 but not sure if that would be possible. If not, let’s try and just use data from the Nasdaq. If we figure that out we should be able to add in the NYSE later or vice versa but they both have around 3 thousand companies/investment options. 

* To keep it simple I’d like to just use market orders.

* Only update the prices every 15 minutes and do that on a delay since real time data like that costs real money. Also, just on a personal note, there’s no way you’re beating the high frequency traders with your “real time” data when they have direct fiber optic lines from the exchange to their supercomputers running their finely tuned trading algorithms.  So, delay data should be just fine for us.

* Another thing that limiting our scope will do is help us explain why an individual buy or sell doesn’t have a noticeable effect on the price because most, if not all, of those companies have millions of shares. 

* We also need to see how much research we can find out there that we can get to our users because that’s one thing all these investment companies have and sometimes the reason investors will choose one firm over another. That good research isn’t free but maybe we can find something out there. If not building a web scraper to render some recent articles shouldn’t be out of our scope at this point. 

* I’d get rid of short selling and margin as well. If we some other stuff built we can circle back to adding this feature as you play longer, build experience, earn points, level up etc.

* Users start out with X number of dollars to invest and go from there. We can talk about how to keep them engaged but one idea I had was having 2 to 3 computer users that all new users will see as friends. These friends have different trading strategies and maybe even make suggestions. They share their portfolio overview with the user so they can see what they’ve invested in and how they’re doing. If our user start’s to lose money maybe one of their friends made some money and don’t mind giving some of it away to our user if the user can help them out with something.

* Not sure about making that all work but mainly I want to just define our MVP so we can do meaningful work on the project and start compartmentalizing this thing.

* Don’t get overwhelmed with learning the stock market just yet. Let’s talk about what we want this thing to do when we’re done. What’s the goal? Why do people want to use it? Stuff like that. After we make some decisions there we can really dig into the research because we’ll have a much better idea of what we want. 


## Tech Questions
--------------
### What tech stack should we use and why? 
* MERN - because that's what we need to be able to build when we graduate and having a complete MERN app would be great.
* It seems like a lot of financial analysis is done in python but I don't know how much actual analysis we will need to be able to do.
* I still need to do more research but it seems like integrating GraphQL would be beneficial for our app.

* I think Chris Demeke did some great work already related to some of the tech questions so if you haven't started on your own I would start with there:

[check out Chris Demeke](https://github.com/Cdemeke1227/project-three-research/blob/master/README.md)

### What deployment options are there? What are the benefits of the deployment options?
* I think we should try to do AWS. No idea if it's the best but learning to use it will be the most beneficial down the road in my opinion. 

### Who are the competitors? What do they do well? What problems do they have?

### What APIs may benefit for a stock market game?
[check out Chris Demeke](https://github.com/Cdemeke1227/project-three-research/blob/master/README.md)
### What industry related algorithms would we need to use?
[check out Chris Demeke](https://github.com/Cdemeke1227/project-three-research/blob/master/README.md)
# App Idea Questions
------------------

### Benefits of real-world scenarios?
* Users will learn how to actually invest and save money for retirement
### What are the features of a game? How does the theme of a stock market change that?
* Entertaining, engaging, fun, educational. Think of the stock market like gambling. It costs money to play, they're a lot of math involved, there's skill involved, there's stategy, you can lose your money pretty quick if you don't know what you're doing and you can win a lot of money by doing nothing right and just getting lucky

### What legalities play into a stock market game? Into a web application?
* Any web application that stores user data has some legalities to it. I think what kind of different legal questions we might need to ask will depend on what we want our web app to do with the data and how we monetize it. 
### What are the rules for various stock/currency exchanges across the world?
* I don't think we need to worry about the world and all the different exchanges just yet. Let's decide what we want our app to do and then we can look into that. 

### How complicated do we want the game to be?
* Not complicated at all. People won't stick around to play it if it's to complicated to get started.

### Who is our target audience?
* People who don't know anything about investing and want to learn the basics.

### How do we hook people and then eventually make money?
* You need to start out with enough money to make it interesting.
* Give the user friends that we make so they can get tips and see different investment strategies.
* If the user starts losing money maybe our friends our doing well enough to give them some charity to keep them interested.

### Viability of the idea as a money making model?
* Hinges on how addictive you can make the game.

### What would our pricing/business model look like?
* Since most games are free to play these days I don't think we can sell the game.
* I think selling ads might be a way to make some money.
