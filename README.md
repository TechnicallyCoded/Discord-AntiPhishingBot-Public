# Discord AntiPhishingBot Public Blacklist

***ALL RIGHTS RESERVED***

*This can be translated to, for the average person, but is NOT limited to, the 
following restrictions:* You may NOT redistribute the list provided in any way 
(especially if claiming it as your own) or include sections of the list (or the 
entire list) in your own works. I also reserve the right to update these terms 
at any time without notice.

**Exceptions:**
- The lists in this repository may be USED (aka, retrieved at runtime) by your 
application as long as there is an OBVIOUSLY VISIBLE reference to the origin of 
the data to the end user such as a link to this repository. The reference must 
be at least as visible as the service using the data.
- Forks of the repository are allowed only if using GITHUB's built-in forking 
function for the sole purpose of making pull requests. By using github's 
method, it creates a link back to the original repository. (Forks made without 
a link back to the original repository are NOT tolerated)
- **Examples of tolerated use:**
  - Example #1: If you have an application or program which uses this list as part
  of only one of the available features, the reference to the source of the data 
  used must be clearly visible next to the option to enable/disable the feature.
  - Example #2: If your application's sole purpose is to provide a service which uses 
  the data available in this repo, you must reference the source along with the
  installation steps or withing the first 100 words of the description of the
  application.

## Description
This blacklist is a compiled list of all scam links that I could find or were
contributed to the repository by others.

## Invite the discord bot
You can invite my own discord bot which uses this list to automatically delete 
messages that match any of the entries listed in blacklist.txt. I provide the 
bot's service as-is, with no guarantees for uptime, lack of false positives or
lack of false negatives. I may also choose to take the bot offline without any 
notice if I so desire. If scam links are not removed you may contribute changes 
to add the missing malicious links (see [#Contributing](./README.md#contributing)).
However, if you do notice any unwanted behavior you may ask nicely for me to 
correct it using a github issue.
- Invite link: [click here to invite the bot to your server](https://discord.com/api/oauth2/authorize?client_id=888061627239383051&permissions=292057902146&scope=bot)

## Setup
- Invite the bot
- Ensure that the bot has the permission to view and delete messages in each
  channel you want protected.
- To test that the bot is working you can send a message with the following 
  fake link: https://testinglinktomakesuretheantiscambotcandeletemessages.testonly

## Donations
I took the time to put this together so that you don't have to. If you wish to
thank me you can star the github repo and optionally donate a few dollars if 
you want to give this bot the best chance of staying online and, in general, 
keeping the list of blacklisted domains as up to date as it can be. 
[Donation link](http://paypal.me/technicallycoded)

## Contributing
You may contribute to this list by creating a pull request. All modifications 
contributed to this list are owned by me once accepted. You waive all 
copyrights of your contributed modifications. (You may still brag about how
much you have contributed but I don't need people claiming they own more than
I do just because they contributed a lot xD)
