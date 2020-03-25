
---
title: '[SCOT] SCT rewards may fluctuate more than 20% in a minute'
permlink: scot-sct-rewards-may-fluctuate-more-than-20-in-a-minute
catalog: true
toc_nav_num: true
toc: true
position: 9999
date: 2019-06-26 13:09:48
categories:
- sct
tags:
- sct
- palnet
- aaa
- weedcash
- spt
thumbnail: 'https://cdn.steemitimages.com/DQmNUYttPwL2nEhCGRXSxp3WnEt4W63d9jwYKXLHiPGinPM/image.png'
sidebar:
    right:
        sticky: true
widgets:
    -
        type: toc
        position: right
---


Hello @holger80, I am delivering the message on behalf of steemcoinpan team, in particular from @kopasi.

We found that SCOT(here, SCT) rewards for postings may fluctuate greatly, when the votes from major stakeholders (users who staked SCT a lot) come in during a short period of time. We would like to know whether there is a way to stabilize (or reduce volatility) of reward numbers.

---

I have translated your article, [https://steemit.com/steem-engine/@holger80/code-optimizations-for-scotbot](https://steemit.com/steem-engine/@holger80/code-optimizations-for-scotbot), and checked the formular with other korean community members.

We have suspected that "pending_rshares" may increase vastly when promotion-encouraging IDs including kopasi, sct.adv, sct.min, and supporters (in total, they are about 30% of the total staked SCT) vote in a short period of time, and it would result in large fluctuation(especially decrease, as pending_rshares would go up a lot) of rewards for postings.

In particular, if there are postings close to payout, the effect will be critical. 

---

So we did an experiment, and one user (@realmankwon) took a video of what happened during 5 minutes when these "whale" accounts voted several times. Please see: [https://drive.google.com/file/d/11IOIrhuUsqZikCitWAEeriJf6frUESSD/view?usp=sharing](https://drive.google.com/file/d/11IOIrhuUsqZikCitWAEeriJf6frUESSD/view?usp=sharing)

As you may see in this video, reward numbers exhibit very high volatility.

---

Previously, when steem-engine had some update/bug fixes, we have seen a big drop(to 1/2 ~ 1/4) of rewards and some users have complained about it. We thought that it would be temporary issues that will not happen as SCOT improves. 

However, there were claims that rewards decreased right before the payout even without any updates, and that's why we examined this issue further. There are some users who worry about unstable payouts - you know, it sucks to see that your posting rewards go down a lot from what you've expected a minute ago before the payout.

We would love to hear from you about how to solve this issue.

- - -

This page is synchronized from the post: ['[SCOT] SCT rewards may fluctuate more than 20% in a minute'](https://steemit.com/@glory7/scot-sct-rewards-may-fluctuate-more-than-20-in-a-minute)
