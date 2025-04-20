---
layout: post
---

Programming is getting cheaper, not just incrementally, but by orders of magnitude. What used to require teams of developers can now be done by a single human working with machine assistance, in a fraction of the time and with a fraction of the cost. And AI programming is improving at a rapid pace.

It is common for folks to discuss the end of programming as a career. But basic economics — and some historical wisdom — says otherwise.

# Some basic economics
We'll start with looking at the most basic economic model: supply and demand.

![Basic Supply-Demand Diagram](/assets/img/basic-supply-demand.svg)

You probably have seen this before: the price is determined by the intersection of the supply and demand curves. To determine whether developers like me are all out of a job, we need to understand what happens when programming gets much cheaper. Economists would say "when the supply of software rises".

![Supply Increase Diagram](/assets/img/supply-increase-diagram.svg)

In the second supply curve, the amount produced at any given price has risen.

If you think about it, there is a neat graphical way to see how much is being spent in these diagrams: the amount spent at any price is the price multiplied by the quantity. And that's the area of this rectangle:

![Area Under Demand](/assets/img/area-under-demand.svg)

So *now* what we’re really asking is: how much does the area under the rectangle change when we shift a good way down the demand curve. In other words, which is the bigger rectangle, *M1* or *M2*?

![Compare Area Under Demand](/assets/img/compare-area-under-demand.svg)

The answer to *that* question depends on the slope of the demand curve.

![Inelastic Demand](/assets/img/inelastic-demand.svg)

In the first case, demand is what economists call *price inelastic*: the quantity doesn't change very fast relative to the price. We can see in this case that M2 is quite a bit smaller than M1 (compare the areas outside of the overlap).

![Elastic Demand](/assets/img/elastic-demand.svg)

On the other hand, when demand is price elastic, the fall in price leads to an increase in the amount demanded. M2 is much bigger than M1.

In the case of software, I believe demand is *extremely* elastic. Lower the cost of software, and we won’t end up with less programming. We’ll end up with everything becoming programmable.

So: the demand for cheaper software will rise dramatically. That's one reason we're not all out of a job.

The other reason is that business adapts surprisingly slowly to new technologies.

# Some economic history

Electrification of industry and better productivity from personal computers took, perhaps surprisingly, decades.

## Electrification of industry took nearly four decades

Edison invented the light bulb in 1878, opened commercial generators in New York and London in 1882. Commercial electric motors were first available in 1883.

By 1900, though, factories still looked like this:

![1900 Factory](/assets/img/factory.png)

There were various reasons why electrification took so long.

Initially, power was used almost entirely for lighting in the morning and evening. By 1897, two thirds of electric companies still provided no daytime service.

Early generators provided DC power, which does not transmit well over long distances, so there had to be many small power plants, rather than large plants and large electric grids that are much more efficient.

Early steam-powered generators were inefficient. It took the widespread deployment of steam turbine generators in the early 20th century and large-scale electric grids in the decade or so after to make electrification inexpensive, reliable and widespread.

At the same time, factories, machines and business processes had to be re-engineered before industrial electrification became widespread.

Electrification of industry, then, was a gradual process over almost four decades.

## Productivity advances from personal computers took two decades

The reasons are less clear, but the deployment of personal computers did not clearly raise business productivity for two decades.

