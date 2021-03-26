# Real Time First Price Auctions Machine Learning

# Table Of Contents
-  [Project Structure Overview](#project-structure-overview)
-  [Introduction](#introduction)
-  [Problem Statement](#problem-statement)
-  [Questions](#questions)
-  [Version](#version)
-  [Author](#author)

<br/>

### Project Structure Overview
```
├── Real Time First Price Auctions Machine Learning
|  ├── data          - this folder contains training data.
|  │    └── Auction_Dataset.csv
|  │
└───── Real Time First Price Auctions.ipynb
```

<br/>

### Introduction

60% of the digital ad inventory is sold by publishers in **Real-Time first price Auctions.** Once a user lands on a webpage, bidders (advertisers) bid for different ad slots on the page, and the one with the highest winning bid displays their ad in the ad space and pays the amount he bid. This process encourages bid shading – bidding lesser than the perceived value of the ad space to maximize utilization for self while maintaining a particular win rate at the lowest prices. 

Hence, for publishers, it becomes important to value their inventory (all the users that visit their website * all the ad slots they have on their websites) correctly so that a reserve price or a minimum price can be set up for the auctions. The minimum price

<hr/>

### Problem Statement

In a first-price auction, the highest bidder wins and pays the price they bid if it exceeds the reserve price. The optimal strategy of a bidder is to shade their bids (bid less than their true value of the inventory). However, the bidder needs to win a certain amount to achieve their goals. This 
suggests they need to shade as much as possible while maintaining a certain win rate.

A bidder perceives a certain value out of every impression they win. Each bidder would like to 
maintain the value they derived out of this set of websites (given in the dataset) in June with a 
the maximum deviation of 20%. 

Setting a reserve price induces this by causing bidders to lose at lower bids which encourages higher bidding and more publisher revenue. However, since most of these take place through 
automated systems, there might be an unknown delay in setting reserve prices & reducing the win rate of bidder & bidder changing their bid shading algorithm & increased publisher revenue.

<hr/>

### Questions
1. What are the reserve prices that one can set? 
2. What is the potential revenue range our publisher can make in July?

<hr/>
<br/>

## Version

1.0.0 

<br/>

## Author

* **Rahul Gaikwad** - Initial work and development

<br/>
