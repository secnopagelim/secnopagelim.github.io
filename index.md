---
layout: page
title: Security Venues with No Page-Limit
tagline:  A short list
description: This website lists all Cybersecurity venues that do not impose any limit to the length of the References/Appendices in the submitted papers
---


## What?

This website contains a comprehensive list of _all_ cybersecurity venues that accept papers without any limit to the amount of pages dedicated to **references** _and_ **appendices**.

### How?

I simply take all well-known venues (i.e., conferences, workshops or symposia) and check their Call for Papers (CfP): if such CfP specify that there is no limit for appendices/references, then I will list them in this website. Specifically, the list of venues is taken from this source: [Jianying Zhou ranking](http://jianying.space/conference-ranking.html)

## List
The list is provided in the table below.
For each conference that has "unlimited" pages, I will also report: the link to the most recent CfP, the amount of "base" pages (i.e., those subject to limitations), the template (DC=Double Column), the year in which the venue started to accept unlimited "extra" pages (since 2011), whether the venue accepts Systematization of Knowledge (SoK) papers, and whether the venue has a (separate) Artifact evaluation.

**Note:** I will also include venues that accept "unlimited" pages _at the time of submission_, but for which the final paper must fit within a specified limit (this is the case, e.g., for USENIX Security). These special cases are marked with an asterisk "*".




| #   | Venue (Acronym) | CfP Link                                                                  | Base Pages | Template   | Since                                                                    | SoK? | Artifact? |
|-----|-----------------|---------------------------------------------------------------------------|------------|------------|--------------------------------------------------------------------------|------|-----------|
| 1   | IEEE EuroS&P    | [2023](https://www.ieee-security.org/TC/EuroSP2023/cfp.html)              | 13         | IEEE, DC   | [2021](https://www.ieee-security.org/TC/EuroSP2021/cfp.html)             | Y    | N         |
| 3   | ACM CCS         | [2022](https://www.sigsac.org/ccs/CCS2022/call-for/call-for-papers.html)  | 12         | ACM, DC    | [2016](https://www.sigsac.org/ccs/CCS2016/call-for-papers/index.html)    | N    | Y         |
| 4   | NDSS            | [2023](https://www.ndss-symposium.org/ndss2023/call-for-papers/)          | 13         | NDSS, DC   | [2020](https://www.ndss-symposium.org/ndss2020/call-for-papers/)         | N    | N         |
| 5   | RAID            | [2022](https://raid2022.cs.ucy.ac.cy/call.html)                           | 12         | ACM, DC    | [2019](http://www.raid-2019.org/callForPapers.html)                      | N    | N         |
| 6   | PETS            | [2023](https://petsymposium.org/authors23.php#submission-guidelines)      | 12         | PETS, DC   | [2023](https://petsymposium.org/authors23.php#submission-guidelines)     | Y    | N         |
| 7   | IEEE CSF        | [2023](https://www.ieee-security.org/TC/CSF2023/cfp.html)                 | 12         | IEEE, DC   | [2011](http://csf2011.inria.fr/call-for-papers.html)                     | Y    | N         |
| 8   | SOUPS           | [2022](https://www.usenix.org/conference/soups2022/call-for-papers)       | 12         | USENIX, DC | [2011](http://cups.cs.cmu.edu/soups/2011/cfp.html)                       | Y    | N         |
| 9   | IEEE SaTML      | [2022](https://satml.org/participate-cfp/)                                | 12         | IEEE, DC   | [2022](https://satml.org/participate-cfp/)                               | Y    | N         |
| 10  | IFCA FC         | [2022](http://fc23.ifca.ai/cfp.html)                                      | 15         | LNCS, SC   | [2015](http://fc15.ifca.ai/cfp.html)                                     | N    | N         |
| 11  | TCC             | [2022](https://tcc.iacr.org/2022/papersubmission.php)                     | 15         | LNCS, SC   | [2011](https://www.iacr.org/workshops/tcc2011/cfp.html)                  | N    | N         |
| 12  | IEEE SaTML      | [2022](https://satml.org/participate-cfp/)                                | 12         | IEEE, DC   | [2022](https://satml.org/participate-cfp/)                               | Y    | N         |
| 13  | Eurocrypt       | [2023](https://eurocrypt.iacr.org/2023/papersubmission.php)         *     | 30         | LNCS, SC   | [2011](https://www.iacr.org/conferences/eurocrypt2011/cfp.php)           | N    | N         |
| 14  | USENIX SEC      | [2023](https://www.usenix.org/sites/default/files/sec23_cfp_092722.pdf) * | 13         | USENIX, DC | [2011](https://www.usenix.org/legacy/events/sec11/cfp/sec11cfp.pdf)      | N    | Y         |
| 15  | Crypto          | [2023](https://crypto.iacr.org/2023/callforpapers.php) *                  | 30         | LNCS, SC   | [2011](https://www.iacr.org/conferences/crypto2011/cfp.html)             | N    | N         |
| 16  | AsiaCrypt       | [2022](https://asiacrypt.iacr.org/2022/files/AC22-CFP.pdf) *              | 30         | LNCS, SC   | [2014](https://www.iacr.org/conferences/asiacrypt2014/index-1.htm)       | N    | N         |
| 17  | ANCS            | [2023](https://sulab-sever.u-aizu.ac.jp/ACNS2023/cfp.html)   *            | 20         | LNCS, SC   | [2015](http://acns2015.cs.columbia.edu/cfp/)                             | N    | N         |




(I will update this list regularly, but feel free to send me an email if you spot a mistake, or if you want to "refresh" it sooner)

## Why?
**under construction**



### Backstory

This website was inspired by the "Rump Session" during the 2022 edition of the [IEEE European Symposium on Security and Privacy](https://www.ieee-security.org/TC/EuroSP2022/program.html).

In particular, during such Rump Session, I gave a talk in which I discussed about the length of papers in Cybersecurity Conferences. Funnily enough, [David Evans](https://www.cs.virginia.edu/~evans/) (the Co-chair of EuroS&P23) said that "the ideal length of a paper is 0 pages", which is something to which I agree with---in principle. Yet, the discussion was very engaging (I believe it lasted nearly 1 hour), and a lot of interesting points were raised by all the participants (h/t to all those who contributed!).

In the few hours before the Rump Session I came up with a "draft" version of this website, which consisted in a simple Google Sheet (accessible at this link: [www.tinyurl.com/noapplim](www.tinyurl.com/noapplim)) 
For various reasons, I decided to "upgrade" such version into a more comprehensive website.





