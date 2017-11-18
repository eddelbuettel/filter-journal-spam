## filter-journal-spam

spamassassin white-list to avoid traffic from predatory publishers

### What?

The [spamassassin](https://github.com/apache/spamassassin) program provides an efficient and robust framework test incoming
email headers and body text.  It also allows user-local overrides, for both guanranteed _white-listing_ (to guarantee
acceptance) and _black-listing_ (to guarantee a high-enough score that the mail is filtered as non-desirable).

I have been hand-editing such a file for many years, and noticed that almost all entries in recent years were in fact due to
spammy journals inviting me to send something. Presumably in hopes of later collecting a processing fee.

Single-person editing works, collaborative editing and merges scales better.  So here is an attempt of making a 'wider' list.
Who knows, we may even end up with a new plug-in just how the some of the filters are already distributed.

### Status

As a start, I just dropping (parts of) my current `~/.spamassassin/user_prefs` for other to see, copy, pull-request against.
I have not really thought through where to take take this, but as a start I figured I could least make the list public.

### License

GPL (>= 2)
