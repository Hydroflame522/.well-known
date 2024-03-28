# Github Domains for Discord Connections
Discord has this stupid thing called discord connections and you can connect domains to your profile, so this is a way to use your *.github.io link from your account as your discord connection link if you're trying to link a lot of connections.

# Tutorial
1. Go to discord connections, click domain, and enter ***your github username***.github.io
2. go to HTTPS Verification on that same discord popup and copy the content it says to copy
3. Fork this github repository with the same repository name (.well-known)
4. Replace the content of the 'discord' file with the copied content
5. Close the domain verification discord popup
6. Then go to repository settings and go to github pages in the settings
7. In the Pages menu, select Source: 'Deploy from a Branch' and Branch: 'main' and click save
8. Go back to the main repository page and wait for github pages to deploy '.well-known'
9. After a few minutes for it to deploy, go back to discord domain connections, reenter your domain, and it should verify it as a connection

Another useless connection for your useless discord profile
