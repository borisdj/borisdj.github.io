---
title: "Solution to OpenSource Sustainability"
date: 2024-12-01T00:00:00-00:00
categories: [tech]
tags: [OS, OpenSource, Solution, Sustainability]
classes: wide
excerpt: "proposal to fix the 'broken' OS"
---

-- **Open Source** is a great concept and excellent way for making Software more accessible and usable (check [OS Initiative](https://opensource.org/){:target="_blank"}).  
It gives everyone better availability for testing, easier debugging and bug fixes. At the same time enables suggestions for improvements and overall contributions with PR (PullRequest) based on GitHub collaboration.  
But lately that model often have problems due to some business practices. Some even say that Open Source is [Broken](https://www.forbes.com/sites/adrianbridgwater/2019/11/11/is-open-source-broken/?sh=18721f5fd560){:target="_blank"}.  
So following proposal is one attempt to find a fix.  

First issue is that even big projects depends mostly on one main developer or handful significant contributors.  
At the same time library/package or application can have several million users, both private and legal entities, either for free or commercial products.  
And often maintenance becomes very time consuming and practically requires a full time job.  
Still it ends up relying mostly on enthusiasm of author and their good will, since there is never enough donations nor financial suport from the big companies. Paid support also does not work usually and is not scalable.  
This then puts high pressure on the author, either to burn out or abandon the project, or becomes unavailable for any reason.  
This also represents a risk to all the users since they would lose support with no easy replacement.  
Notable examples are [OpenSSL Heartbleed](https://heartbleed.com/){:target="_blank"} security bug,

Second concern is that large corporation are profiting significantly from many OS software while giving back very litle or non at all.  
They take dozens of OS software and encapsulate it into a commercial proprietary app and some of them make large revenues.  
Which is fine as such but there should be a path to have them pay their fair share to the Devs.  
Categorical imperative in this case would be those who profits the most should give something back from all the value they are getting with their business in the industry ([Pareto](https://en.wikipedia.org/wiki/Pareto_principle){:target="_blank"} Principle in business model).  
We can't just consume open source while ignoring the cost, instead enerybody should take responsibility and change the culture work toward [sustainability](https://techcrunch.com/2018/06/23/open-source-sustainability/){:target="_blank"}.

Criticism without effective solutions are not useful nor justified.  
One constructive idea that is getting traction is to make it mostly free while keeping it the source open.  
'Mostly free' means Free (of charge) for majority of users, so it is basically a [Dual Licensing](https://duallicensing.com/){:target="_blank"}.
Here is a distinction between Free (of charge) and Free/Libre camps ([FLOSS and FOSS](https://www.gnu.org/philosophy/floss-and-foss.en.html){:target="_blank"}).
Even the paid ones should have simple progressive pricing tiers with rounded amount (do not use amont such as 799, plain 800 is just fine).  
I call this **cFOSS** - *conditionally Free and OpenSource Software*.  
Note that this is not like source Available that essentially only allowes for code to be read and nothing else.  
Instead Openness is retained with freedom to use the code, modify it and distribute it as a dependency ([OS term](https://danb.me/blog/why-open-source-term-is-important/){:target="_blank"} important).  
This enables/creates [sustainability](https://thenewstack.io/this-week-in-programming-a-manifesto-for-sustainable-open-source-development/){:target="_blank"} and ensures project survies in the long term.  
It gives good incentives and creates self-reinforcing positive loop by encouraging free users to give back via 'code commits'.  
And even the paid ones should have simple progressive pricing tiers with rounded amount (don no use 999, plain 1000 is just fine).  
One could argue that in the long term all software will become open sourced, one way or another, just because of tendencies, since cFOSS as business model has several advantages compared to closed source. Those include better distribution, community licenses that pushes bottom up addoption, gratis marketing, etc. To frame it: The [OS won](https://aaronstannard.com/sustainable-open-source-software/){:target="_blank"}.

Entire idea is to have 2 categories of Licenses for OS project depending on hardship of maintenance.
-- First group would be fully free ([MIT, Apache, BSD](https://opensource.stackexchange.com/questions/11109/what-are-the-practical-differences-between-mit-apache-and-bsd-licenses){:target="_blank"} etc), default for smaller projects that do not require significant time and efforts. Besides initial development, later would need only occasional updates.  
-- Second cFOSS type for larger and complex ones where it becomes burden to developer. And if needed they should be encourages to switch to these types of license and also all project that are from start made in such manner are to be welcomed into the OpenSource community.  

Another interesting approach is OpenCore which in base has core project completely free, but some premium features are paid.  
I'm personally not fan of such structure, and prefer  to keep it as single unified project - [KISS](https://en.wikipedia.org/wiki/KISS_principle){:target="_blank"} principle, but don't mind others using it as long as core componente is fully functional for more then half situations.
And you can always reasearch ideas about [OS monetisation](https://www.scaleway.com/en/blog/how-to-monetize-your-open-source-project/){:target="_blank"}.

*- PS Last but Not Least  
For start find a project that interest you which you also need and use, and could allocate some spare time to it.
Later if you have a problem/idea make your own fully FOSS, and after a few of those one might become cFOSS.
Rule of thumnb would be that 1 in 4 or 5 projects could be significabt enought to have cFOSS model besides other fully FOSS (another case of Pareto).
There are always needs in helping others with questions, improving documentation and sample, making tests, solving different issue, adding new functionality and other ways of contibution.  

