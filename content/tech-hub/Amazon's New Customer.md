---
Date of creation: 2025-07-31
Source: https://stratechery.com/2017/amazons-new-customer/
tags:
  - Stratechery
Last Modified: 2025-07-31
---


**If you don’t understand a company’s goals, how can you know what its strategies and tactics will be?**

# Amazon’s Goal

> [!important]
> In the case of Amazon, the company stated [in its 1997 S-1](http://www.nasdaq.com/markets/ipos/filing.ashx?filingid=1249014):
> 
> > Amazon.com’s objective is to be the leading online retailer of information-based products and services, with an initial focus on books.
> 

> [!important]
> Within a few years Amazon’s updated mission statement [reflected the reality of the company’s e-commerce ambitions](https://web.archive.org/web/20030804040525/http://phx.corporate-ir.net/phoenix.zhtml?c=97664&p=irol-faq):
> 
> > Our vision is to be earth’s most customer centric company; to build a place where people can come to find and discover anything they might want to buy online.
> 

> [!important]
>  “Anything they might want to buy online” was pretty broad; the advent of Amazon Web Services a few years later showed it wasn’t broad enough, and a few years ago Amazon reduced its stated goal to just that first clause: 
> 
> > We seek to be Earth’s most customer-centric company_. 

> [!important]
> There are no more bounds.



# Amazon's Strategy

> [!important]
> Amazon’s goal is to take a cut of all economic activity.

> [!important]
> Amazon has several different strategies (to reach its goal).
> 
> The **key to the enterprise** is **AWS**: if it is better to build an Internet-enabled business on the public cloud, and if all businesses will soon be Internet-enabled businesses, it follows that AWS is well-placed to take a cut of all business activity.
> 
> On the **consumer side** the key is **Prime**. While Amazon has [long pursued a dominant strategy](https://stratechery.com/2013/amazons-dominant-strategy/) in retail — superior cost _and_ superior selection — it is difficult to build sustainable differentiation on these factors alone. After all, another retailer is only a click away.
> 
> This, though, is the brilliance of Prime: thanks to its reliability and convenience (two days shipping, sometimes faster!), plus human fallibility when it comes to considering sunk costs (you’ve already paid $99!), why even bother looking anywhere else? With Prime Amazon has created a powerful moat around consumer goods that does not depend on simply having the lowest price, because Prime customers don’t even bother to check.


> [!important]
> Different parts of the company — like AWS and Prime — were on a conceptual level more similar than you might think, and that said concepts were rooted in the very structure of Amazon itself.
> Explained in [[The Amazon Tax]]*

![[amz_aws_strategy.png]]

> [!important]
> The “primitives” model modularized Amazon’s infrastructure, effectively transforming raw data center components into storage, computing, databases, etc. which could be used on an ad-hoc basis not only by Amazon’s internal teams but also outside developers.
> The AWS layer in the middle has several key characteristics:
> 
> - AWS has massive fixed costs but benefits tremendously from economies of scale
> - The cost to build AWS was justified because the first and best customer is Amazon’s e-commerce business
> - AWS’s focus on “primitives” meant it could be sold as-is to developers beyond Amazon, increasing the returns to scale and, by extension, deepening AWS’ moat
> 
> This last point was a win-win: developers would have access to enterprise-level computing resources with zero up-front investment; Amazon, meanwhile, would get that much more scale for a set of products for which they would be the first and best customer.


![[amz_prime_strategy.png]]

> [!important]
> Prime is a super experience with superior prices and superior selection, and it too feeds into a scale play...The same structure as AWS — and it shares similar characteristics:
> 
> - E-commerce distribution has massive fixed costs but benefits tremendously from economies of scale
> - The cost to build-out Amazon’s fulfillment centers was justified because the first and best customer is Amazon’s e-commerce business
> - That last bullet point may seem odd, but in fact 40% of Amazon’s sales (on a unit basis) are sold by 3rd-party merchants; most of these merchants leverage Fulfilled-by-Amazon, which means their goods are stored in Amazon’s fulfillment centers and covered by Prime. This increases the return to scale for Amazon’s fulfillment centers, increases the value of Prime, and deepens Amazon’s moat


> [!important]
> As I noted in that piece, you can see the outline of similar efforts in logistics: Amazon is building out a delivery network with itself as the first-and-best customer; in the long run it seems obvious said logistics services will be exposed as a platform.



# Amazon's Tactics

> [!important]
> This, though, is why groceries is a strategic hole: not only is it the largest retail category, it is the most persistent opportunity for other retailers to gain access to Prime members and remind them there are alternatives. That is why Amazon has been so determined in the space: AmazonFresh launched a decade ago, and unlike other Amazon experiments, has continued to receive funding along with other rumored initiatives like convenience store and grocery pick-ups. Amazon simply hasn’t been able to figure out the right tactics.

> [!important]
> The mistake Mackey made: while he rightly understood that Amazon was going to do everything possible to win in groceries — the category accounts for about 20% of consumer spending — he presumed that the effort would be limited to e-commerce. E-commerce, though, is a tactic; 
> ...it doesn’t even rise to strategy.



> [!important]
> To understand why groceries are such a challenge look at how they differ from books, Amazon’s first product:
> 
> - There are far more books than can ever fit in a physical store, which means an e-commerce site can win on selection; in comparison, there simply aren’t that many grocery items (a typical grocery store will have between 30,000 and 50,000 SKUs)
> - When you order a book, you know exactly what you are getting: a book from Amazon is the same as a book from a local bookstore; groceries, on the other hand, can vary in quality not just store-to-store but, particularly in the case of perishable goods, day-to-day and item-to-item
> - Books can be stored in a centralized warehouse indefinitely; perishable groceries can only be stored for a limited amount of time and degrade in quality during transit



> [!important]
> Groceries is a fundamentally different problem that needs a fundamentally different solution;
> AmazonFresh was at a cost disadvantage to physical grocers as well: in order to be competitive AmazonFresh needed to stock a lot of perishable items; however, as long as AmazonFresh was not operating at meaningful scale a huge number of those perishable items would spoil. And, given the inherent local nature of groceries, scale needed to be achieved not on a national basis but a city one.
> 

> [!important] The Whole Foods Acquisition
>  From the outside it may seem that Amazon is buying a retailer. The truth, though, is that Amazon is buying a _customer_ — the first-and-best customer that will instantly bring its grocery efforts to scale.
> Today, all of the logistics that go into a Whole Foods store are for the purpose of stocking physical shelves: the entire operation is integrated.


![[amz_wholefoods_strategy.png]]

> [!important]
> What I expect Amazon to do over the next few years is transform the Whole Foods supply chain into a service architecture based on primitives: meat, fruit, vegetables, baked goods, non-perishables (Whole Foods’ outsized reliance on store brands is something that I’m sure was very attractive to Amazon).



In the long run, physical grocery stores will be only one of Amazon Grocery Services’ customers: obviously a home delivery service will be another, and it will be far more efficient than a company like Instacart trying to layer on top of Whole Foods’ current integrated model.



I suspect Amazon’s ambitions stretch further, though: Amazon Grocery Services will be well-placed to start supplying restaurants too, gaining Amazon access to another big cut of economic activity. It is the AWS model, which is to say it is the Amazon model, but like AWS, the key to profitability is having a first-and-best customer able to utilize the massive investment necessary to build the service out in the first place.


Unlike Whole Foods Amazon has no particular desire to be a grocer, and contrary to conventional wisdom the company is not even a retailer. At its core Amazon is a services provider enabled — and protected — by scale.