Desktop personal computers became ubiquitous in business in the early 80s, but the earliest credible finding of productivity improvements from IT investment was reported in 1996. Here is a [great, short discussion of the issue by the St. Louis Fed, in 1998](https://www.stlouisfed.org/publications/regional-economist/october-1998/have-computers-made-us-more-productive-a-puzzle).

The reasons are debated. A reasonable general answer is just that business takes time to adapt to new technologies.

Part of why programmers aren't out of a job right away is that business will take time to adapt to new technologies. The old ways will persist for longer than you might expect.

Back to supply and demand.

# The Price Elasticity of Demand for Software is Probably Very High

## Making software usable

How many of the pieces of software you use everyday do you regard as being really well designed and easy to use? Many people will say none.

Let's face it: most software is terrible crap that only just works.

![A bad dialog box](/assets/img/user-locked.png)

As programming gets cheaper, at least some more effort will go into making at least some of our software better. As folks start to use some really usable software and the rest is still terrible, they will start to demand better. People will switch banks because the other bank has a really great website. A virtuous cycle will ensue and there will be a good deal of work making our software more usable. Hooray!

## Computerising the uncomputerised

Companies that lay artificial turf could use a good program to work out what pieces of turf to lay where in order to minimise waste. None exists or is yet contemplated, afaik. There are similar problems in every trade, hobby or recreation.

## Uniting the tribes

The walls between different organisations' websites, databases and services have to come down.

Say I was looking for a house in a new city. I can search (*very crudely*) the recent listings easily. But what I want is to combine that information with all kinds of other information about that city. I really want to add to that list:

- the crime rate in the area;
- the walking and driving distances to the nearest supermarket;
- the associated primary and high schools and information about their quality;
- the recent history of price changes in that area;

and so on. The Real Estate listing company that works out how to make their data open to joining with other databases and services will make a killing.

It's time to bring down the walls we calls "apps" and "websites" (and in some cases, "companies", but we'll get to that).

## Fulfilling the promise of computing

Where are the bicycles for the mind?

Have you ever seen The Mother of all Demos? This was a demonstration of in many ways a modern graphical user interface and services. In 1968. There were things demonstrated in that video that we still can't do conveniently today.

Non-programmers are *grossly* under-served by the software we have today. In the early days, we developed software that let non-programmers do computing. The spreadsheet was the first. Also the personal database.

And there have been some moderately successful attempts at making basic traditional programming accessible to amateurs. The likes of Visual Basic.

But these were all developed decades ago, and their modern equivalents are not massively better than they were back then. There has not been a single major improvement on this problem since maybe 1990.

It is cheaper to write software now. Go write software that will let non-programmers do computing.

## Making software infrastructure good, finally

Software infrastructure is shit.

![Digital Infrastructure](/assets/img/digital-infrastructure.png)

