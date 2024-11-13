---
title: "October 2024 Patchstack Bug Bounty Competition"
date: 2024-11-01T07:14:34-04:00
draft: false
tags: ["wordpress"]
---

WordPress has been my latest rabbit hole for hacking and bug bounty. For the past couple of months I've been tinkering with it on a local docker container and learning as much as I can about source code review. Up until this point I've only hunted for bugs occasionally on public bug bounty programs with marginal success. Fast forward to today and I am completely zoned in on WordPress plugins and having the most success (and fun!) hacking on them. Here's a summary of how I did in the month of October on [Patchstack's](https://patchstack.com/bug-bounty) Monthly Bug Bounty Competition.

**TL;DR**: Patchstack has a monthly bug bounty competition and they made history with 1571 valid bugs reported in a single month. This month I submitted 23 bugs (18 valid, 5 rejected) and finished in 12th place. :partying_face:

[Patchstack Blog Post](https://patchstack.com/articles/nearly-1000-plugins-closed-during-wordpress-security-cleanup/)

### Background

Patchstack is one of a handful of WordPress security platforms that offers security services and bug bounty. Each month they hold a bug bounty competition where hackers can submit bugs in plugins and themes for a chance to win cash prizes. It's a bit different than traditional bug bounty for several reasons, but as someone who just started gaining some traction hacking on WordPress the competitive nature of it was incredibly motivating for me. My goal this month was to finish in the top 10 and I fell a bit short of my goal, but I'm not at all disappointed. I was participating in a historic event with some of the most talented WordPress hackers in the world and somehow managed to finish in 12th place. 

Since October is "Cybersecurity Awareness Month" they adjusted their scope to accept submissions in plugins and themes with less than 1,000 installs, which ultimately helped the WordPress ecosystem by cleaning up outdated, vulnerable plugins. Likewise it opened up a massive attack surface and was highly beneficial to me in terms of improving my skillset. I've included a breakdown of the bug types I found as well as their severity in a table below.

If this sounds interesting to you then I recommend checking out the [guidelines](https://patchstack.com/articles/bug-bounty-guidelines-rules/).

Before going into the results here are some cool stats from the month. Much more info in their [blog post](https://patchstack.com/articles/nearly-1000-plugins-closed-during-wordpress-security-cleanup/)!

> | :chart_increasing: Interesting Stats    | Submission Totals    | Percentage    |
> |---------------- | --------------- | --------------- |
> | Valid    | 1571    | 94% (of all submissions)   |
> | Most by Single Researcher    | 534    | 34%    |
> | Top 4 Hackers   | 1084   | 69%   |


### Results

Even though my goal was top 10, I'm still very pleased with how it went for me. Below is a breakdown of the bugs I submitted. A few of these were collaborations and/or leads from some friends.

**:card_index: Breakdown by Class**

> | Class   | Submissions    |
> |--------------- | --------------- |
> | XSS   | 9   |
> | LFI   | 1   |
> | Broken Access Control   | 3   |
> | SQLi   | 1   |
> | Privilege Escalation   | 2   |
> | Account Takeover   | 1   |
> | Arbitrary File Download   | 1   |
> | Arbitrary File Deletion   | 1   |
> | Arbitrary File Upload/RCE   | 4   |

**:warning: Breakdown by Severity**

> | Severity   | Submissions    |
> |--------------- | --------------- |
> | Critical   | 5   |
> | High   | 6   |
> | Medium   | 7   |

**:no_entry: Breakdown by Rejection**

> | Reason   | Submissions    |
> |--------------- | --------------- |
> | Duplicate   | 2   |
> | Low/No Impact   | 2   |
> | Out of Scope   | 1   |

In a future post I'll do a writeup of one of my findings from this event.

Thanks for reading!

-ghsinfosec
