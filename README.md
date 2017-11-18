## filter-journal-spam

spamassassin white-list to avoid traffic from predatory publishers

### What Is This?

The [spamassassin](https://github.com/apache/spamassassin) program provides
an efficient and robust framework test incoming email headers and body text.
It also allows user-local overrides, for both guanranteed _white-listing_ (to
guarantee acceptance) and _black-listing_ (to guarantee a high-enough score
that the mail is filtered as non-desirable).

I have been hand-editing and growing such a file since 2002, and noticed that
almost  all entries  in recent  years  were in  fact due  to spammy  journals
inviting me  to send  something. Presumably  in hopes  of later  collecting a
processing fee.

Single-person editing works, collaborative editing and merges scales better.
So here is an attempt of making a 'wider' list.  Who knows, we may even end
up with a new plug-in just how the some of the filters are already
distributed.

### What This Is Not (Yet?)

A grand plan to integrate with
[spamassassin channels and rule updates](https://wiki.apache.org/spamassassin/RuleUpdates). I
am at this point unsure how active these are. I think my (Debian/Ubuntu)
Linux servers actually fetch rule updates automagically. But I have no idea
about the process in which those rules get formed and validated.

### Status

As a start, I just dropped (relevant parts of) my current
`~/.spamassassin/user_prefs` for others to see, copy, pull-request against.
I have not really thought through yet where to take take this, but as a start
I figured I could least make the list public.  With that, the process goes
from 'one person editing one file' to _maybe_ more than one person doing
so. 

### License

GPL (>= 2)
