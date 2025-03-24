---
title: Difficult Truths for our Harsh Times — Have security & privacy research, and the students we have trained, actually made the world a better place?
date: 2025-03-24
lastmod: 2025-03-24
---

Not everyone will miss Ross Anderson.

Ross was not afraid to speak truths that made people uncomfortable. His ideas and arguments threatened the beliefs, status, power, ego, and bank balances of others — often those with power. His writings and talks undermined proponents of hardware attestation, chip-and-pin authentication, and surveillance, to name just a few. Many of those threatened by what Ross had to say professed to be faithfully working to serve the public. Many likely believed they were.

Most of those of us celebrating Ross&apos;s life are members of the scientific and academic community that researches security within the context of computing, technology, and public policy. While we may not be policymakers or titans of industry, almost all of us are privileged to have knowledge and skills that give us far more power over our use of technology than the average citizen, and to train others to use that power. Most of us believe that we use the skills and knowledge we are privileged to possess to faithfully serve the public.

We can honor Ross by embracing discomfort and questioning our own beliefs that we, individually and as a community, are using the powers we possess to make the world a better place.

Examining this question *should* indeed make us uncomfortable. I first met Ross in 2002, while I was a graduate student, at a time when the study of security was just starting to receive the attention it deserved. It was an exciting time, and many of us had high aspirations and ambitious goals. Yet, it is hard to imagine a metric of success for serving the public – real living people – for which our field can claim anything but defeat.

Imagine the questions we would have to answer if our prior selves could hold a post-mortem of the goals and aspirations we started with in the early 2000s.

#### Have we protected people&apos;s identifiers or other key information?

*No*. It&apos;s nearly impossible to participate in modern society without taking actions that will eventually lead the the leak your government identifiers, financial data, phone number, and physical address.

What have we achieved?

1. Nearly every member of the public now has enough free credit reporting to last until the heat death of the universe, and
2. we have numbed the public to seemingly-endless disclosures that their data has been compromised.

#### Have we protected against scams, extortion, and other cybercrime?

*Nope*. Any successes we can claim in harm-reduction have been counteracted many times over by our contributions to harm-amplifying technologies.

