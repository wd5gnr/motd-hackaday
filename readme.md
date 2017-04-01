# Hackaday RSS reader for motd
## Public Domain
## Al Williams al.williams@awce.com

You need a few common pieces of software you probably already have and if you don't, get them from your package manager:

banner
curl
tput
grep
sed
bash

You almost certainly have the last 4, by the way.

Make sure 51-hackaday is executable and try running it to make sure
it all works:

   ./51-hackaday

Then move or copy it to /etc/update-motd.d (you'll need to be root)

     sudo mv 51-hackaday /etc/update-motd.d

That's it.