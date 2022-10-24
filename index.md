---
layout: page
title: Security Venues with No Page-Limit
tagline:  a short list
description: This website lists all Cybersecurity venues that do not impose any limit to the length of the References/Appendices in the submitted papers
---


### What?

This website contains a comprehensive list of those cybersecurity venues that accept papers without any limit to the amount of pages dedicated to **references** _and_ **appendices**.

#### How?

I simply take consider well-known venues (i.e., conferences, workshops or symposia) and check their Call for Papers (CfP): if such CfP specify that there is no limit for appendices/references, then I will list them in this website. Specifically, the list of venues is taken from this source: [Guofei Gu ranking](https://people.engr.tamu.edu/guofei/sec_conf_stat.htm).

### List
The list is provided in the table below. For each conference that has "unlimited" pages, the table also reports: the link to the most recent CfP, the amount of "base" pages (i.e., those subject to limitations), the template (DC=Double Column), the year in which the venue started to accept unlimited "extra" pages (since 2011), whether the venue accepts Systematization of Knowledge (SoK) papers, and whether the venue has a (dedicated) Artifact evaluation.

**Note:** I will also include venues that accept "unlimited" pages _at the time of submission_, but for which the final paper must fit within a specified limit (e.g., for USENIX Security); such venues are marked with an asterisk "(*)". The ordering of the venues is the same as in [Guofei Gu ranking](https://people.engr.tamu.edu/guofei/sec_conf_stat.htm) (the only venue reported in this table and not listed in that ranking is IEEE SaTML, since it's completely new). Venues that are not "active" anymore (e.g., [MALCON](https://malwareconference.org/), whose last edition was in 2017) are not included (see [here]({{ BASE_PATH }}/pages/guofeiGu.txt) for a list of included/excluded venues)



{% include_relative pages/tables/short_unlimited.md %}

I will update this list regularly, but feel free to [email me](mailto:giovanni.apruzzese@uni.li) if you spot a mistake (e.g., a missing venue), or if you want to refresh it sooner. Please include "[SNPL]" in the subject of the email (I will give proper credit to any contribution!). Alternatively, you can _post a message_ on the (public) [GitHub project](https://github.com/secnopagelim/secnopagelim.github.io/discussions) related to this website.


### Why?
This website was inspired by the "Rump Session" of the [7th IEEE European Symposium on Security and Privacy](https://www.ieee-security.org/TC/EuroSP2022/program.html) (held on Wednesday, June 8th, 2022). In the few hours before the Rump Session I came up with a "draft" version of the website, which consisted in a simple spreadsheet (still accessible at: [https://tinyurl.com/noapplim](https://tinyurl.com/noapplim)) that I shared with the attendees of the Rump Session. For various reasons, I decided to "upgrade" such version into a proper website.

The main reason is to _help cybersecurity researchers in choosing to which venue_ they should submit their papers---since having plenty of space for appendices may be a deciding factor. To the best of my knowledge, there are no resources that aggregate all such information in a single list.

Nonetheless, there are deeper reasons that motivated me in creating this website, albeit most of them are subjective and stem from my (recent, and arguably limited) experience---both as a reviewer, and as an author. Put simply, it is to _send a message to our community_. 
As all such considerations are personal, I will not discuss them here: feel free to read them in the dedicated [blog-post that I made on my personal website](https://www.giovanniapruzzese.com/posts/2022/secnopagelim).


### Venues with Page Limits

For completeness, below is a table of those venues (also from [Guofei Gu rankings](https://people.engr.tamu.edu/guofei/sec_conf_stat.htm)) that, at the time of writing, **have page limits** for their appendices (if any). For each "limited" venue, the table reports: the latest CfP, the length of base pages, the template, the length of "extra" pages (for appendices and/or references---an asterisk * denotes unlimited pages for references), and whether it accepts SoK and Artifacts. (credit to [David Evans](https://www.cs.virginia.edu/~evans/) for recommending to include also this table!)


{% include_relative pages/tables/short_limited.md %}

(last update: October 1st, 2022)


#### Long lists

I am also curating a "longer" list of all venues, which is accessible at the following page: [Long List]({{ BASE_PATH }}/pages/long)
