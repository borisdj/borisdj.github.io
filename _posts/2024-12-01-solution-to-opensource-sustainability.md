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

-- **Open-Source** is a great concept and movement and an excellent way to make Software more accessible and usable (check [OS Initiative](https://opensource.org/){:target="_blank"}). It gives everyone better availability for testing, easier debugging and bug fixes. At the same time enables suggestions and improvements with contributions using **PR** (*PullRequest*) based on GitHub collaboration.  
-- But lately, that model often has problems due to some business practices. Some even say that Open Source is [***Broken***](https://www.forbes.com/sites/adrianbridgwater/2019/11/11/is-open-source-broken/?sh=18721f5fd560){:target="_blank"}. So the following proposal is one attempt to find a fix.  

 \* **I**) The first issue is that even big projects depend mostly on one main developer or a handful of significant contributors. At the same time library/package or application can have several million users, both private and legal entities, integrated into free or commercial products. At the same time maintenance often becomes time-consuming with very high expectations and practically requires a full-time job.  
-- Still, it ends up relying mostly on the enthusiasm of the author and their goodwill, since there are never enough donations or financial support from the big companies. Paid support also doesn't usually work and is not scalable, while getting a funding like via [OpenCollective](https://blog.opencollective.com/funds-for-open-source/){:target="_blank"} is always a struggle.  
-- Such dynamics then puts high pressure and burden on the author, leading to burnout and abandoning the project or he becomes unavailable for any reason (including [jail time](https://www.theregister.com/2023/02/15/corejs_russia_open_source/){:target="_blank"}).  
-- This also represents a risk to all the users since they would lose support with no easy replacement. One well known situation was [OpenSSL Heartbleed](https://heartbleed.com/){:target="_blank"} security bug, and another is [log4j](https://medium.com/readme/ghosts-of-log4j-open-source-vulnerabilities-confound-software-developers-e81b931560){:target="_blank"} vulnerabilities. Also in the long term thing for consideration is [governance framework](https://stackoverflow.blog/2020/09/09/open-source-governance-benevolent-dictator-or-decision-by-committee/){:target="_blank"}.

 \* **II**) The second concern is that large corporations are profiting significantly from much of OS software while giving back very little or none at all. They take dozens of OS software and encapsulate it into a commercial proprietary app and some of them make huge incomes. Which is fine as such but there should be a path to have them pay their fair share to the Engineers.  
-- The *Categorical Imperative* ([**moral implications**](https://dev.to/degoodmanwilson/open-source-is-broken-g60){:target="_blank"}) in this case would be those who profit the most should give something back from all the value they are getting with their business in the industry ([Pareto](https://en.wikipedia.org/wiki/Pareto_principle){:target="_blank"} Principle in business model). We can't just consume open source while ignoring the cost, instead everybody should take responsibility and change the culture work toward [sustainability](https://techcrunch.com/2018/06/23/open-source-sustainability/){:target="_blank"}.

-- Criticism without effective solution is not useful or justified. One constructive idea that is getting traction is to make it mostly free while keeping the source open. 'Mostly free' means Free (of charge) for majority (90%+) of users (one criterion yearly gross revenue bellow $ 1 mil.), so it is basically a [**Dual Licensing**](https://duallicensing.com/){:target="_blank"}.  
-- Distinction between Free/Libre and Free (of charge) camps ([**FLOSS and FOSS**](https://www.gnu.org/philosophy/floss-and-foss.en.html){:target="_blank"} philosophy) is that first focuses mainly on Freedom but does not imply zero price in some circumstances (it is not [black-and-white](https://nadh.in/blog/open-source-is-not-broken/){:target="_blank"}).  
-- I call this **cFOSS** - ***conditionally Free and OpenSource Software*** (relatively permissive license type). Note that this is not like the *Source Available* that essentially only allows for code to be read and nothing else.  
-- Instead, **Openness** is retained with freedom to use the code, modify it and distribute as a dependency ([OS term](https://danb.me/blog/why-open-source-term-is-important/){:target="_blank"} is important). This enables [sustainability](https://thenewstack.io/this-week-in-programming-a-manifesto-for-sustainable-open-source-development/){:target="_blank"} and ensures the project survives in the long term. It gives good incentives and creates a self-reinforcing positive loop by encouraging free users to give back via 'code commits'. Additionaly, the paid ones should have simple progressive pricing tiers (based on nuber od Devs or some other metric) with even the top tier not too expensive, to be small cost for such companies.  

-- One could argue that in the long term, all software will have tendencies towards becoming open-sourced, one way or another, since cFOSS as business model has several advantages compared to closed source. Those include better distribution, community licenses that push bottom-up adoption, gratis marketing, etc. To frame it: The [OS won](https://aaronstannard.com/sustainable-open-source-software/){:target="_blank"}.

-- The entire idea is to have 2 categories of Licenses for OS projects depending on the hardship of maintenance:  
**1)** \-The first group would be fully free ([MIT, Apache, BSD](https://opensource.stackexchange.com/questions/11109/what-are-the-practical-differences-between-mit-apache-and-bsd-licenses){:target="_blank"} etc), the default for smaller projects that do not require significant time and effort. Besides initial development, later would need only occasional updates.  
**2)** \-Second **cFOSS** type for larger and more complex ones where it becomes a burden to the developer. And if needed they should be encouraged to switch to these types of license and also project that are from start made in such a manner deserve to be welcomed by the OpenSource community.  

-- Another interesting approach is OpenCore which in base has a core project completely free, but some premium features are paid. I personally am not a fan of such structure, and prefer to keep it as a single unified project - in line with the [KISS](https://en.wikipedia.org/wiki/KISS_principle){:target="_blank"} principle. However, I wouldn't mind others using it, as long as the core component is fully functional for more then half of regular use cases. Still, you can always research ideas about [OS monetisation](https://www.scaleway.com/en/blog/how-to-monetize-your-open-source-project/){:target="_blank"}.

Some notable examples of projects with cFOSS license type or similar structure:  
-- [*ImageSharp*](https://github.com/SixLabors/ImageSharp){:target="_blank"}, -- [*MathParser*](https://github.com/mariuszgromada/MathParser.org-mXparser){:target="_blank"}, -- [*QuestPdf*](https://www.questpdf.com/){:target="_blank"};  
-- [**EfCore.BulkExtensions**](https://github.com/borisdj/EFCore.BulkExtensions){:target="_blank"} - personal Flagship library; last but not least  
' (Free Community License covers most cases, only companies with 1 million+ $ revenue yearly need Commercial)

-- Finaly a Recommendation for everyone to find a project that interest you which you also need and use, and could allocate some spare time to it. Later if you have a problem/idea make your own fully FOSS, and after a few of those one might become cFOSS.  
-- The Rule of thumb would be that 1 in 4 or 5 projects could be significant enough to have cFOSS model besides other fully FOSS (another case of Pareto). Always there is a need to help others with questions, improve documentation and sample, make tests, solve issue, add new functionality and other ways of contribution.  
-- There is useful info on opensource: [/starting-a-project](https://opensource.guide/starting-a-project/){:target="_blank"} and [/getting-paid](https://opensource.guide/getting-paid/){:target="_blank"}.  
-- As for the companies they also can make sure [Open-Source tools are safe](https://www.forbes.com/councils/forbestechcouncil/2022/05/10/12-ways-companies-can-ensure-open-source-tools-are-safe-and-sustainable/){:target="_blank"}.

More info:
1. [medium/the-sustainability-of-open-source](https://goldglovecb.medium.com/the-sustainability-of-open-source-7ec0390f58e8){:target="_blank"}  
2. [dev.to/the-hidden-cost-of-free-open-source](https://dev.to/opensauced/the-hidden-cost-of-free-why-open-source-sustainability-matters-1jk7){:target="_blank"}  
3. [hendrik-erz.de/open-source-has-a-sustainability-crisis](https://hendrik-erz.de/post/open-source-has-a-sustainability-crisis){:target="_blank"}  
4. [unlockopen.com/towards-a-sustainable-solution](https://speaking.unlockopen.com/5JrQdv/towards-a-sustainable-solution-to-open-source-sustainability){:target="_blank"}  

