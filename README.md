# Capture the Flag (CTF) Guide for UF Students
## A quick and dirty (unofficial) guide to getting started in participating in CTFs with UF's Kernel Sanders team

_Disclaimer: The author apologizes in advance for any errors, inaccuracies, or omissions, but he, possibly like the reader, is a relative newcomer to the world of CTFs._

If you are reading this, it may be because you:

* Need to meet the CTF participation requirements for a class such as CIS 4204 (Penetration Testing: Ethical Hacking).
* Desire to earn leeway (i.e., sorta extra) credit towards your Final Exam for CIS 4204 or CIS 4930 (Malware Reverse Engineering).
* Keep hearing how cool and fun CTFs are and just want to see what the fuss is all about.

This short guide is written to help you jump-start your foray into participating in CTFs with Kernel Sanders.  It is not intended to teach you how CTFs actually work or how to succeed at them (as I, a beginner myself, definitely am unqualified to do this).

Here are some preliminary thoughts to keep in mind:

* This (unofficial) guide is intended for those who wish to participate with the University of Florida's (UF's) Kernel Sanders team.
* Kernel Sanders is the nickname given to the University of Florida Student Infosec Team (UFSIT).  See https://ufsit.club/#/
* Participating with Kernel Sanders may be a requirement of your course instructor for credit. In other words, you can't go it alone.
* Kernel Sanders typically will particpate in a CTF nearly every weekend of the year.
* Most CTFs start on a Friday and end on a Saturday or Sunday.  There are exceptions, of course.
* Kernel Sanders may even sometimes participate in two or more CTFs simultaneously in any given weekend.
* To see what the pool of candidate CTFs for an upcoming weekend looks like, just head over to https://ctftime.org/.
* It is very common to hear from beginners how hard it is to solve CTF challenges.  There is only one way to get better at these, and it's to invest the time.

Here is how to get started:

* Join the UFSIT_ctf_squad Discord server.  Discord is a messaging, collaboration, and community platform, somewhat like but also quite different from Slack, Teams, etc.  A link to join UFSIT_ctf_squad is:  https://discord.gg/h2qEXqc48p.  Do pay attention at the ensuing Web page and only type in a username if you do NOT already have an account; otherwise, click the link a little lower as indicated if you already have an account.  Please note that this link has a limited lifespan.  If it no longer works, reach out to someone who can provide you with a fresh one, e.g., the UFSIT Competition and Development Chair or someone in your class who might be in the know.
* Send an instant message to the Kernel Sanders lead administrator asking to be added to the "CTF TEAM" category and explain why (e.g., "I am in Dr. Wilson's Malware Reverse Engineering class, and I would like to get 50 solves so that I may skip my final exam").  At the time this page was published, the administrator's handle on Discord is @noopnoop (who also happens to be the UFSIT Competition and Development Chair).  You do not want to wait until the day a CTF starts to make the request.
* Once you've been added to the "CTF TEAM" category, beginning on the Wednesday before the weekend you desire to particpate, periodically check the #general channel in the Discord "CTF Team" category to see in what CTF competition(s) Kernel Sanders will be participating.  Sometimes, a decision may not be made until the day of.
* Once the decision is made, Kernel Sanders will post or pin its login credentials for the CTF, comprising of a username (or e-mail address) and password.  If it's a post, it will be in the #general channel.  If it's a pinned message, look for the thumbtack (likely red in color) in the upper right corner.  For some CTFs, you first may have to create a personal user account with the CTF and then join the Kernel Sanders team using the team credentials provided on Discord.
* Although it's not "necessary," most CTF participants would strongly suggest that you to set up a virtual machine ahead of time.  Options vary, but one example could be Kali Linux running in a VMware Workstation.  There are numerous tutorials available for accomplishing this (e.g., YouTube).
* _At my signal, unleash hell!_

Here are a few suggestions and nuggets of knowledge complete beginners might find helpful:

* Because CTFs are an international affair, it is common to see start and end times represented in UTC (Universal Time).  To convert from UTC to Eastern Time:
    * If it's presently Eastern Standard Time, subtract five (5) hours, e.g., 22:00 UTC = 17:00 EST (using military time).
    * If it's presently Eastern Daylight Savings Time, subtract four (4) hours, e.g., 22:00 UTC = 18:00 EDT (using military time).
