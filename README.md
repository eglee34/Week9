# Week9

For this assignment, I created 4 honeypots: mhn-honeypot-1 Ubuntu - Dionaea with HTTP, mhn-honeypot-2 Ubuntu - Snort, mhn-honeypot-3 Ubuntu - Snort and Ubuntu - Wordpot, mhn-honeypot-4 Ubuntu - Glastopf. At one point, I decided to see what it would be like for one honeypot to have two scripts, so honeypot 3 had two and the rest had one. Out of all of these, I ran into q error. Honeypot 4 (Glastopf) was the second one that didn't work, probably because when the command for Glastopf was entered it returned an error for the setup tools being old.

Snort was the only one that picked up payloads, Snort (both honeypot 2(97 attacks) and 3(159 attacks)) and Dionaea(1597 attacks) were the only honeypots that ended up being attacked, with Dionaea being the honeypot that got the most attacks, while WordPot and Glastopf didn't get any attacks.

The main problem encountered was from honeypot 4, since the error when it was being set up occurred, so honeypot 4 was unusable. Other problems were from the MHN Admin Console not loading in the browser, but eventually everything loaded and I was able to continue with the assignment.
