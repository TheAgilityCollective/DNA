---
title: Email conventions
prev_section: unconference.html
next_section: hand-signals.html
---

Email conventions
=================

How do we get transparency without email overflow?

Answer: a single mailing list (the "team list"), plus a few simple subject line conventions to sort out important stuff from chatter.

By default, reading team mail is optional. The only "must-reads" are the ones with OBS or OSA in the subject.

> We've had this convention for many years and it works great, because it has an subtle but important impact on how we communicate. Normally, a mailing list forces the *receiver* to decide what's important to read or not. Now we shift that responsibility to the *sender*. Think about it: every email on the team list involves *one sender* and *many receivers*, right? So we save a lot of time if we burden the sender rather than the receivers.

RTN = "Read this now!"
------------------

So RTN is basically an announcement. Everyone should read it, but no response is needed.

Examples:

-   RTN: Date for next conference
-   RTN: New Crisplet started

RAR = "Read and respond!"
-------------------------

> It's kind of like RSVP, which by the way is a French acronoym for "Répondez s'il vous plaît" which literally means "Reply if you please". But we really do want a response (or at least an action) so skip the "if you please" part.

Examples:

-   RAR: Let's update the happiness index!
-   RAR: Printing new business cards. Who needs?

Sometimes an RAR has a deadline:

-   RAR 12 Sep: Sign the updated team contract

BUN = "Heads up, here's a bun!"
---------------------------------

> We use the [Bun Protocol](bun-protocol.html) to route client requests.

These emails are optional, they are mostly for people looking for a new gig. Anyone who gets a client request that they can't take themselves will usually send a BUN email. The BUN prefix means we are applying the [Bun Protocol](bun-protocol.html), so we try to be really clear and write things like "I'm taking this bun".

Examples:

-   BUN: Lean training @ ANZ
-   BUN: Agile Coach needed for company X

Another variant of this is DOU (= dough). That means the email contains a lead that might turn into a bun, for example if someone heard a client mention that they may need another consultant.

-   DOU: Company Y may need coaching

Email filtering
---------------

The subject line conventions above make it really easy to create email filters to separate out the unimportant stuff. Gmail example:

    to:team@theagilitycollective.com -firstname.lastname@theagilitycollective.com
    subject:-RTN -RAR -BUN

The filter will identify any email that is sent to the team list, and not directly to me, and doesn't have RTN/RAR/BUN in the Subject. For these emails, configure Gmail to skip the Inbox and apply the label "Collective". That way you could respond quickly to RTN/RAR/BUN and then cherry-pick among the other emails at your leisure.

It's up to each individual. The important thing is that everyone knows that you can't expect everyone to read your email unless you write RTN or RAR.

Keep long discussions off the list
----------------------------------

For these use [Slack](http://www.slack.com). Often a conversation starts on email, and then when it gets chatty someone suggests that we continue the conversation on Slack, so people who are interested can opt in.

Keep conflicts and sensitive stuff off the list
-----------------------------------------------

Email is a terrible medium for personal conflicts and sensitive discussions, plus it can really sour up the general climate of the team list. We want people to look forward to reading those emails, not dread them! So we try to keep that stuff off the list.

Better to meet and talk, or call each other, or at the very least have a direct email thread instead of involving the whole team.

So if an email conversation starts turning ugly, the involved people will usually notice and take it off the list.

We don't mind conflict and debate. It's just that email (especially the team list) is a lousy forum for it.

Other informal email conventions
--------------------------------

These additional subject prefixes can be used from time to time. 

-   **WOP** (boast): "I'm proud of something and want to boast a bit!". If you're proud of something, why not sing it out loud and get some pats on the back!
-   **OFFTOPIC**: "This doesn't really have anything to do with Crisp, but what the heck..."
-   **PROF** (proofread): "Please proofread my article & help me improve it"
-   **DAGBOK** (diary): "Here's what's going on in my life right now". Always interesting to read!
-   **HELP** (help): "I need help!"
