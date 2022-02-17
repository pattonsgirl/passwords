# Hashcat

* [https://hashcat.net/hashcat/](https://hashcat.net/hashcat/)
* `./data/shadow` file of password hashes
* `./dictionaries/` various wordlists for hashing

## The setup

Previously you all created user account with dummy passwords and submitted them to pilot.  Hashcat needs them in a particular format so I have altered them all and placed them in 
`./data/shadow`.  Entries look like this:

```
$6$d1gWjURFVstVjUpd$6eBD1QlS7HMwmimKpVeFWUCB9iE7LHaNNlMis3kZLBZhH8vbuUxPaKLFxGYdKnJAWB9i8rEA8vhZiKBhOJEOH0
$6$PD9hEdJXwkI2toeV$YLjTZbAm5PEVMhxuSj3NPPJnUrQ.sh15QpbGsW1PXtJtgCd7yCvnqK/nFj830Vrx9QPahVZUawh397tJuXww60
...
```

Where each line is a section from a user's `/etc/shadow` entry.

In this exercise you will be attempting to recover as many passwords as you can from the supplied shadow file.

You will need to download the dictionaries and shadow file via github website (windows) or via wget as follows:
