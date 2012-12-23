# Mailstats

Simple mail count stats for Gmail, seeing the changes over time in labels.

E.g. tracking Inbox, Actionable, MailingList, Google automatic labels, Spam....

The tracking could be shown on a simple time graph. Recording is done periodically, every 1h, 1d or 1w, to see short term (not that important) and long term trends.

Should be able to:

* authenticate with Gmail
* get list of labels
* get number of messages for each label

Have to think out some good structure, since every label is different for people. Need to handle deletion and creation of labels. Maybe all on client side?

What's the use of it? What can one get out of this? Besides the [Inbox Zero][inboxzero] initiative, is there other particularly important part?

[inboxzero]: http://inboxzero.com/ "Inbox Zero homepage"