We helped create the cryptocurrency technologies that have enabled rug pulls, ransomware, pump and dump schemes, romance scams, and human enslavement. We helped breathe new life into organized crime and authoritarian governments that harbor criminals. We helped finance [\$197 million dollars of spending in the 2024 US election to fund candidates who support this cancerous &lsquo;*industry*&rsquo;](https://www.followthecrypto.org/)[^industry], eclipsing the lobbying of all other industries. We succeeded in making the lobbying of the fossil fuel industry seem like noise – [a mere \$60 million!](https://www.statista.com/statistics/788056/us-oil-and-gas-lobbying-spend-by-party/) – by comparison.

[^industry]: Using the word &lsquo;industry&rsquo; generously to describe enterprises that produce no actual goods.

Cryptocurrencies alone may have produced the *magnitude* of impact that, back in 2002, Ross and I might have hoped the field would achieve. Alas, that impact was in the wrong direction.

#### Have we built a robust cybersecurity industry to at least attempt to protect the public?

*Still No*! What we have built is an industry to protect business from the public. Walk the floors of our biggest industry conference, RSA, and you will see the extravagant display of the wealth of the [cybersecurity industry that purports to bring in nearly \$200 Billion dollars a year](https://www.statista.com/outlook/tmo/cybersecurity/worldwide). Yet, you will be hard-pressed to find one of the roughly [600 vendors](https://www.rsaconference.com/library/press-release/rsa-conference-2024-opens) that is making products to protect actual people (&lsquo;consumers&rsquo;, in industry-speak).[^exception] Economic theorists might tell us that the public should reap the benefits of a cybersecurity industry that protects businesses from losses that might otherwise be passed onto consumers but, in practice, much of what the industry sells are compliance products to protect businesses from negligence lawsuits. The net effect is that these expenditures protect business from members of the public who might seek recompense for the prices we pay for business&apos;s *endless* stream of security failures.

[^exception]: The notable exceptions that proves the rule are password managers. Some were founded with the mission of serving consumers, but shifted focus to enterprises after being purchased by private equity ([LastPass](https://en.wikipedia.org/wiki/LastPass)) or receiving investments from venture capitalists (1Password).

What&apos;s worse, this industry produces security products that require highly-privileged access to customers networks and data and that, if compromised, can have devastating security consequences. Yet, these companies almost all start out as start-ups that prioritize shipping product over safety. Even as companies mature, the code is rarely as robust as it should be given its criticality. Over and over, the products of our cybersecurity industry have themselves introduced new vectors through which attackers can compromise the organizations that are in greatest need of protection and that invest the most in it. Or, as in the case of [CrowdStrike](https://en.wikipedia.org/wiki/2024_CrowdStrike-related_IT_outages), security products have introduced entirely new failure modes that require no adversarial behavior to disrupt lives and incur billions of dollars of losses.

#### Have we secured citizens from authoritarian technology?

*Mostly we have done the opposite.* We have given authoritarians greater control over their citizens&apos; access to technology.

In 2002 most citizens had *technological autonomy*: their primary computing device was a personal computer onto which they could install or compile any software they wanted. Their government might ban certain software and make it hard to find, but if a government wanted its citizens to have access to modern technology, it had to give them access to general-purpose computing devices that were at least capable of running *any* software.[^tpms]

[^tpms]: Back in 2002, trusted platform modules appeared to be the biggest threat to technological autonomy.

Then, Apple and Google discovered they could make more money if they monopolized the means through which software was distributed on their platforms. When they introduced iOS and Android, they took away users&apos; autonomy to install the software of their choosing. It&apos;s not like we could ignore the consequences: at roughly the same time (2009) Amazon [removed books](https://www.npr.org/2009/08/03/111487759/amazon-removes-books-from-kindle) that they consumers had already purchased from the devices they bought from Amazon and mistakenly believed they owned.

Security technologists at Apple and Google told users that their loss of autonomy was in their best interest. Many of us in the security research community agreed that the only way to prevent malware was to prevent users from having the choice to download and install software of their own choosing. Our culture of blaming users for failures of software architecture[^malware] helped industry justify robbing users of their autonomy. And, once industry could restrict users&apos; access to software, governments could force industry to impose their own restrictions. Today, governments can decide whether we are allowed to use applications that can perform encryption, and they have turned our computing devices are used to surveil us, reducing our privacy.

[^malware]: Malware was so prevalent on personal computers because their security model gave all software the power to corrupt other software by default. Mobile operating systems sandboxed applications from each other by default, and evolved fined-grained permissions systems so that users would not need to give the games they downloaded access to their camera, contact information, and stored passwords.

#### Do we still even aspire to build trustworthy systems to keep people safe?

*Depressingly, No*. In an Orwellian twist, we have allowed industry to pervert the very meanings of such basic concepts as safety and trust. Back in January 2002, the year I met Ross, Bill Gates laid out a corporate vision for what &lsquo;Trust&rsquo; meant to tech&apos;s de-facto leader of the time:

> Users should be in control of how their data is used. Policies for information use should be clear to the user. Users should be in control of when and if they receive information to make best use of their time. It should be easy for users to specify appropriate use of their information including controlling the use of email they send.
>
> …
>
> There are many changes Microsoft needs to make as a company to ensure and keep our customers’ *trust} at every level – from the way *we* develop software, to *our* support efforts, to *our* operational and business practices.[^Microsoft]

[^Microsoft]: Emphasis in quote added to highlight that when *Microsoft&apos;s} founder and then-CEO used the word &lsquo;trust&rsquo;, he used it to hold *Microsoft} accountable to its users. The original January 15, 2002 memo is reproduced available via a [10-year retrospective from Microsoft](https://news.microsoft.com/2012/01/11/memo-from-bill-gates/) and a [Wired article from January 17, 2002](https://www.wired.com/2002/01/bill-gates-trustworthy-computing/).

Regardless of what you think of Gates, Microsoft&apos;s history[^disclosure], or the extent to which Gates and Microsoft were able to deliver on those principles, Gates was willing to state without ambiguity that &lsquo;trust&rsquo; meant being accountable to customers about the quality and safety of its products.

[^disclosure]: Disclosure: I worked at Microsoft Research from 2007 until 2016.

Contrast that with today&apos;s doublespeak, where today&apos;s tech companies use &lsquo;*trust and safety*&rsquo; to mean protecting users from others, so that their company can control how their users&apos; data is exploited, where their users&apos; attention goes, and to obscure how this all happens so that users remain as oblivious as possible. This industry, littered with companies we helped birth and students we helped train, has redefined *trust and safety* to mean moderating others&apos; content and access. These companies intentionally elide even the slightest consideration that their platforms, such as social networks and [dating apps](https://stuartschechter.org/posts/safety-tips-dating-apps-omit/), might not adequately protect the public&apos;s data or might sell that data to advertisers, governments, political parties, and anyone else willing to pay.

This capture of our lexicon has been enabled by the students our academic institutions have produced and by our academic research institutions themselves, which hold conferences dominated by industry members and that embrace this language.

Industry thrives on the talent that our research institutions train and we thrive by consuming the funding they provide. Our research institutions welcome with open arms those who advanced their careers by enabling the industry&apos;s most abusive oligarchs. In addition to cozying up to companies and institutions that we know to be actively trying to subvert the public good, many of us not only accept research funding from them, but brag about that research funding when brandishing our credentials. And we don&apos;t question when our institutions do it.

Many of our most prestigious scientific research institutions have helped to promote technologies that harm the public. Cornell Tech [advertises its placement](https://admissions.tech.cornell.edu/admitted/we-are-one-of-the-best-universities-for-blockchain/) on [CoinDesk&apos;s Best Universities for BlockChain](https://www.coindesk.com/layer2/2022/09/26/best-universities-for-blockchain-2022/). [Stanford](https://fdc.stanford.edu/) and [Berkeley](https://haas.berkeley.edu/blockchain/research/) (the latter funded by cryptocurrency company Ripple) are also actively promoting their links to the &lsquo;*industry*&rsquo;. Our institutions show no shame for doing so because too few of dare question the propriety of our colleague&apos;s research funding[^Epstein], and too many would ostracize those courageous enough to do so.

[^Epstein]: Until recently major universities accepted research funding from known pedophiles.

## Have we improved the study of the science of security?

*Not significantly*. Our scientific culture perpetuates systems that subvert the truth. Scientist&apos;s success and prestige is not judged by the meticulousness of our methods or our caution against overstating the implications of our findings, but on how significant we can make our findings appear, how many papers we can publish, and whether these appear in venues of the highest prestige. We gather for exclusive meetings amongst our research-area elites, to decide how we will distribute prestige, and pat ourselves on the back for performing this &lsquo;community service&rsquo;. We spend the most time and effort explaining to a super-majority of researchers submitting results that their work does not meet &lsquo;the bar&rsquo; for the arbitrarily chosen acceptance rate that we believe maintains our desired the aura of prestige. We put service to our employers, industry organizations, and program committees over service to science and budding scientists.

We know these institutions pervert how we conduct and evaluate science to serve their interests, but we choose complicity rather than risk our degrees, jobs, promotions, and social status. Perpetuating system that we know to pervert science may be the default choice, *but it is a choice*. It is a choice we make make unconsciously every time we dedicate a service hour to peer reviewing a work to determine if it&apos;s worthy of prestige, when we could instead be helping others conduct more meticulous research and communicate it to the public more clearly.

I do not believe that most of us don&apos;t want to make pro-social choices and better the world. And some members of our community have had huge positive social impact. Two worthy examples are efforts to democratize public key infrastructure (Let&apos;s Encrypt) and secure messaging (Signal), both through not-for-profits. These wins came from principled people who believed that it should be safer for *everyone* who wants to publish information on the web, and safer for *everyone* to communicate with others over telecommunications networks. There&apos;s a lot to learn from these *exceptional* wins, and I do not mean to diminish them, but we can&apos;t get the most out of them if we fail to understand that they are, indeed, *exceptions*. If we don&apos;t own up to our field&apos;s failures, examine our roles in those, and learn from these failures, we can&apos;t expect to fail less in the future.

## What can *we* do?

One of the underlying problems for those of us who work in security, privacy, trust, and safety is the ambiguity over *who* we are most obligated to protect. Many of us in public-facing security roles purport that protecting the public (*users*) is our paramount goal when, in fact, our first obligation is to protect our employers.

Ambiguity and deception about our motives and obligations underlie many of the failures we need to own up to: the cybersecurity industry that protects companies from the public&apos;s negligence lawsuits instead of making us safer, the cryptocurrency industry that protects organized crime&apos;s payment infrastructure at the cost of public safety, and big tech platforms that use security to justify reducing our technological autonomy and handing it over to authoritarian governments. These failures were made possible by security technologists who contributed to the illusion that they were part of an endeavor that served the public, or who stood silent while their peers engaged in such deceptions.

Whereas doctors are bound by the ethical code of nonmaleficence, there is no code that obligates those of us working in security protect and inform the public when the public interest is in conflict with that of our employer.[^disclosure-laws] Whereas doctors can assert that they must do not harm lest they violate their oath and put their future employability at risk, we have no code to fall back on if our employers explain that killing our metaphorical patients will maximize shareholder value and that we are thus contractually obligated to do so.

[^disclosure-laws]: Breach-disclosure laws attempt to remedy a symptom of this problem, but not the underlying cause.

We should have our own codes of nonmaleficence. We&apos;ll inevitably need more than one. That&apos;s fine. They can be like open-source licenses. A few will become popular and most people will find one of the popular ones works for them.

Not everyone needs to adopt a code of nonmaleficence for such codes to have a meaningful impact on our field and the public. Even if only a small but influential minority of us adopted codes of nonmaleficence, the public would soon learn which companies and organizations were willing to employ those of us who did and which were not. Those who know of peers who have adopted a code of nonmaleficence, but choose not to do so, will have only themselves to blame when they are asked put their shareholders over the public after being asked to present their work as that of protecting the public.

In addition to codes of nonmaleficence, we need to build a culture where we expect more from each other and help each other anticipate and make hard choices. We need to ask hard questions of each other, and we need to expect our peers to ask hard questions of us.

  - &ldquo;Are you confident that your are making the choice that makes people&apos;s lives better?&rdquo;
  - &ldquo;Are you actively looking for ways you may be causing harm or are you actively trying not to look?&rdquo;
  - &ldquo;Is your ability to gauge whether this choice furthers the public interest compromised by it furthering your own interest or that of your employer?&rdquo;
  - &ldquo;Are you confident you are the protagonist in this story?&rdquo;

We need to all be a little more willing to ask ourselves, colleagues, friends, and those with power over us questions that are certain to make us all uncomfortable and some of us even angry.

Those most likely to be angered off will be people in authority who fear having their power undermined. We have to be prepared for them to brush us off with indignant responses, such as &ldquo;Who died and made you the asshole who thinks it&apos;s okay to ask that kind of question?&rdquo;

Funny you should ask. It was *Ross Anderson*.

## Acknowledgments
I am grateful to Frank Stajano and the RossFest organizing committee for including a work that greatly deviated from their submission guidelines in trying to honor Ross. This work benefited greatly from the ideas, incisive comments, encouragement, and proofreading of/by Ben Edelman, Cormac Herley, Maritza Johnson, Andy Ozment, and Bruce Schneier.