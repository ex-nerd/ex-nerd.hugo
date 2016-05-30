+++
date = "2012-09-29T07:33:42Z"
title = "keeping your digital life secure"
categories = ["Tech"]
+++

There have been a number of high-profile stories recently about hacking and digital identity theft, along with a rash of hacked yahoo.com email accounts that usually lead to scams/cons. When a number of my friends and family members fell victim to these hacks (thankfully not to the scams) and discovered that the collateral damage could be worse than the hack itself, I decided that I should put together some recommendations to help them avoid more trouble in the future.

<!--more-->

Keep reading for a thorough explanation of how to recover from these email hacks, along with a bunch of recommendations for how to limit the chance of them happening, or the damage done if they do occur.

### The scam

Most of the scams I've seen from these hacked accounts are [stranded traveler scams](https://www.google.com/#q=stranded+traveler+scam). The scammer sends an email purporting to be your friend, mugged and stranded in some foreign country with no cash to pay for a hotel or buy tickets home (yet somehow they still have their computer to send email!).  When you reply to ask your friend for more information, your reply is actually redirected to the scammer, who set up a sneaky Reply-To address on the original email that looks almost identical to the correct one.  For example, if your friend's email address is <code>user@example.com</code>, the reply-to address might be <code>userr@example.com</code> (notice the second r?).

So when you reply to your friend, either to ask how they're doing, or even just to tell them that their account has been hacked, they never even get the message.  When you reply to one of these kinds of messages, it's safest to address a new email to your friend, so that you can be sure that you are sending the message to the correct person.

If you are the one who got hacked, your priorities should be:

