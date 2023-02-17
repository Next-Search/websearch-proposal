# New Location
Please see the updated article available here: https://github.com/davidshq/next-search/blob/main/S01.%20Human%20Augmentation.md
# The Trust Network

## Introduction

The greatest challenge for any search engine is in ensuring that the results shown to the end user are the best results available. Over time the methods by which results are ranked have evolved many times over.

Search Engines have ordered pages by the date they were crawled, alphabetically, based on developer included meta tags, keyword density, implicit and explicit search actions by users...and the list goes on.

Some of the improvements made to result quality calculations have been about understanding the content itself but much of the effort has been spent trying to outsmart marketers and malicious actors who attempt to game the results and ensure their product/service/site is shown at the top of the rankings.

We believe The Trust Network can significantly improve the quality of results while decreasing the spamminess of results. How? We are so glad you asked!

## Calculating Trust

> "\[A\]_ll individuals are given the opportunity to participate, but their influence is based on publicly earned merit – what they contribute to the community._" - [The Apache Way](http://www.apache.org/theapacheway/)

NeSE uses accounts to attribute value to an individual's explicit and implicit feedback on results quality and that determines how we value that feedback. If we stopped here we'd be susceptible to manipulation just like other search engines...so we don't stop there, we add the trust network layer.

### How an Authority Score Increases

NeSE provides each user \(excluding anonymous users\) with an authority score. This starts quite low and can be increased over time through several methods:

1. A trusted user explicitly trusts your user account.
2. You provide substantive contributions over time to the engine \(explicitly and/or implicitly, with the former carrying significantly more weight than the latter\).
3. You verify your identity in ways that ensure you are an actual individual making legitimate contributions.
4. You verify your credentials on a specific topic.

For example, an individual who is a professor in history at an accredited university might receive some trust on that topic due to their verifiable expertise. Similarly, someone who works for a company might receive some trust associated specifically with information regarding that company. Other areas that might lend themselves to this sort of crediting of trust include book/journal authorship, owning/contributing to respected site on x topic, etc.

We recognize that some of the ways in which trust is granted above may be easier for some to accumulate than others and that this could result in one group having inordinate power over the results as compared to another. 

We won't go into detail on how we intend to counter this propensity but will provide three high-level plans on our part:

1. We will actively seek out trustworthy members of communities which may be marginalized using the above methods and provide them with additional initial authority to help offset such imbalances.
2. We will accept applications for any individual to see an authority grant extended to any particular subset of individuals who may be marginalized. 
3. We will monitor significant divergences in preferred results as user's are willing to share data about themselves to ensure that a group is not marginalized.
4. We will intentionally be integrating multiple perspectives into our results. Individuals may submit an application for any topic to include an alternative perspective section in the results.

### How We Prevent Gaming of Authority Scores

If we stop here we are _still_ susceptible to manipulation, individuals and/or machines can open accounts and increase their authority by granting trust to one another. That is why we take things yet a step further:

To ensure clarity, in the following description we will use the terms "grantor" and "grantee".

"Grantor" is the individual who is granting trust to another user.

"Grantee" is the individual who is the recipient of a Grantor's trust.

* When individual account \("grantor"\) trusts another account \("grantee"\), the grantor's account reputation becomes linked to the grantee's account reputation.
* If the grantor account trusts a spammy grantee account the grantor will take a penalty to its own reputation just as the spammy grantee does. 
* The negative penalty increases exponentially - that is, initially it may only be a few points off the grantor's authority score but as the number of grantee accounts performing detrimental actions increases we will use a multiplier to rapidly deduct from the grantor's authority.

This linkage need not be only first level trusts. For example:

* If JohnDoe \(grantor\) trusts JaneDoe \(grantee\) and JaneDoe \(grantor\) trusts IAmSpammy \(grantee\) those penalized will be: IAmSpammy \(most penalized\), JaneDoe \(moderately penalized\), JohnDoe \(lightly penalized\).

This doesn't make us impervious to manipulation but it will make manipulation much harder. In order to gain authority one has to provide value and build relationships. To build relationships others must trust you to an extent where they are willing to suffer a penalty if you behave poorly.

It is likely that malicious activity will still occur through account compromises, but using the trust network we should be able to quickly isolate the impact of such manipulation and \(hopefully\) restore account access to the appropriate individual. That is, when a trusted user begins performing or being linked to negative behavior this is likely a sign that the individual's account has been compromised.

## Acknowledgment
We want to acknowledge our significant indebtedness to the marvelous innovations in automatic trust calculations pioneered by [StackOverflow](https://stackoverflow.com/) and [Discourse](https://www.discourse.org/).

Unfortunately, trusting someone to be correct is not the same as trusting someone to be kind. StackOverflow has published several [articles regarding making a kinder environment](https://stackoverflow.blog/?s=welcome+wagon). See also [here](https://stackoverflow.blog/2018/04/26/stack-overflow-isnt-very-welcoming-its-time-for-that-to-change/), [here](https://stackoverflow.blog/2019/03/28/the-next-ceo-of-stack-overflow/), [here](https://stackoverflow.blog/2020/04/09/the-unfriendly-robot-automatically-flagging-unwelcoming-comments/), and [here](https://stackoverflow.blog/2019/10/10/iterating-on-inclusion/).
