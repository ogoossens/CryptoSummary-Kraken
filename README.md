# CryptoSummary!
A node.js project for checking the value of your investments in cryptocurrencies

Hosted on Heroku under : http://cryptosummary.herokuapp.com

![Alt text](http://cryptosummary.herokuapp.com/screenshot.png)

The idea was - as a cryptocurrency investor I always had to log in to my traders account to see my winnings / losses / development on my investments and I tought - that's unnecessary.

So I build a node.js app that takes in URL parameters about your open positions - checks and compares the values when you bought it and the current ones and outputs a total summary so you know where unstand 

# Sample URL
http://cryptosummary.herokuapp.com/?1=XRPEUR*10000*0.19&2=LTCEUR*15*38&3=XBTEUR*1.5*2000

# URL BUILDing - build once, save as bookmark forever
http://cryptosummary.herokuapp.com/? +
and now as many open positions (1= & 2=) as you need, save as bookmark and open anytime anywhere

Format: <currency_pair>*<amount_bought>*<bought_at_price>

# Supported
Currency: EUR

Crypto: XBT, ETH, XRP, LTC, BCH, ETC, DASH, EOS

This was build for my use - should you need and require more pairs/currencies Ill add them, or just make a pull request :P

# Few side notes\
* Actually your coins can be stored anywhere, your wallet or traders wallet - does not matter :-)

* You can use any exchange - Im just pulling the current values from Kraken API so there might be some differences to your trader


This is more or less just an calculator to see the pro- or regress of the value of coins you bought

# Security
Thats the neat point, Im woking with public Kraken API and the only thing you specify is : HOW MUCH of WHAT did you buy AT WHICH PRICE and non of that info is considered "dangerous" in my opinion
