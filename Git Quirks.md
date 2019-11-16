#Git Quirks and Workarounds

##Multiple Userspaces on OS X
If utilizing github on os x for multiple usernames, to switch the commandline login you must delete the credentials from keychain.
This can be done by opening keychain, searching through the category "All Items" for "git", and deleting the entry of type "Internet Password".
