This application will read the mailbox data (mbox.txt) and count the number of email messages per organization (i.e. domain name of the email address) using a database with the following schema to maintain the counts.

CREATE TABLE Counts (org TEXT, count INTEGER)

You need to download sqlite to your computer to execute this program successfully since this piece of code is a database practise for those who is trying to learn or recall basic database concept.