(Courtesy [XKCD](https://xkcd.com/2347/))

Why, in 2025, do payments take days?

![Slow Payments](/assets/img/slow-payments.png)

Our software development and deployment infrastructure and practices are overwhelmingly designed to suit the needs of big business. The small guy can only learn and use so much of this sort of thing at once.

![Kubernetes](/assets/img/kubernetes.png)

A big part of building bycycles for the mind will be making it much simpler and cheaper for people to deploy software, storage, and services. There should be quick, easy and basically free ways to stand up bespoke services that anyone can use.

## Programming is shit

The fancier tools the professionals use aren't great, either. Why is this the state of the art in error handling?

![Log Viewer](/assets/img/log-viewer.png)

Or this, for authentication?

![OAuth](/assets/img/oauth.png)

 Have you ever used a really good LISP or Smalltalk IDE? This is a Smalltalk IDE from 1978.

![Smalltalk 78](/assets/img/smalltalk-78.png)

Do you secretly hate SQL? There was an elegant, simple, much better query language invented in 1977 called (Datalog)[https://en.wikipedia.org/wiki/Datalog].

Here is a query to search for cousins in a database of relations:

```
Sib(x,y) :- Par(x,p) AND Par(y,p) AND x<>y
Cousin(x,y) :- Par(x,xp) AND Par(y,yp) AND Cousin(xp,yp)
```

Here is the equivalent in SQL:

```
WITH  Sib(a,b) AS
   (SELECT p1.c, p2.c
   FROM Par p1, Par p2
	WHERE p1.p = p2.p AND p1.c <> p2.c),
Cousin(x,y) AS
   (SELECT * FROM Sib
       UNION ALL
	SELECT p1.c, p2.c 
	FROM Par p1, Par p2, Cousin
	WHERE p1.p = Cousin.x AND p2.p = Cousin.y)
SELECT DISTINCT * FROM Cousin WHERE x <= y ORDER BY 1,2;
```

One of my greatest puzzlement about the current state of our industry is why HyperCard disappeared. It was the best kind of non-programmer development environment ever developed.

![HyperCard](/assets/img/hypercard.png)

The industry has favoured the industrial over the craftsmanlike for far too long. The opportunities to just actually start using the best ideas of the past, let alone inventing a few more, are endless.

 We can and will spend our newfound programming productivity on making much better programming tools.

## Small business software is particularly shit

Small businesses basically waste thousands or tens of thousands on cookie-cutter, terrible, barely useful websites, both customer-facing and to automate internal processes. Here is a page from a great San Diego small theatre (love you, Powpac!):

![Powpac](/assets/img/powpac.png)

As small business sites go, this is, sadly, relatively decent.

I hope I've made my point. There's so, so much to do. Make programming cheaper and point us at these problems and we can make the world a much better place.

## Developers probably won't be working for Google

The large software companies with their monolithic services will still be around, but they will need far fewer developers than they have now. The layoffs will continue until the bottom line improves.

No, the growth in software work will mostly be in the small, the bespoke, the useful-for-that-one-small-group. Go write the turf laying software. You'll make a fortune!

## Engineering will be closer to management

Note that in a world of faster, cheaper, more flexible programming, companies can more easily adapt their software to their changing needs. This means that management and software development will be much more tightly coupled.

# That's only the beginning

I hope I've convinced you that there is already ample opportunity for gainful employment in the years to come for developers, just making better the digital world we have today.

But of course, we won't have that world. We will, in fact, have a very different world, very soon.

We can't see past the singularity we're entering. But we don't know nothing about what's coming. We can anticipate some of the shape of some of the changes. Hopefully, if we unpack one or two of those, you can see ways in which our social and economic reorganisation will also be opportunities to develop software, because all of these changes will be driven by and with new software.

# Markets

We've already seen a fair amount of this. Uber and AirBnB are reinventions of old markets using technology. There will of course be much more of this.

Perhaps that much is obvious. A brief excursion into the theory of the firm might add some depth to this observation.

In the theory of the firm, the firm exists to reduce the costs of coordination. There is a reson we don't build our cars by bidding every hour for a supply of labour. Rather, we build domains of extra-market cooperation by longer term contract such as employment. Our economy is in fact various semi-authoritarian domains that use markets as a coordination mechanism wherever that is cheaper.

AI affects will move these market boundaries in two ways:

1. Coordination ("management") becomes cheaper and more effective. Fewer employees will be needed. AIs can perform routine middle-manager tasks. The CEO can have a thousand very smart AIs minutely representing their vision throughout the company. Companies that wield large resources that currently require a large management workforce will be much better run with many fewer managers.

2. Non-market coordination mechanisms will *also* become cheaper and more effective. If we all employ AIs that know our business and can negotiate on our behalf, it is likely to become practical to do a great deal more informal neighbourhood sharing. If I need a hammer drill, my AI knows from Jim around the corner's AI that he has a hammer drill I can borrow for the afternoon. AIs will facilitate a great many new, deeper and richer forms of cooperation.

(There are some other ideas coming from humans that could change some things too. Go read about (Dominant Assurance Contracts)[https://en.wikipedia.org/wiki/Assurance_contract], for example.)

The boundaries between the market, the firm, the government, consumers and the community are about to go all over the place.

## Non-markets

There will also be entirely new kinds of economic organisation:

- smart contracts (e.g. Ethereum);
- new types of goods (e.g. place-based digital goods as in (Pokémon Go)[https://en.wikipedia.org/wiki/Pokémon_Go]);
- new types of markets (e.g. fractional ownership services like (Masterworks)[https://www.masterworks.com] and (Rally)[https://rallyrd.com]
- deep dynamic pricing
- reputation systems.
- synthetic cooperatives — AI-mediated collectives that self-organize around shared goals.
- personal economic agents — AIs that manage your labor, attention, data, or intellectual property.
- post-firm production — where systems of value creation look more like networks, guilds, or swarms than balance sheets and reporting chains.

Can we reinvent the committee? Fix HOAs?

How about Government? Fast feedback loops, closer monitoring, more participation.

Won't it be fun building software that facilitates a world of greater sharing?

# And everything else, really

AI will upend education, science, healthcare, law (Smart contracts! AI rights!), and our physical enviroment. Your city should have an API.

Politics. Perhaps better not to think about that one for now.

# Conclusion

A world of rapid change that is almost entirely driven by and enabled by software is not one in which programmers will be idle.