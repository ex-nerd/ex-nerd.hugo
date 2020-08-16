+++
date = "2010-08-27T08:01:40Z"
title = "plus addressing for email"
categories = ["Tech"]
+++

Like most tech-savvy people, I have more than a handful of email addresses, and I like to guard them against being shared without my permission (and track back to the company that did the sharing).  When you run your own mail server, this is quite easy -- just make up a custom email address for every company you do business with.  Unfortunately, this gets somewhat cumbersome after awhile, and definitely isn't a solution for the general public.  Enter [plus addressing](http://en.wikipedia.org/wiki/Plus_addressing#Sub-addressing), a method built into most mail servers that allows users to modify their own email addresses with additional data that can be tracked but does not interfere with mail delivery.

This would be the perfect solution if it was actually supported by the majority of online account providers (and in the 6 years since this article was originally written, things aren't much better).

<!-- more -->

The technique for plus addressing is simple:  add a plus and a word after the username portion of your email address.  For example, `exnerd@example.com` would become `exnerd+shopping@example.com`.  This way, you can create a custom email address for certain types of transactions, or even for every company you do business with online.  The format is well-documented and supported by my favorite [free email provider](http://gmailblog.blogspot.com/2008/03/2-hidden-ways-to-get-more-from-your.html).  It works great, too, until you run into a company that knows very little about technology.  Like all of my credit card companies, and about half of the online stores I shop at.

Seriously.

Even without the feature of using the plus to create an ignored portion of the email address, the plus character has been valid for use in email addresses since [RFC 822](http://tools.ietf.org/html/rfc822), which was written in 1982!  That RFC has been replaced a few times (the current is [RFC 6854](http://tools.ietf.org/html/rfc6854)), but support for the plus character hasn't changed.

In conclusion, I would highly recommend using plus addressing to sort and track your incoming mail.  I would also recommend that whenever you run into a so-called technologically-adept company like your credit card provider, to ask them why they are violating an email formatting standard that is over 30 years old.
