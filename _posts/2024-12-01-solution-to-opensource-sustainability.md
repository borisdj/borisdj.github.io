---
title: "Solution to OpenSource Sustainability"
date: 2024-12-01T00:00:00-00:00
categories: [tech]
tags: [OS, OpenSource, Solution, Sustainability]
classes: wide
excerpt: "proposal to fix the 'broken' OS"
---

![/solution-to-opensource-sustainability](https://raw.githubusercontent.com/borisdj/borisdj.github.io/main/assets/images/solution-to-opensource-sustainability/OS.jpg)

<center>QR Link</center>
![QR Link](https://quickchart.io/qr?text=https://infopedia.io/solution-to-opensource-sustainability/)

-- **Open-Source** is a great concept and movement and an excellent way to make Software more accessible and usable (check [OS Initiative](https://opensource.org/){:target="_blank"}).  
It gives everyone better availability for testing, easier debugging and bug fixes. At the same time enables suggestions for improvements and overall contributions with PR (PullRequest) based on GitHub collaboration.  
But lately, that model often has problems due to some business practices. Some even say that Open Source is [Broken](https://www.forbes.com/sites/adrianbridgwater/2019/11/11/is-open-source-broken/?sh=18721f5fd560){:target="_blank"}. So following proposal is one attempt to find a fix.  

-- The first issue is that even big projects depend mostly on one main developer or a handful of significant contributors.  
At the same time library/package or application can have several million users, both private and legal entities, either for free or commercial products.  
And often maintenance becomes very time-consuming and practically requires a full-time job.  
Still, it ends up relying mostly on the enthusiasm of the author and their goodwill, since there are never enough donations or financial support from the big companies. Paid support also does not work usually and is not scalable, finding a funding like [OpenCollective](https://blog.opencollective.com/funds-for-open-source/){:target="_blank"} is always a struggle.  
This then puts high pressure on the author, leading to burnout and/or him abandoning the project or becomes unavailable for any reason (including [jail](https://www.theregister.com/2023/02/15/corejs_russia_open_source/){:target="_blank"}).  
This also represents a risk to all the users since they would lose support with no easy replacement.  
One well known situation was [OpenSSL Heartbleed](https://heartbleed.com/){:target="_blank"} security bug, and another is [log4j](https://medium.com/readme/ghosts-of-log4j-open-source-vulnerabilities-confound-software-developers-e81b931560){:target="_blank"} vulnerabilities. 
And in the long term thing for consideration is [governance framework](https://stackoverflow.blog/2020/09/09/open-source-governance-benevolent-dictator-or-decision-by-committee/){:target="_blank"}.

-- The second concern is that large corporations are profiting significantly from many OS software while giving back very little or none at all.  
They take dozens of OS software and encapsulate it into a commercial proprietary app and some of them make large revenues.  
Which is fine as such but there should be a path to have them pay their fair share to the Devs.  
The categorical imperative ([moral implications](https://dev.to/degoodmanwilson/open-source-is-broken-g60){:target="_blank"}) in this case would be those who profit the most should give something back from all the value they are getting with their business in the industry ([Pareto](https://en.wikipedia.org/wiki/Pareto_principle){:target="_blank"} Principle in business model).  
We can't just consume open source while ignoring the cost, instead enerybody should take responsibility and change the culture work toward [sustainability](https://techcrunch.com/2018/06/23/open-source-sustainability/){:target="_blank"}.

-- Criticism without effective solution is not useful or justified.  
One constructive idea that is getting traction is to make it mostly free while keeping the source open.  
'Mostly free' means Free (of charge) for majority (90%+) of users, so it is basically a [Dual Licensing](https://duallicensing.com/){:target="_blank"}.
Distinction between Free/Libre and Free (of charge) camps ([FLOSS and FOSS](https://www.gnu.org/philosophy/floss-and-foss.en.html){:target="_blank"} philosophy) is that first focuses mainly on Freedom but does not imply zero price in some circumstances (it is not [black-and-white](https://nadh.in/blog/open-source-is-not-broken/){:target="_blank"}).
In addition even the paid ones should have simple progressive pricing tiers with rounded amount (do not use number such as 799, plain 800 is just fine).  
I call this **cFOSS** - *conditionally Free and OpenSource Software*.  
Note that this is not the like source Available essentially only allows for code to be read and nothing else.  
Instead, Openness is retained with freedom to use the code, modify it and distribute it as a dependency ([OS term](https://danb.me/blog/why-open-source-term-is-important/){:target="_blank"} important).  
This enables/creates [sustainability](https://thenewstack.io/this-week-in-programming-a-manifesto-for-sustainable-open-source-development/){:target="_blank"} and ensures the project survives in the long term.  
It gives good incentives and creates a self-reinforcing positive loop by encouraging free users to give back via 'code commits'.  
Even the paid ones should have simple progressive pricing tiers with rounded amount (don no use 999, plain 1000 is just fine).  

One could argue that in the long term, all software will have tendencies to become open-sourced, one way or another, since cFOSS as business model has several advantages compared to closed source. Those include better distribution, community licenses that push bottom-up adoption, gratis marketing, etc. To frame it: The [OS won](https://aaronstannard.com/sustainable-open-source-software/){:target="_blank"}.

The entire idea is to have 2 categories of Licenses for OS projects depending on the hardship of maintenance.  
-- The first group would be fully free ([MIT, Apache, BSD](https://opensource.stackexchange.com/questions/11109/what-are-the-practical-differences-between-mit-apache-and-bsd-licenses){:target="_blank"} etc), the default for smaller projects that do not require significant time and effort. Besides initial development, later would need only occasional updates.  
-- Second cFOSS type for larger and more complex ones where it becomes a burden to the developer. And if needed they should be encouraged to switch to these types of license and also project that are from start made in such a manner deserve to be welcomed by the OpenSource community.  

-- Another interesting approach is OpenCore which in base has a core project completely free, but some premium features are paid.  
I personally am not a fan of such structure, and prefer to keep it as a single unified project - the [KISS](https://en.wikipedia.org/wiki/KISS_principle){:target="_blank"} principle, but don't mind others using it as long as the core component is fully functional for more then half of regular use cases.
And you can always reasearch ideas about [OS monetisation](https://www.scaleway.com/en/blog/how-to-monetize-your-open-source-project/){:target="_blank"}.

Some notable example of projects with cFOSS license type or similar structure:  
[ImageSharp](https://github.com/SixLabors/ImageSharp){:target="_blank"}, [MathParser](https://github.com/mariuszgromada/MathParser.org-mXparser){:target="_blank"}, [QuestPdf](https://www.questpdf.com/){:target="_blank"};  
Last but Not Least, a personal one: [EfCore.BulkExtensions](https://github.com/borisdj/EFCore.BulkExtensions){:target="_blank"} - Flagship library  
(Free Community License cover most cases, only companies with over 1 million $ revenue per year need to pay for Commercial one)

** Finaly a Recommendation for everyone to find a project that interest you which you also need and use, and could allocate some spare time to it.
Later if you have a problem/idea make your own fully FOSS, and after a few of those one might become cFOSS.
The Rule of thumb would be that 1 in 4 or 5 projects could be significant enough to have cFOSS model besides other fully FOSS (another case of Pareto).
Always there is a need to help others with questions, improve documentation and sample, make tests, solve issue, add new functionality and other ways of contribution. There is useful info on opensource: [/starting-a-project](https://opensource.guide/starting-a-project/){:target="_blank"} and [/getting-paid](https://opensource.guide/getting-paid/){:target="_blank"}.  
As for the companies they also can ensure [Open-Source tools are safe](https://www.forbes.com/councils/forbestechcouncil/2022/05/10/12-ways-companies-can-ensure-open-source-tools-are-safe-and-sustainable/){:target="_blank"}.

More info:
1. [medium/the-sustainability-of-open-source](https://goldglovecb.medium.com/the-sustainability-of-open-source-7ec0390f58e8){:target="_blank"}  
2. [dev.to/the-hidden-cost-of-free-open-source](https://dev.to/opensauced/the-hidden-cost-of-free-why-open-source-sustainability-matters-1jk7){:target="_blank"}  
3. [hendrik-erz.de/open-source-has-a-sustainability-crisis](https://hendrik-erz.de/post/open-source-has-a-sustainability-crisis){:target="_blank"}  
4. [unlockopen.com/towards-a-sustainable-solution](https://speaking.unlockopen.com/5JrQdv/towards-a-sustainable-solution-to-open-source-sustainability){:target="_blank"}  

