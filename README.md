# ListOfPromotedTweets
List of Twitter accounts that promote tweets. Useful for mass blocking purposes
to clean your timeline. Project started by [Nic Losby](twitter.com/blurbdust).

## Using This List

To block all promoted accounts: Twitter > Settings and Privacy > Blocked 
Accounts > Advanced Options > Import a List

Upload the file completelist.csv. Twitter will display all of the accounts 
contained on the list, and if you're following any of the accounts it will 
move them to the top of the list and automatically uncheck the "block" button.
If you want to manually review the thousands of accounts on the list, now is the
time to do it. Otherwise, continue and Twitter will begin blocking everyone who
pays to pollute your timeline. This may take some time, but it will happen in
the background. 

## Contributing To This List

This list exists to weed out promoted advertisements from the twitter timelines.
It does not exist for pushing political agendas or blocking celebrities you don't
like. Try keep your contributions to promoted accounts.

Twitter > Settings and Privacy > Blocked Accounts > Advanced Options > Export
Your List

1. Download your list as "myBlockedAccounts.csv" 
2. `grep -v -f completelist.csv myBlockedAccounts.csv` will show if you have
blocked accounts that aren't on the complete list. If you do, great! Add them to
the list.
3. `grep -v -f completelist.csv myBlockedAccounts.csv >> completelist.csv`
4. Pull Request.