* After signing in to a CTF, you likely will see something resembling a Jeopardy-style scoreboard.  This board will have various challenges falling under certain categories, including but not limited to:
    * Crypto:  Some type of cryptography is involved.
    * Reverse Engineering:  Self-explanatory.
    * Pwn:  I'm not familiar with these, but I believe they typically involve binary exploitation.  Apparently, in slang, to pwn something means to "own" it.
    * Web:  Self-explanatory.
    * Forensics:  These seem to vary but may involve a variety of the above and/or something that doesn't neatly fall in any category at all.
* Each of the challenges has a score associated with it.  The higher the score, the more difficult the challenge is.
* Some CTFs are set up so that each time a team solves a challenge, the number of points to be awarded is reduced.
* Once you solve a CTF challenge, you will be presented with a flag, the form for which may vary, but usually looks something like flag{#######}.  Somewhere on the CTF's website, this form will be indicated.  Here are a few actual flags from prior CTFs:
    * flag{squarectf}
    * CYCTF{c@3$@r_c!ph3r}
    * sun{lucky-octal-encoding-is-the-best-encoding-method}
* To gain credit for solving the challenge, you must enter the flag where indicated.  Once it is solved and points are awarded, then this particular challenge comes off the board.  In other words, you can't get credit for solving a challenge that's already been solved.
* It's a good idea to make an announcement in the appropriate Discord channel, e.g., #pwn, as soon as you've solved a challenge so that others don't unknowingly continue working on the same one.  It also may serve double-duty as notification for leeway credit purposes.  Regarding leeway credit, definitely ascertain what the official protocol is to document solves.  In my opinion, a sound idea is to post something in Discord as previously stated and also direct message the appointed liaison. 
* If you want to increase the odds of solving a challenge, it's best to sign in right at the opening bell, while the easier challenges are still unsolved.
* Some CTFs will release new challenges periodically throughout the event.
* It is more common than not for two or more Kernel Sanders teammates to collaborate on challenges.  Such chat typically occurs in the specific Discord channel representing the challenge type, e.g., #crypto.  However, be cognizant of the impact this will have on your ability to earn leeway credit in a course offering it.  For instance, in Penetration Testing: Ethical Hacking, it may be that a maximum of two students can work together to get leeway credit.  Consequently, if three worked together on a particular challenge, then drawing straws may be in order.
* It also is common to find two or more individuals working through the night on challenges, chatting with each other on Discord, crashing for a few hours when the sun comes up, and then resuming efforts.
* Some challenges may take 10 minutes to solve.  Alternatively, you may spend 10+ hours on a challenge and never solve it.  The first legitimate one I solved was a Crypto challenge during my seventh CTF and it took me a little less than two hours.  Conversely, I have double-digit hours on other ones that I never could solve.
* It helps to be comfortable at a Linux command line and to be familiar with the netcat utility, which appears in many CTF challenges.
* Don't be afraid to ask for help on Discord.  The more seasoned folks are very happy to lend a hand.  Things are much more productive if you state what efforts you've undertaken until you reached a roadblock.  (This is contrasted with someone who starts out with "I don't know what I'm doing.  Where do I begin?")
* You are allowed to use whatever resources you can find to aid you with your efforts; however, read the published rules first at the respective CTF website.
* Most CTFs have a Discord or Slack channel you can join.  It's not necessarily helpful with finding solutions directly, but sometimes the organizers will post something timely on there about there being a problem with one of the challenges that they are working to resolve, or that they just released a hint for a challenge.  After the event, I have seen folks freely discuss solutions there, or even on an Internet Relay Chat (IRC) board.
* Also after the event, write-ups for solutions start trickling in at https://ctftime.org/.  (If I was a little wiser - and had more time - I would start studying these.)
* If you have zero background in specialized areas such as Web or Reverse Engineering, I personally feel that the Crypto category may be the most intuitive one to tackle as a beginner.  Alternatively, you may want to explore Forensics or Miscellaneous.  If you're reading this during a Spring semester, you may be taking Malware Reverse Engineering, which means that you're focusing on reverse engineering and pwn challenges.  As uttered in the movie _Taken_, "good luck."

### Frequently Asked Questions (FAQ)
_Coming soon_...
