---
title: "Solution to OpenSource sustainability (SOSs) - cFOSS"
date: 2024-12-01T00:00:00-00:00
categories: [tech]
tags: [OS, OpenSource, Solution, Sustainability]
classes: wide
excerpt: "proposal to fix the 'broken' OS"
---

LANG(jezik): Global (en-us) / [Local](https://infopedia.io/sr-latn/solution-to-opensource-sustainability/) (sr-latn)  
Short article: [medium/cfoss](https://medium.com/@borisdj/cfoss-as-a-solution-to-opensource-sustainability-soss-e890419d70d2){:target="_blank"}  

![/solution-to-opensource-sustainability](https://raw.githubusercontent.com/borisdj/borisdj.github.io/main/assets/images/solution-to-opensource-sustainability/OS2.jpg)

&nbsp; **Open-Source** ([img](https://3dnature.com/downloads/open-source/){:target="_blank"}) is a great concept and movement and an excellent way to make Software more accessible and usable (check [OS Initiative](https://opensource.org/){:target="_blank"}). It gives everyone better availability for testing, easier debugging and bug fixes. At the same time enables suggestions and improvements with contributions using **PR** (*PullRequest*) based on GitHub collaboration. But lately, that model often has its own challenges and problems due to some business practices. Some even say that Open Source is [***Broken***](https://www.forbes.com/sites/adrianbridgwater/2019/11/11/is-open-source-broken/?sh=18721f5fd560){:target="_blank"}. So the following proposal is an attempt to find a fix.  
But first to address two major issues:  

**1) Single Person Dependency**  
&nbsp; The first matter is that even big projects depend mostly on main developer (one man show) or a handful of significant contributors. At the same time software package or program can have several million users, both private and legal entities, and be used in many applications. However, maintenance often becomes time-consuming with very high expectations and practically requires a full-time job.  
Still, it ends up relying mostly on the enthusiasm and goodwill of the author, since there are never enough donations or financial support from the big companies. Also, paid support usually doesn't work and is not scalable, while getting a funding like via [OpenCollective](https://blog.opencollective.com/funds-for-open-source/){:target="_blank"} is always a struggle.  
&nbsp; Such dynamics then puts high pressure and burden on the author, leading to Burnout and abandoning the project or he/she becomes unavailable for any reason (including [imprisonment](https://www.theregister.com/2023/02/15/corejs_russia_open_source/){:target="_blank"}).  
This situation represents a risk to all users since they would lose support with no easy replacement. One well known situation was [OpenSSL Heartbleed](https://heartbleed.com/){:target="_blank"} security bug, and another is [log4j](https://medium.com/readme/ghosts-of-log4j-open-source-vulnerabilities-confound-software-developers-e81b931560){:target="_blank"} vulnerabilities. Also, in the long term issue for consideration is [governance framework](https://stackoverflow.blog/2020/09/09/open-source-governance-benevolent-dictator-or-decision-by-committee/){:target="_blank"}. In conclusion, it is rational for companies to pay the small fee and fund the maintainer(s), since it is in their own interest to have better insurance for LTS - *Long Term Support*. Selection/survival is part of software evolution process. If project grows beyond hobby  scope of being a hoby it either dies or obtains proper support and funding.

**2) Corporate Exploitation**  
&nbsp; The second concern is that large corporations are profiting significantly from much of OS Software while giving back very little or none at all. They take dozens of OSS and encapsulate it into a commercial proprietary app or service, and on top of that some of them make huge incomes. Which is fine as such but there should be a way to have them pay their fair share to the Engineers behind those projects.  
&nbsp; *Categorical Imperative* ([**moral implications**](https://dev.to/degoodmanwilson/open-source-is-broken-g60){:target="_blank"}) in this case would be that those who profit the most should give something back from all the value they get with their business in the industry ([Pareto](https://en.wikipedia.org/wiki/Pareto_principle){:target="_blank"} Principle in business model). We can't just consume open source while ignoring the cost, instead everybody should take responsibility and change the work culture toward [sustainability](https://techcrunch.com/2018/06/23/open-source-sustainability/){:target="_blank"}.

**Model Explanation**  
&nbsp; One constructive idea that is getting traction is to make it mostly free while keeping the source open. 'Mostly free' means zero cost for majority (80 to 90%+) of users, such as those with yearly gross revenues below certain limit, like 500 K or $1 million. Essentially, this approach mirrors a [**Dual Licensing**](https://duallicensing.com/){:target="_blank"} strategy.  
&nbsp; I call this **cFOSS** - ***conditionally Free and OpenSource Software***, relatively permissive license type with loosely enforced funding (custom OpenSource Protocol). Note that this is not like the *Source Available* (or Public Source) which essentially only allows for code to be read and nothing else, almost [meaningless](https://keygen.sh/blog/source-available-is-meaningless/){:target="_blank"} ([OS term](https://danb.me/blog/why-open-source-term-is-important/){:target="_blank"} is important).  
Instead, **Openness** is retained with freedom to use the code, modify it and distribute as a dependency.  
&nbsp; It enables [sustainability](https://thenewstack.io/this-week-in-programming-a-manifesto-for-sustainable-open-source-development/){:target="_blank"} (subsidizing alike) and ensures that project can survive in the long term. What's more, gives good incentives and creates a self-reinforcing positive loop by encouraging users to contribute via 'code commits'. Additionaly, pricing should be progressive but with simple tiers (based on number of Devs but in groups or some other metric). And even the top tier should not be too expensive, to be easily acceptable cost for such companies and proportional to the value they receive. For example, tiers could be in range from several hundreds to a few thousand for annual subscription, or alternatively to also have an option for perpetual (permanent) license. Regular funding would also make it possible to have a reward model for impactful collaborators. 
Also when setting prices please avoid amounts like 999 (stay away from psychology of 'advertising'), instead use rounded numbers, plain 1000 is fine. Finally, you can consider accepting *Bitcoin* as payment, as it aligns with the principles *OpenSource Money* (more info in previous blog posts).

&nbsp; One could argue that in the long term, all software will have tendencies (converges) towards becoming open-sourced. The reason being is that cFOSS as business model has several advantages compared to closed source. Those include better distribution, community licenses that push bottom-up adoption, gratis marketing, etc. To frame it as: The [OS won](https://aaronstannard.com/sustainable-open-source-software/){:target="_blank"}.    
For sceptics, to add that criticism without effective solution is neither useful nor justified.  

&nbsp; Ultimately we could group Licenses for OS projects into 2 categories, depending on the hardship of maintenance:  
1) The first group would be fully free ([MIT, Apache, BSD](https://opensource.stackexchange.com/questions/11109/what-are-the-practical-differences-between-mit-apache-and-bsd-licenses){:target="_blank"} etc), the default for smaller projects that do not require significant time and effort. Besides initial development, later would need only occasional updates.  
2) Second **cFOSS** type for larger and more complex projects where it becomes a burden to the developer. And if needed they should be encouraged to switch to these types of licenses (path from projects to products). Also code repositories that are from start made in such a manner deserve to be welcomed by the OpenSource community. Of course, in situations where there was a change anyone can fork the last fully free version and continue maintaining on their own, but it is not an easy endeavor.

&nbsp; Also to mention that distinction between 'Free-Libre' and 'Free (of charge) as in beer' camps ([**FLOSS and FOSS**](https://www.gnu.org/philosophy/floss-and-foss.en.html){:target="_blank"} philosophy) is that first focuses mainly on Freedom but does Not imply no cost in all circumstances (it is not [black-and-white](https://nadh.in/blog/open-source-is-not-broken/){:target="_blank"}).  
&nbsp; Another interesting approach is *OpenCore* which in base has a core project completely free, but some premium features are paid. Personally, I am not a fan of such structure, and prefer to keep it as a single unified project - in line with the [KISS](https://en.wikipedia.org/wiki/KISS_principle){:target="_blank"} principle. However, I wouldn't mind others using it, as long as the core component is fully functional for more then half of regular use cases. Still, you can always research ideas about [OS monetization](https://www.scaleway.com/en/blog/how-to-monetize-your-open-source-project/){:target="_blank"} - [best platforms](https://blog.stackademic.com/the-best-platforms-for-monetizing-your-open-source-projects-in-2024-2025-1b7803ea5bc9){:target="_blank"} and find curious stories.

Some notable examples of projects with cFOSS license type or similar design:  
-- [*ImageSharp*](https://github.com/SixLabors/ImageSharp){:target="_blank"}, -- [*MathParser*](https://github.com/mariuszgromada/MathParser.org-mXparser){:target="_blank"}, -- [*QuestPdf*](https://www.questpdf.com/){:target="_blank"}, -- [MediatR](https://github.com/LuckyPennySoftware/MediatR){:target="_blank"};  
-- [**EFCore.BulkExtensions**](https://github.com/borisdj/EFCore.BulkExtensions){:target="_blank"} - personal Flagship library (this blog post grew from the Bulk saga)  
' (Free Community License covers most cases, only companies with $1 million+ revenue yearly need Commercial)

More systemic approach, would be to have several Foundations that would collect donations for popular fullyFree projects and even do billing for payed cF licenses from large Companies and then distribute funding to maintainers.  
[Github Sponsors](https://github.com/sponsors){:target="_blank"} is one example of this model in general but, at the moment, I do not se it having big traction nor significant impact.  
And in MS ecosystem there is [.Net Foundation](https://dotnetfoundation.org/){:target="_blank"} that should do similar but they ended up doing absolutely nothing (zero funding), existing only as a name on papar.  

&nbsp; Finally a Recommendation for everyone would be to find a project that interests them which they also need and use, and could allocate some spare time to it. There is always a need to help with open question, improve documentation and samples, make tests, solve issue, add new functionalities and other ways of contribution. Later if you have a problem/idea make your own fully FOSS, and after a few of those one might become cFOSS or set it up as such from start.  
&nbsp; The Rule of thumb could be that 1 in 3 to 5 projects might be significant enough to have cFOSS while others would be fully FOSS (another case of Pareto). There is useful info on *opensource* : [starting-a-project](https://opensource.guide/starting-a-project/){:target="_blank"} and [getting-paid](https://opensource.guide/getting-paid/){:target="_blank"}. As for the companies they also can make sure [Open-Source tools are safe](https://www.forbes.com/councils/forbestechcouncil/2022/05/10/12-ways-companies-can-ensure-open-source-tools-are-safe-and-sustainable/){:target="_blank"}.

License types comparison:

| Name             | Type    | Code <br />public | Distribute & <br />Modify | Price     | Examples         |
| ---------------- | ------- | ----------- | ---------------  | -------------------------- | ---------------- |
| fFOSS            | Regular | Yes         | Yes              | fully Free and permissive  | MIT, Apache, BSD |
| **cFOSS**        | Dual    | Yes         | Yes              | cond. Free up to threshold | cF-1M            |
| sFOSS            | Dual    | Yes         | Yes              | semi Free, paid commerical | GPL(s)           |
| OpenCore         | Special | Yes         | Yes              | paid for premium features  | -                |
| Source Available | Regular | Yes         | Yes/No           | paid or freemium           | BSL              |
| Closed Source    | Regular | No          | No               | paid or freeware           | proprietary      |

More info:
1. [medium/the-sustainability-of-open-source](https://goldglovecb.medium.com/the-sustainability-of-open-source-7ec0390f58e8){:target="_blank"}
2. [medium/open-source-is-struggling](https://medium.com/@jankammerath/open-source-is-struggling-and-its-not-big-tech-that-is-to-blame-cfba964219f8){:target="_blank"}
3. [medium//how-we-maintain-a-healthy-open-source](https://medium.com/spiffworkflow/how-we-maintain-a-healthy-open-source-project-2e6d7115f668){:target="_blank"}
4. [medium//the-silent-uprise-of-paid-open-source](https://prasannamestha.medium.com/the-silent-uprise-of-paid-open-source-309b8d9ffc41){:target="_blank"}  
5. [dev.to/the-hidden-cost-of-free-open-source](https://dev.to/opensauced/the-hidden-cost-of-free-why-open-source-sustainability-matters-1jk7){:target="_blank"}  
6. [hendrik-erz.de/open-source-has-a-sustainability-crisis](https://hendrik-erz.de/post/open-source-has-a-sustainability-crisis){:target="_blank"}  
7. [unlockopen.com/towards-a-sustainable-solution](https://speaking.unlockopen.com/5JrQdv/towards-a-sustainable-solution-to-open-source-sustainability){:target="_blank"}
8. [dual licensing a model that works](https://www.linkedin.com/pulse/why-open-core-gpl-dual-licensing-model-works-mark-curphey/){:target="_blank"}

Leave a message: [IP comment Form](https://docs.google.com/spreadsheets/d/e/2PACX-1vS2z9KBq6jiePC8rfPdAcd_b0jtfE_8gPAXPvbKV45fRenyA0fKSSTWmbMA1pd3f4yYiFTr6Wq8Dq5z/pubhtml?gid=2013428247&single=true){:target="_blank"} (comments [list](https://docs.google.com/spreadsheets/d/e/2PACX-1vQYCQRmyTGP2q3GphttZcEae9GlXohAqYy77GIdvVsh5deOfzo-M8J_S_gworsgvkH2klOfLmBoHzQO/pubhtml?gid=1455445651&single=true){:target="_blank"})  
List of all referenced [**Links**](https://docs.google.com/spreadsheets/d/e/2PACX-1vS2z9KBq6jiePC8rfPdAcd_b0jtfE_8gPAXPvbKV45fRenyA0fKSSTWmbMA1pd3f4yYiFTr6Wq8Dq5z/pubhtml?gid=2013428247&single=true){:target="_blank"}  

Infopedia blog subscription Form - [Newsletter](https://docs.google.com/forms/d/e/1FAIpQLSfgtWNZVkNP9pATa0RNWj7eNoMz6XVo5D2T2m14hLLE8J78lg/viewform?usp=dialog){:target="_blank"}  
Supported by [***codis.tech***](https://codis.tech/){:target="_blank"}

<center>QR Link to page</center>
![QR Link](https://quickchart.io/qr?text=https://infopedia.io/solution-to-opensource-sustainability/)