1. Change your password and clear out that bogus reply-to address (here's how to do it for [yahoo](http://email.about.com/od/yahoomailtips/qt/et_reply_to.htm) and [gmail]http://support.google.com/mail/bin/answer.py?hl=en&amp;answer=7991)).
2. Contact as many friends as you can to let them know <strong>not</strong> to reply to the bogus/scam email.
3. Contact your email provider to let them know about the hack, and about the bogus email address that has likely been set up to collect all of your friends' replies.
4. Change your password anywhere else that you use your email address to log in (e.g. facebook, twitter, amazon.com).
5. Figure out what (if anything) the hacker deleted from your email account.

### Passwords
When you choose a new password, it's important to remember that most of the passwords we use are <a title="A great XKCD comic about password strength." href="http://xkcd.com/936/">hard for humans to remember and fairly easy for a computer to guess</a>.  Take a look at the comic linked to from the previous sentence before you choose a new password.  It's a lot easier for you to remember four words (e.g. "correct horse battery staple") than a bunch of semi-random characters.

If you want to take things a step further, check out a password vault like [1Password](https://agilebits.com/onepassword).  At $50, it's fairly expensive, but it's also very easy to use, and has tools to help create and organize those large random-character passwords that you still need to occasionally use because a lot of websites don't actually let you use long passwords.  I was finally convinced of its worth when I realized that my wife had no way to access any of our financial information if I wasn't around to help (yes, I've reached that point in life where I feel the need to take precautions against things like getting run over by high speed vehicles).  It only took a few minutes to show her how to use 1Password, and now her computer and phone have access to all of the same passwords that mine do.

If you use GMail and want to be extra-secure, look into turning on [2-Step Verification](http://support.google.com/accounts/bin/answer.py?hl=en&amp;answer=180744).

### Backups

Major email providers like Yahoo, Google, or Microsoft make <strong>no assurances</strong> that the data stored on their servers is safe from accidental deletion.  It's unlikely, but not unheard of, for accounts to randomly disappear or users to find their inboxes suddenly empty.  Even if you have no fear of your email account getting hacked, you should at least trust in the small chance that your email may someday vanish or be locked away where you can't get at it.  Feel free to keep your email around as an archive, but if you have important documents that you don't want to lose, make sure you download them to your own computer where you can be sure they will be backed up.

When I say "backup", I usually refer to "remote backups", meaning storing your backup files somewhere far away.  Local backups like Apple's Time Machine are great (you can never have too many backups, and local backups make for much faster recovery), but they won't get you your files back if your computer is stolen or if your house burns down.

In my mind, there are two kinds of remote backups, too.  Easy-access services like Dropbox or Google Drive can provide free storage for your files, and allow easy access from multiple locations, but they usually have the same disclaimers as email providers, releasing them of responsibility if your files ever fail to appear.  However, I still encourage you to look into one or more of these services (there are others, but these are the top three):

* [Dropbox](http://db.tt/zxULLdP): At 2GB free, Dropbox gives you the least amount of free storage (though you can add some additional space for free by doing things like completing their online tutorial), but their user experience is by far the best, and by referrals and other gimmicks, you can get considerably more free storage.  This is probably the most popular provider (it's certainly my favorite), especially because of how easy they make it to share files (it took me under a minute to set up a folder for my whole family to share photos, including showing my parents how it worked).  <em>Disclaimer: the link provided is a referral link.  If you sign up via my link, each of us will receive an additional 500M of free storage space once you install the app.  I'm more than happy to admit my bias toward you choosing Dropbox first.</em>
* [Google Drive](https://www.google.com/intl/en_US/drive/start/index.html): Google Drive is a new addition to Google Docs, their web-based word processor, spreadsheet, and other office tools.  If you have a Google account, you already have a Google Drive with at least 15GB of storage and just need to download and run the application on your computer.  Choose this one if you use Google Docs.
* [Microsoft SkyDrive](http://windows.microsoft.com/en-US/skydrive/home): Like Google, Microsoft uses SkyDrive to integrate with their web-based office tools.  They also give you a total 7GB of space to store your files.  If you use a lot of Microsoft products, this is probably your best bet.

All of these services include applications that you can install on your computer and smartphone.  They work by creating a folder on your computer to synchronize, and any file you put there will find its way to their servers.  Even better, these services will keep your files in sync between all of your computers, if you happen to have more than one.  If you don't want to decide right away which one to use, there's no reason that you can't run more than one at the same time (I have accounts with all of them, though I only run Dropbox on my computer/phone).

For true backups, I recommend [CrashPlan](http://crashplan.com/).  There are other services out there, but I won't even bother providing comparisons (there are plenty of other sites out there to do that).  If you keep around an external hard drive, their free software will handle your local backups, and will even let you share your hard drive out to friends and family to trade backup space (e.g. offer to back up each other's most important files), keeping your things encrypted so that your friends will only host the files but never be able to see their contents.  Most importantly, their monthly rates are more than reasonable if you would like to back your files up to their own servers (at most $5/month for unlimited storage for one computer, and as low as $1.50/month if you have under 10GB of files to back up).  They even have a reasonably-priced "Family Plan" that allows you to protect up to 10 computers.

Being a true backup service, CrashPlan makes assurances that your files will be there when you need them, keeps them encrypted so no one but you will ever see the contents, allows you to use extremely secure passwords, and offers a number of concierge style services (e.g. for a reasonable fee, they will mail you a hard drive containing your requested backup restore files).

At the very least, go out and buy yourself some USB thumb drives and/or an external hard drive, and use the free version of CrashPlan to copy files over every few weeks.  If you go with a thumb drive or two, make sure to keep at least one of them somewhere other than your computer (e.g. at work or in your car's glove box).  CrashPlan's encryption will keep your personal information safe even if someone else happens to run across the disk and tries to use it.

### Email
All of the big free email hosts these days seem to provide a way to connect up a standalone email program via [IMAP](http://en.wikipedia.org/wiki/Imap).  If you run Windows, then Outlook Express is already installed.  On MacOS, Apple's included Mail.app program will do the job nicely.

The most important thing to know about IMAP is that it only mirrors the email that's on the server.  This means that if something or someone deletes the files on the server, your local mail program will happily synchronize up that empty mail box.  What you <strong>do</strong> get with these programs is an easy way to back up (and to some extent, restore) your mail data, as long as you remember to do it.

Here are instructions for [Outlook Express](http://support.microsoft.com/kb/270670), [Mail.app](http://www.maclife.com/article/howtos/how_back_and_restore_mail_lion), and [Thunderbird](http://kb.mozillazine.org/Importing_and_exporting_your_mail) (which is a great free email client for Mac, Windows, and Linux).  Remember that if you subscribe to a backup service like CrashPlan, exporting to a folder on your hard drive means your mail archives will get backed up along with everything else, and a good provider like CrashPlan will even let you restore them from specific points in time.

Also, I'm personally a big fan of [GMail](http://mail.google.com/mail/signup) (not to mention all of Google's other great free services), so don't feel too bad ditching Yahoo or that @comcast.net email address that came with your internet connection if you want something else.

### Browsers
It used to be a big deal for techie folks to try to push their friends/relatives to use [Firefox](http://www.mozilla.org/firefox/) or [Google Chrome](https://www.google.com/chrome/), but in all honesty the latest versions of Internet Explorer (Windows) and Safari (Mac) are actually pretty secure.  The most important thing to remember is to <strong>keep your browser up to date</strong>.  If you run an older version of Windows or MacOS, then I would highly recommend taking a look at Firefox or Chrome, since their engineers keep them up to date with the latest security patches a lot faster than Microsoft and Apple supply new versions of browsers to old computers.

### That's it
I know this was a bit long, but I've actually tried to keep it as lightweight as possible (it's far from a comprehensive overview of every option out there) while still providing good information that covers more than just my personal favorites.  If you take anything away from this, please let it be:

<ul>
    <li><strong>Use strong passwords.</strong>  Numbers and symbols are great, but longer passwords are better than short ones full of random characters you can't easily remember.</li>
    <li><strong>Keep your software up to date.</strong>  Software engineers work hard to keep their software free of security holes, but it won't help you unless you actually get the latest versions.</li>
    <li><strong>Back up your files.</strong>  Pay for a service and/or buy yourself a handful of USB thumb drives to store your most important files.</li>
</ul>

<strong>Disclaimer:</strong> Most of the links for this page were found with a quick web search, so please let me know in the comments if they ever stop working and I will find new/better ones.  Only the [Dropbox](http://db.tt/zxULLdP) link contains any sort of referral that might be perceived to benefit me.
