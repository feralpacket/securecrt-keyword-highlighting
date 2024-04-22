# securecrt-keyword-highlighting

##**New:**

Added **feralpacket_iosxr_2024.ini**.  These are changes for IOS XR.  Not sure if there will end up being some conflicting regex I use for IOS and IOS XE.  So, I'm creating a separate .ini just in case.  Work in progress.  Will probably not be complete until some time after the CCIE SP bootcamp I'm attending this June.

Starting with SecureCRT version 9.3, the length of the regular expression for each line was increased.  

**feralpacket2023.ini** ( and **feralpacket2024.ini** ) will start using longer regular expressions.  This will allow me to do some consolidation and reduce the number of lines.  Maybe, someday. 

Note, the regular expressions I had been using where up to 256 characters long.  **shrug**

From SecureCRT_HISTORY.TXT:

  > - Increased the character limit for keywords from 246 to 2048,
  >   which allows more complex regular expressions to be specified
  >  for keyword highlighting.



My original blog post from 2016.

**SecureCRT Text Highlighting**

https://feralpacket.org/?p=299

Updated blog post from 2019.

**Regular Expressions For SecureCRT Keyword Highlighting – Update**

https://feralpacket.org/?p=817


This contains an updated .ini file that I shared with the Routergods and Art of Network Engineering communities.

http://dentonj.freeshell.org/
