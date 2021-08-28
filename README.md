# CheckPass
 This script anonymously checks a password using an api on the website [Have I Been Pwned] (https://haveibeenpwned.com/Passwords) to see if it has been compromised. The script locally converts the password to a SHA1 hash the first 5 characters of which are polled against a database of over 613,584,246 previously compromised password hashes. Finally the script prints a hash of the password and the amount of occurnences if any in the database.
